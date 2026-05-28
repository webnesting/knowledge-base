# Connecting a Custom Domain

**Last verified:** 2026-05-16 12:35pm

A custom domain gives your website its own professional web address, like `www.yourcompany.com`, instead of the default WebNesting address. This guide walks you through the full setup process.

> **This guide is for your WEBSITE domain only** — the address visitors type to reach your site. Setting up your domain for **email** (so support tickets arrive at `support@yourcompany.com` or marketing campaigns send from your domain) is a separate flow with different DNS records. See the [Email Setup section in the Helpdesk guide](../dashboard/helpdesk.md#connecting-your-email) for the email side. You can use the same domain for both — they don't conflict with each other.

---

## What Is a Custom Domain?

When you create a site on WebNesting, it starts with an address like `yoursite.webnesting.site`. A custom domain replaces that with a web address you own, such as `www.yourcompany.com` or `mybusiness.com`.

Using your own domain makes your site look more professional, builds trust with visitors, and is easier for people to remember.

---

## Before You Start

To connect a custom domain, you will need:

- **A registered domain name.** You can purchase one from any domain registrar such as GoDaddy, Namecheap, Cloudflare, or Google Domains. If you do not have a domain yet, visit any of these providers and search for the name you want.
- **Access to your domain registrar's DNS settings.** This is the control panel where you manage your domain. You will need to log in to your registrar's website to make changes.

> **Tip:** If you are not sure who your domain registrar is, try searching for your domain at [who.is](https://who.is) -- it will show you where the domain is registered.

---

## Step 1: Find Your WebNesting Site Address

Before you update any settings, you need to know your current WebNesting site address. This is the address that your custom domain will point to.

1. Open your WebNesting Dashboard.
2. Click **Settings** in the left sidebar.
3. Look for your current site address. It will look something like `yoursite.webnesting.site`.
4. Write this address down or copy it -- you will need it in a later step.

---

## Step 2: Add Your Custom Domain in WebNesting

1. In your Dashboard, go to **Settings**.
2. Open the **Domain** section.
3. Enter your custom domain name (for example, `www.yourcompany.com`).
4. Click **Save**.

WebNesting will confirm your domain has been added and display the DNS records you need to set up with your domain registrar.

---

## Step 3: Update Your DNS Records

Now you need to tell your domain registrar to point your domain to WebNesting. You do this by adding a DNS record.

### What Is a DNS Record?

DNS stands for Domain Name System. Think of it as the internet's address book. When someone types your domain name into their browser, DNS looks up where that domain points and sends the visitor to the right place. By updating your DNS records, you are telling the internet to send visitors of your domain to your WebNesting site.

### What Is a CNAME Record?

A CNAME record is a type of DNS record that points one address to another. Instead of pointing to a number (like an IP address), it points to a name -- in this case, your WebNesting site address. Think of it like mail forwarding: visitors who go to your custom domain are forwarded to your WebNesting site.

### How to Add a CNAME Record

The exact steps depend on your domain registrar, but the process is similar everywhere:

1. Log in to your domain registrar's website (GoDaddy, Namecheap, Cloudflare, Google Domains, or whichever provider you use).
2. Find the **DNS settings**, **DNS management**, or **DNS records** section. It is usually under your domain's settings or an "Advanced" menu.
3. Add a new **CNAME** record with the following details:
   - **Name** (or Host): Enter `www` if you want to use `www.yourcompany.com`. Enter `@` or leave it blank for the root domain (`yourcompany.com`) -- though not all registrars support CNAME records on root domains.
   - **Value** (or Points To / Target): Enter your WebNesting site address (for example, `yoursite.webnesting.site`).
   - **TTL**: Leave this at the default value, or set it to **Auto**.
4. Save your changes.

> **Tip:** If your registrar does not allow a CNAME record on the root domain, check your WebNesting settings for an A record option. Some registrars also support "CNAME flattening" or "ALIAS records" as alternatives.

---

## Step 4: Wait for DNS Propagation

After you update your DNS records, it takes some time for the change to spread across the internet. This process is called DNS propagation.

- **Most changes complete within an hour.**
- In some cases, it can take up to **48 hours**.
- During this time, your domain may work intermittently -- this is normal.

There is nothing you need to do during this waiting period. Just be patient and check back later.

---

## Step 5: Verify and Enable SSL

Once your DNS records have propagated and your domain is pointing to WebNesting, an SSL certificate will be automatically provisioned for your site.

### What Is SSL?

SSL (Secure Sockets Layer) is the technology that keeps the connection between your visitors and your website secure. When SSL is active:

- Your site address starts with `https://` instead of `http://`.
- Visitors see a padlock icon in their browser's address bar.
- Information sent between your visitors and your site is encrypted and protected.

SSL is important for visitor trust, data security, and search engine rankings. WebNesting handles SSL setup automatically, so there is nothing you need to configure.

SSL provisioning usually completes within a few minutes after DNS is connected, but it can take up to an hour in some cases. If you see a security warning in your browser during this time, wait a few minutes and try again.

---

## WWW vs. Non-WWW

You can choose whether your site uses `www.yourcompany.com` or just `yourcompany.com`. Both work the same way, and one is not better than the other in terms of performance.

Most modern websites use the non-www version (for example, `yourcompany.com`) because it is shorter and cleaner. However, the choice is entirely up to you.

### How to Set Your Preference

1. In your Dashboard, go to **Settings**.
2. Open the **General** section.
3. Find the **WWW Preference** setting.
4. Choose either **Use WWW** or **Do not use WWW**.
5. Save your changes.

WebNesting will automatically redirect visitors to whichever version you choose, so no matter which version someone types in, they will always end up on the right one.

> **Tip:** Pick one version and stick with it. This helps search engines treat your site as a single website rather than two separate ones.

---

## Troubleshooting

If your custom domain is not working after setup, try these steps.

### Domain Not Connecting

- **Check your DNS records.** Log in to your domain registrar and confirm that the CNAME record is pointing to your WebNesting site address. Make sure there are no typos in either the host name or the target value.
- **Wait for propagation.** DNS changes can take up to 48 hours to take effect. If you just made the change, give it more time.
- **Clear your browser cache.** Sometimes your browser remembers the old address. Try opening your domain in a private or incognito window.

### Security Warning in Browser

- **SSL may still be provisioning.** This usually completes within a few minutes to an hour after DNS is connected. Wait and try again.
- **Check that your domain is pointing correctly.** SSL can only be provisioned once DNS records are properly configured.

### Wrong Site Appears

- **Verify your DNS records.** Make sure your CNAME record points to the correct WebNesting site address, not a different hosting provider.

### Domain Works Without WWW but Not With It (or Vice Versa)

- **Set up DNS records for both versions.** You may need a CNAME record for `www` and a separate record for the root domain.
- **Check your WWW preference** in Settings to make sure the redirect is configured.

### Still Having Trouble?

If your domain is still not working after 48 hours, contact WebNesting support. Include your domain name and a screenshot of your DNS settings so the support team can help you quickly.

---

## Related Guides

- **[Site Settings](../dashboard/site-settings.md)** -- Full overview of all site settings, including domain and SSL options
- **[Troubleshooting](troubleshooting.md)** -- Solutions for other common issues
