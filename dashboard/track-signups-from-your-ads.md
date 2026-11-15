# Track signups from your ads

**Last verified:** 2026-11-14 11:41pm

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

## Check that it works

Each main ID has a **Send test signup** button. Save your settings, then select it. A new tab opens and sends one test signup to that platform. The test does not change your own signup numbers.

The platform can take a few minutes to show the test. Look on its events or diagnostics page.

## What visitors see

Your tags start after a visitor allows marketing cookies in your cookie banner. A visitor who says no is never sent to an ad platform. **Signups by ad** still counts their signup, because that count stays inside WebNesting.

When you save your first ID, WebNesting turns your cookie banner on, because a site with no banner never asks and the tags would never start. A line at the top of the page tells you, with a link to the banner settings. If you turn the banner off later, it stays off.

The platform learns that a signup happened. It never gets what the visitor typed, such as a name or an email address.

## Add the privacy paragraph to your site

When an ID is saved, a ready-made paragraph appears under that platform's fields. It names your business and says what that platform does with a visit. Select **Copy**, then paste it into your privacy page. Read it first and change anything that does not match how you run your business.

## Related

- [Count signups from any other ad platform](count-signups-any-ad-platform.md)
- [Site Settings](site-settings.md)
