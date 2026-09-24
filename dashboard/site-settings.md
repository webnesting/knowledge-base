# Site Settings

**Last verified:** 2026-09-24 9:56am

Site Settings is where you control the behind-the-scenes details of your website -- things like your logo, search engine preferences, analytics, and social media links. Most of these are "set it and forget it" options that you configure once when you build your site.

---

## Where to Find Site Settings

1. Open your WebNesting dashboard.
2. In the site menu, open **Settings** and click **Site Settings**.
3. You will see several sections organized by category. Click on any section to expand it and make changes.

![The site settings page with categories for SEO, Google, Social Media, and more](../images/dashboard/site-settings.png)

---

## Site Timezone

Your site's timezone decides which days this site counts in -- the days its analytics, form reports and published dates use. To change it, open **Site Settings**, click **Site Configuration**, and scroll to the **Timezone** section.

- **Use workspace timezone** (the default for every new site) -- the site follows your workspace's timezone, and changes with it.
- **A specific timezone** -- pick one when this site serves customers somewhere else, for example a client's site in another country.

Click **Save Changes** to apply it. Team members who haven't set a timezone on their own profile also see this site's times in it.

---

## SEO Settings

SEO stands for Search Engine Optimization. These settings help search engines like Google understand your site and display it correctly in search results.

All of these live on the **SEO Defaults** page: go to **Site Settings** and click **SEO Defaults**.

### Title

This is the name that appears in browser tabs and in search engine results for pages that do not have their own custom title.

1. On the **SEO Defaults** page, find the **Title** field.
2. Enter a clear, descriptive title for your website. For example: "Smith & Co. Accounting -- Tax Services in Portland."
3. Save your changes.

You can insert your site's name or the current page's title automatically by typing `{{ site.name }}` or `{{ page.title }}`. For example, `{{ site.name }} | {{ page.title }}` shows as "Smith & Co. Accounting | About Us" on your About Us page.

> **Tip:** Keep your title under 60 characters so it does not get cut off in search results.

### Description

This is the short summary that appears below your site's title in search engine results. It helps visitors decide whether to click through to your site.

1. On the **SEO Defaults** page, find the **Description** field.
2. Write a brief, compelling description of your website (one to two sentences). The same `{{ site.name }}` and `{{ page.title }}` shortcuts work here.
3. Save your changes.

> **Tip:** Write a description between 120 and 160 characters. Include your most important keywords naturally -- do not stuff keywords in unnaturally.

### Previewing How You Appear in Search

Under the Title, Description and Image fields, **How it looks in search results** shows your site the way it appears in a search engine's results -- the web address, the title as a blue link, and the description underneath. It updates as you type, with `{{ site.name }}` and `{{ page.title }}` already filled in with their real values.

- Use **Preview for** to see a different page. The title changes with each page's name wherever you used `{{ page.title }}`.
- If a page has its own SEO title or description, the preview shows that instead, and says so -- the defaults only apply to pages without their own.
- Titles longer than 60 characters and descriptions longer than 155 are cut off with "…", as search results usually do.

Search engines sometimes shorten or rewrite what they show, so treat the preview as a close guide rather than an exact promise.

### Image (social sharing image)

When someone shares a link to your site on social media (Facebook, LinkedIn, X, etc.), this image appears alongside the link for any page that has no image of its own. It is sometimes called an OG image (Open Graph image).

1. On the **SEO Defaults** page, find the **Image** setting.
2. Click to choose an image from your File Manager, or upload a new one.
3. Save your changes.

> **Tip:** Use an image that is at least 1200 x 630 pixels for the best results across all platforms.

### Hiding Your Site from Search Engines

If your site is not ready for the public yet (for example, if you are still building it), you can tell search engines not to list any of its pages.

1. On the **SEO Defaults** page, find **Hide site from search engines**.
2. Click the **Hide my whole site** card. Because this affects every page, WebNesting asks you to confirm before it takes effect.
3. Save your changes.

While it is on, the setting shows a warning reminding you that the site is hidden, and your site tells search engines not to index it in two ways: its `robots.txt` file blocks everything, and every page carries a "noindex" instruction. Visitors can still open the site by typing its address.

**Important:** Remember to switch this back to **List my site** when your site is ready to launch. If you leave it on, people will not be able to find your site through Google or other search engines.

> **Tip:** This is a request that search engines honor, not a lock. Most major search engines respect it, but it is not a guarantee, and pages already listed can take a while to drop out of results.

### Sitemap Address Preferences

A sitemap is a file that lists all the pages on your site (at `yoursite.com/sitemap.xml`). Search engines use it to find and index your content more efficiently. WebNesting generates it for you automatically and keeps it up to date whenever you add, change, or remove pages.

Two on/off switches control how the addresses inside it are written:

- **Use secure (https) links in your sitemap** -- leave this on if your site uses a secure `https://` address (almost all do).
- **Start sitemap links with "www."** -- turn this on only if your site's address includes `www.`

Pick the form that matches how visitors actually reach your site so search engines see one consistent address for every page.

---

## Google Settings

**Google Settings** (under **Connections** on the Settings page) adds Google's tracking code to your site and holds the reCAPTCHA keys that protect your forms from spam. It has two sections: **Visitor tracking** and **Spam protection**.

### Google Analytics and Tag Manager (Visitor tracking)

- **Google Analytics ID** -- your GA4 measurement ID, from Google Analytics → **Admin** → **Data streams**. Type the part after `G-`; the box already shows the `G-`. WebNesting adds Google's tracking code to every page.
- **Google Tag Manager container** -- your container ID, shown next to the container's name in Tag Manager. Type the part after `GTM-`. Click **Check** to ask Google whether that container exists and is published -- an unpublished container does nothing on your site.

If you set a Tag Manager container, the Google Analytics ID is not used: add Google Analytics inside Tag Manager instead, so your visitors aren't counted twice.

To see Google Analytics numbers inside WebNesting, connect Google Analytics under **Workspace Settings → Integrations** (see [Integrations](integrations.md)). That is separate from the tracking code on this page.

> **Tip:** It can take 24 to 48 hours for data to start appearing in Google Analytics after you first add your ID.

### reCAPTCHA keys (Spam protection)

reCAPTCHA stops bots from submitting your forms. A form uses these keys when its spam protection is set to reCAPTCHA.

1. Go to [google.com/recaptcha/admin](https://www.google.com/recaptcha/admin) and register your site's domain.
2. Copy the **Site key** into **reCAPTCHA site key**, and the **Secret key** into **reCAPTCHA secret key**.
3. Save your changes.

The secret key is stored encrypted and never shown again after you save -- the box says **Saved** instead. Leave it empty to keep the saved key, or type a new one to replace it. If the box says the saved key can't be read, enter it again.

To test your keys, submit one of your forms that uses reCAPTCHA. Google only accepts reCAPTCHA on the domains you registered, so it can't be tested from the settings page.

### WebNesting's Built-In Analytics

WebNesting also has its own privacy-friendly visitor stats -- no Google account needed. Turn on **Enable first-party analytics** in **Site Configuration**, under **Analytics**. You can use it alongside Google Analytics; they work independently.

---

## Social Media Profiles

Add your social media links so they can appear in your site's header, footer, or anywhere you use social media components.

### Adding Your Social Media Links

1. Go to **Site Settings** and open the **Connections** section, then click **Social Settings**.
2. You will see fields for each supported platform.
3. For each platform, enter your handle (like `@yourcompany`) or paste the link to your profile (like `https://www.instagram.com/yourcompany`). Either works.
4. Save your changes.

### Default Platforms

WebNesting includes fields for the following social media platforms by default:

- Facebook
- X (formerly Twitter)
- YouTube
- Instagram
- Pinterest

You can also add more platforms yourself — open **Add another network** at the bottom of the Social Settings page, and enter the network name and your handle or profile link, then click **Add** (or just **Save Changes** — it saves the new network along with your other changes). Each network name can only be used once. You only need to fill in the platforms you use. Leave the rest blank.

> **Tip:** A link works with or without the `https://` part, and a handle works with or without the `@`. Your site turns each one into a link to your profile.

---

## Site Images

These are the key images that represent your brand across your website. They live on the **Site Images** page, under **Content** in Site Settings. Each image on the page says where it appears, and the pictures are shown two to a row.

### Setting Your Logo

Your logo appears in your site's header and anywhere else your theme displays it.

1. Go to **Site Settings**, open **Content**, and click **Site Images**.
2. Find **Logo**.
3. Click to choose an image from your File Manager, or upload a new one.
4. Save your changes.

> **Tip:** Upload your logo as a PNG file with a transparent background. This ensures it looks good on any background color. SVG format also works well for logos.

### Setting Your Favicon

A favicon is the tiny icon that appears in browser tabs next to your page title. It also shows up in bookmark lists and on mobile home screens.

1. On the **Site Images** page, find **Favicon**.
2. Click to choose an image from your File Manager, or upload a new one.
3. Save your changes.

> **Tip:** Favicons should be square and simple. A good size is 512 x 512 pixels. Complex images will be hard to see at such a small size, so use a simple icon or the first letter of your brand name.

### Setting the Fallback Image

The **Fallback image** is used wherever something has no picture of its own -- an empty slideshow or gallery slot, for example.

1. On the **Site Images** page, find **Fallback image**.
2. Click to choose an image from your File Manager, or upload a new one.
3. Save your changes.

The image that appears when someone shares a link to your site on social media is a separate setting -- see **Image** under [SEO Settings](#seo-settings) above.

You can also add your own named images here with **Add** at the bottom of the page; your theme and content can then use them by name.

---

## Site Configuration

These settings control foundational aspects of how your website works -- its name, description, business name, theme, visibility, and web address. They live on the **Site Configuration** page, under **Your site** in Site Settings.

### Launching Your Site (Visibility)

A new website starts in **Coming soon** mode: visitors see a "Coming Soon" page instead of your site, while you keep building. When you are ready for people to see it:

1. Go to **Site Settings**, open **Your site**, and click **Site Configuration**.
2. Under **Visibility**, click the **Live** card.
3. Save your changes.

To take the site back down later, choose **Coming soon** and save. Either way, you always see your real site while you are signed in -- open it in a private browser window to see what visitors see.

### Business Name

**Business name** appears in the copyright line at the bottom of every page ("Copyright © 2026 Your Business"). Leave it blank to use your Site Name instead.

### Choosing a Theme

**Theme** is a picker of the designs installed on WebNesting. Pick one and save; your site's colors and fonts are then customized on the **Themes** page (see [Themes and Customization](themes-and-customization.md)).

### Secure (HTTPS) Addresses

A secure address starts with `https://` instead of `http://`, and visitors see a lock icon in their browser.

1. Go to **Site Settings**, open **Your site**, and click **Site Configuration**.
2. Find **Always use a secure (https://) address?**
3. Click the **Always secure** card once your domain's certificate is active -- anyone who types `http://` is sent to `https://`. **Either works** leaves both forms reachable.
4. Save your changes.

> **Tip:** Once your certificate is active, always redirect to https. It protects your visitors, builds trust, and is favored by search engines.

### WWW Preferences

You can choose whether your site address starts with "www." or not.

- **With "www.":** `www.yoursite.com`
- **Without "www.":** `yoursite.com`
- **Either works:** both versions work as typed

Most modern sites use the non-www version. Choose whichever you prefer and stick with it, so search engines do not see them as two different sites.

1. On the **Site Configuration** page, find **Should your address start with "www."?**
2. Click one of the three cards.
3. Save your changes.

If you choose **With "www."** or **Without "www."**, WebNesting automatically redirects visitors who type the other form, so no one lands on the wrong one.

### All Settings (power-user view)

**All Settings**, under **Advanced**, lists every raw setting on your site in one place. Values there are saved exactly as typed, with no checks -- so if a setting has its own page (SEO Defaults, Site Images, Social, Google), edit it there instead. Use All Settings for the custom values you have added yourself -- the **Add your own setting** form at the bottom of the page is where you add them.

> **Tip:** After making changes to any settings, visit your live site in a new browser tab to confirm everything looks the way you expect.

---

## Custom Domain

By default, your website is available on a WebNesting subdomain (like `yoursite.webnesting.site`). If you want to use your own domain name (like `www.yourcompany.com`), you can connect it in your site settings.

### What Is a Custom Domain?

A custom domain is a web address you own, like `www.yourcompany.com`. Using your own domain makes your site look more professional and is easier for visitors to remember.

### How to Add a Custom Domain

1. Go to **Settings → Site Settings** in your site menu.
2. Open the **Domain** section.
3. Enter your custom domain name (for example, `www.yourcompany.com`).
4. Save your changes.

WebNesting will display the DNS records you need to set up with your domain provider.

### Setting Up DNS Records

After adding your domain in WebNesting, you need to update the DNS settings with your domain registrar (the company where you bought your domain, like GoDaddy, Namecheap, or Google Domains).

1. Log in to your domain registrar's website.
2. Find the DNS settings or DNS management area.
3. Add the records that WebNesting provided:
   - For a root domain (like `yourcompany.com`), add an **A record** pointing to the IP address shown in your WebNesting settings.
   - For a subdomain (like `www.yourcompany.com`), add a **CNAME record** pointing to the address shown in your WebNesting settings.
4. Save your DNS changes.

> **Tip:** DNS changes can take anywhere from a few minutes to 48 hours to take effect. This is normal and depends on your domain registrar.

### SSL Certificate (HTTPS)

Once your DNS records are set up and pointing to WebNesting, an SSL certificate will be automatically provisioned for your domain. This ensures your site uses `https://` and visitors see the secure lock icon in their browser.

SSL provisioning usually completes within a few minutes after DNS is connected, but it can take up to an hour in some cases.

### Troubleshooting Domain Issues

If your custom domain is not working after setup:

- **"Site not found" error** -- DNS records may not have propagated yet. Wait up to 48 hours and try again.
- **Security warning in browser** -- The SSL certificate may still be provisioning. Wait a few minutes and refresh.
- **Wrong site appears** -- Double-check that your DNS records point to the correct WebNesting addresses. Your DNS records should include a CNAME record pointing to your WebNesting site address (shown in Site Settings under Custom Domain).
- **Domain works without WWW but not with it (or vice versa)** -- Make sure you have set up DNS records for both versions, or configure your WWW preference in the General Settings section above.

If you are still having trouble after 48 hours, contact support with your domain name and a screenshot of your DNS settings.
