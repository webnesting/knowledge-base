# Count signups from any other ad platform

**Last verified:** 2026-11-14 10:44pm

You run ads on a platform and you want it to count each signup your ads bring in. WebNesting has a built-in setting for seven platforms: Meta, Reddit, Google Ads, TikTok, LinkedIn, Pinterest and Microsoft Ads. If your platform is on that list, use the built-in setting. It needs no code. See "Track signups from your ads".

For any other platform, use one of the two ways below.

Each time a visitor sends one of your forms, your site announces it. The announcement never holds what the visitor typed. It says only which form was sent. Tag Manager, or a small piece of code, can listen for that announcement and tell your ad platform.

| | Google Tag Manager | Pasted code |
|---|---|---|
| Best if | You already use Tag Manager | You do not use Tag Manager |
| What you do | Set up a trigger in Tag Manager | Paste the platform's code in Site Settings |

## Way 1: Google Tag Manager

Your site adds an event called `wn_form_submit` to Tag Manager each time a form is sent. You build a trigger on that event and attach your platform's tag to it.

1. In Tag Manager, add your platform's tag. Use the platform's ready-made tag type, or **Custom HTML**.
2. Create a trigger of type **Custom Event** with the event name `wn_form_submit`.
3. Attach the trigger to the tag.
4. Publish the container.

With your cookie banner on, the whole container waits until a visitor allows **Analytics**. A visitor who says no loads none of its tags.

The trigger steps, and how to count one form only, are in [Count Signups in Google Analytics or Google Tag Manager](analytics.md#count-signups-in-google-analytics-or-google-tag-manager). That section also says where to enter your Tag Manager ID.

## Way 2: Pasted code

Use this way when the platform gives you a piece of code and you do not use Tag Manager. Paste it into **Site Settings → Code from Other Services**. See [Code from Other Services](site-settings.md#code-from-other-services).

Follow two rules:

1. Write each script as `<script type="text/plain" data-consent-category="marketing">`. The words `text/plain` stop the script from running at once. The words `data-consent-category="marketing"` make it run only after the visitor allows marketing cookies.
2. Listen for the event `wn:form-submit`. Your site sends it on the page each time a form is sent.

The pattern looks like this. Replace the comment with your platform's own signup call:

```html
<script type="text/plain" data-consent-category="marketing">
  document.addEventListener("wn:form-submit", function () {
    // your platform's signup call goes here
  });
</script>
```

Put the platform's base code and your listener in one script, as the example below does. Then the base code always runs first.

### What happens with the cookie banner

Pasted code written this way waits for the visitor's marketing choice once your cookie banner is on. A visitor who says no never loads the code, so that visitor is not counted.

Code pasted without `type="text/plain" data-consent-category="marketing"` runs for every visitor. The banner cannot hold it back.

## Worked example: X (Twitter) Ads

You need two values from X. Both come from **Events Manager** in your X Ads account:

- Your pixel ID, shown in the base code X gives you.
- The event code of your signup event. It looks like `tw-abc12-abc34`. If you have no signup event, create one in Events Manager, then copy its code.

Copy the values from X, because X can change its code. X's help page is [Conversion Tracking for Websites](https://business.x.com/help/conversion-tracking-for-websites).

1. Open **Site Settings → Code from Other Services**.
2. In **Top of every page**, paste the code below.
3. Replace `YOUR_PIXEL_ID` with your pixel ID.
4. Replace `YOUR_SIGNUP_EVENT_CODE` with your event code.
5. Click **Preview with Code** to check the page, then click **Publish**.

```html
<script type="text/plain" data-consent-category="marketing">
  !function(e,t,n,s,u,a){e.twq||(s=e.twq=function(){s.exe?s.exe.apply(s,arguments):s.queue.push(arguments);
  },s.version='1.1',s.queue=[],u=t.createElement(n),u.async=!0,u.src='https://static.ads-twitter.com/uwt.js',
  a=t.getElementsByTagName(n)[0],a.parentNode.insertBefore(u,a))}(window,document,'script');
  twq('config', 'YOUR_PIXEL_ID');

  document.addEventListener("wn:form-submit", function () {
    twq('event', 'YOUR_SIGNUP_EVENT_CODE', {});
  });
</script>
```

The first part is X's base code. It loads X's pixel and counts page views. The last part is your signup call. It runs each time a form is sent.

### Check that it works

1. Publish, then open your live site in a private window.
2. Allow marketing cookies in the banner.
3. Send one of your forms as a test signup.
4. In X **Events Manager**, look at the event's status. It can take a while to show.

## Before you go live: your privacy page

You are responsible for naming each ad platform on your site's privacy page. Say that you use it to measure which ads lead to signups. WebNesting does not write this text for pasted code or Tag Manager tags.

Visitors in some places, such as the EU, the UK and California, have rights about ad tracking. Ask a lawyer if you are unsure what your page must say.

## Frequently asked questions

**Does a signup count when a form sends the visitor to a thank-you page?**
Yes. The announcement is made before the visitor leaves the page.

**Is a signup counted when I test in the builder or a preview?**
No. The builder and previews do not announce signups, so your tests there never reach an ad platform.

**Can I see which ad brought a signup without any tag?**
Yes. WebNesting counts signups by source, campaign and ad on its own. See [Analytics and Reports](analytics.md).
