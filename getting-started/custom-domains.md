# Connecting a Custom Domain

**Last verified:** 2026-10-27 10:11am

A custom domain gives your website its own professional web address, like `www.yourcompany.com`, instead of the free WebNesting address. This guide explains what you can do today, and where to go for the steps at your domain registrar.

> **This guide is for your WEBSITE domain only** — the address visitors type to reach your site. Setting up your domain for **email** (so support tickets arrive at `support@yourcompany.com` or marketing campaigns send from your domain) is a separate flow with different DNS records. See the [Email Setup section in the Helpdesk guide](../dashboard/helpdesk.md#connecting-your-email) for the email side. You can use the same domain for both — they don't conflict with each other.

---

## What Is a Custom Domain?

When you create a site on WebNesting, it starts with a free address like `yoursite.webnesting.site`. A custom domain replaces that with a web address you own, such as `www.yourcompany.com` or `mybusiness.com`.

Using your own domain makes your site look more professional, builds trust with visitors, and is easier for people to remember.

---

## What you can do today

- **Use the free address.** Every site has one from the moment you create it. Nothing else is needed to publish.
- **Enter your domain when you create a site.** The **Create Site** form has a **Custom Domain (optional)** box. Leave it blank to use the free address.
- **Choose how your address is written.** Open your site, then **Settings** > **Site Settings** > **Site Configuration**. Under **Web address**, **Always use a secure (https://) address?** decides whether anyone who types `http://` is sent to the secure address. **Should your address start with "www."?** decides whether visitors who type it the other way are sent to your choice. Both settings start on **Either works**.

A screen in the app where you connect, check and change a domain later is not available yet. Until it is, email Support at support@webnesting.com with your site name and your domain name. Support tells you what to do next.

> **Tip:** Do not change anything at your registrar before Support answers. A wrong record can take your email or an existing website offline.

---

## Before You Start

To connect a custom domain, you will need:

- **A registered domain name.** You can buy one from any domain registrar, such as GoDaddy, Namecheap, Cloudflare or Squarespace Domains.
- **Access to your domain registrar's DNS settings.** This is the control panel where you manage your domain. You will need to sign in to your registrar's website to make changes.

> **Tip:** If you are not sure who your domain registrar is, search for your domain at [who.is](https://who.is) -- it shows where the domain is registered.

The steps at the registrar are in [Connect a domain from another registrar](connect-a-domain-from-another-registrar.md).

---

## What happens after the records are added

- **Wait for DNS to update.** Most changes finish within an hour. Some take up to 48 hours. Your domain may work on and off while it spreads. That is normal.
- **Your secure address turns on by itself.** WebNesting issues a security certificate once your domain points to your site, so the address starts with `https://` and visitors see a padlock. There is nothing to set up. Certificates usually finish in a few minutes after your domain points to WebNesting, and can take up to an hour. If your browser shows a security warning in that time, wait a few minutes and try again.

---

## If your domain is not working

- **Check your DNS records.** Sign in at your registrar and confirm the record matches what Support gave you, with no typos in the host name or the value.
- **Wait for DNS to update.** Changes can take up to 48 hours.
- **Try a private window.** Your browser may remember the old address. Open your domain in a private or incognito window.
- **Security warning in the browser.** The certificate may still be on its way. Wait and try again. It can only be issued once your domain points to WebNesting.
- **Wrong site appears.** The record may point to another host. Check the value against what Support gave you.
- **Works without "www." but not with it, or the other way round.** Add a record for both versions, then check **Should your address start with "www."?** in **Site Configuration**.

Still not working after 48 hours? Email Support at support@webnesting.com. Include your domain name and a screenshot of your DNS settings so Support can help you quickly.

---

## Related Guides

- **[Connect a domain from another registrar](connect-a-domain-from-another-registrar.md)** -- Where to find DNS settings, what to add and what to leave alone
- **[Site Settings](../dashboard/site-settings.md)** -- Full overview of all site settings
- **[Troubleshooting](troubleshooting.md)** -- Solutions for other common issues
