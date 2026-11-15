# Track signups from your ads

**Last verified:** 2026-11-15 3:19am

Paste one ID per ad platform, and each platform learns which of its ad clicks became signups. The built-in page covers Meta, Reddit, Google Ads, TikTok, LinkedIn, Pinterest and Microsoft Advertising. For another platform, see [Count signups from any other ad platform](count-signups-any-ad-platform.md).

## Add your IDs

1. Open your site, then **Site Settings**, then **Ad tracking**.
2. Find the platform you use.
3. Paste its ID in the field. The table below says where to find it.
4. Select **Save Changes**.

WebNesting refuses an ID in the wrong format. A short message under the field says what the ID should look like. To turn a platform off, clear its field and save.

| Platform | What to paste | Where to find it |
|---|---|---|
| Meta | Pixel ID (digits) | Meta Events Manager, Data sources, your pixel; the number under its name |
| Reddit | Pixel ID (starts with a2_ or t2_) | Reddit Ads, Events Manager, your pixel |
| Google Ads | Conversion ID (starts with AW-) and Conversion label | Google Ads, Goals, Conversions, your signup conversion, Tag setup, **Use Google Tag Manager** |
| TikTok | Pixel ID | TikTok Ads, Events, your pixel |
| LinkedIn | Partner ID and Conversion ID (digits) | LinkedIn Campaign Manager, Analyze, Insight Tag and Conversions |
| Pinterest | Tag ID (digits) | Pinterest Ads, Conversions, your tag |
| Microsoft Advertising | UET tag ID (digits) | Microsoft Advertising, Tools, UET tag |

Google Ads and LinkedIn count no signup until you fill in both of their values.

## Send signups from your server too (optional)

An ad blocker or a strict browser can stop a tag in the visitor's browser. Meta, Reddit, Google Ads and TikTok can also hear of each signup straight from your site's server, which an ad blocker cannot reach. Each platform matches the two reports of one signup and counts it once.

After you save a platform's ID, more fields appear under it:

| Platform | What to paste | Where to find it |
|---|---|---|
| Meta | Conversions API access token | Meta Events Manager, your pixel, Settings, Conversions API, **Generate access token** |
| Reddit | Conversions API access token | Reddit Ads, Events Manager, Conversions API, **Generate access token** |
| TikTok | Events API access token | TikTok Events Manager, your pixel, Settings, Events API, **Generate Access Token** |
| Google Ads | Customer ID, signup conversion action ID, and a Google Cloud service account key | See the steps below |

For Google Ads:

1. Copy your **customer ID** from the top of Google Ads, beside your account name.
2. In Google Ads, open **Goals**, then **Conversions**, and click your signup conversion. The address in your browser has `ctId=` and a number. Paste that number as the **conversion action ID**. The conversion must be a website conversion.
3. In Google Cloud, turn on the **Data Manager API** and create a service account.
4. In Google Ads, add the service account's email address as a user of your account.
5. In Google Cloud, open the service account, then **Keys**, **Add key**, **JSON**. Paste the whole file into **Google Cloud service account key**.
6. If you reach this Google Ads account through a manager account, also fill in **Manager account ID**.

WebNesting stores every token and key encrypted. After you save one, the field says it is saved but never shows the value again. To replace it, paste the new one and save. A field you leave empty keeps the saved value. To stop the server send, select the bin icon beside the field and confirm.

## Check that it works

Each main ID has a **Send test signup** button. Save your settings, then select it. A new tab opens and sends one test signup to that platform. The test does not change your own signup numbers.

The platform can take a few minutes to show the test. Look on its events or diagnostics page.

## What visitors see

Your tags start when advertising cookies are on for the visitor. Outside the EU, EEA and UK they are on when the visitor arrives, and the cookie banner offers a Reject button. In the EU, EEA and UK, and for a site set to ask every visitor, the tags start after the visitor allows marketing cookies. A visitor who says no is never sent to an ad platform. **Signups by ad** still counts their signup, because that count stays inside WebNesting.

When you save your first ID, WebNesting turns your cookie banner on, because a site with no banner never asks and the tags would never start. A line at the top of the page tells you, with a link to the banner settings. If you turn the banner off later, it stays off.

The tag in the browser tells the platform that a signup happened. It never sends what the visitor typed, such as a name or an email address.

When you save a server token, your server also sends that platform a scrambled (hashed) copy of the visitor's email address, so the platform can match the signup to an ad click. It sends it only when advertising cookies are on for that visitor, and never for a browser with Global Privacy Control turned on. The plain email address stays in WebNesting.

## Add the privacy paragraph to your site

When an ID is saved, a ready-made paragraph appears under that platform's fields. It names your business and says what that platform does with a visit. Its last lines say who your site asks before using these cookies: visitors in the EU, EEA and UK only, or every visitor, whichever your cookie banner is set to. Elsewhere the cookies are on unless the visitor turns them off. When you also save a server token, one more sentence appears that tells visitors about the hashed email address. Select **Copy**, then paste the text into your privacy page. Read it first and change anything that does not match how you run your business.

## Related

- [Count signups from any other ad platform](count-signups-any-ad-platform.md)
- [Site Settings](site-settings.md)
