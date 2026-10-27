# Connect a Domain From Another Registrar

**Last verified:** 2026-10-27 10:11am

You bought your domain from a registrar such as GoDaddy, Namecheap, Cloudflare or Squarespace Domains, and you want your WebNesting site to open at that address. This guide shows what to do at the registrar. The domain stays registered where you bought it. You only change its DNS records.

For what the app offers today, read [Connecting a Custom Domain](custom-domains.md) first.

---

## Before you start

- Your site is created, and you can open it with **Manage Site**.
- You can sign in to your registrar's website. You need the account that owns the domain.
- You have the records Support gave you for your site. Never guess a record value. A wrong value can take your domain offline.
- You know whether your domain already runs a website or email. If it does, change nothing except the records you were asked to add.

> **Tip:** Not sure who your registrar is? Search for your domain at [who.is](https://who.is). The result names the registrar.

---

## What a DNS record is

DNS is the internet's address book. A DNS record is one line in that book. It says where a name, such as `www.yourcompany.com`, should send visitors. Your registrar keeps the address book for your domain. You add a line that sends visitors to your WebNesting site.

A **CNAME** record points one name at another name. A **TXT** record holds a short piece of text, for example to prove that you own a domain. Support tells you which records your site needs.

---

## Steps

1. Email Support at support@webnesting.com with your site name and your domain name. Support replies with the records to add.
2. Sign in to your registrar.
3. Open your domain's DNS settings. Registrars name this page **DNS**, **DNS management**, **DNS records** or **Advanced DNS**. It is usually inside the domain's settings.
4. Select the button that adds a record. Its name is often **Add record** or **Add new record**.
5. Choose the record **Type** Support gave you, for example **CNAME**.
6. Enter the **Name** (some registrars say **Host**) exactly as Support wrote it. Enter `www` for `www.yourcompany.com`. Enter `@` for the root address, `yourcompany.com`.
7. Enter the **Value** (some registrars say **Points to** or **Target**) exactly as Support wrote it.
8. Leave **TTL** on its default, or choose **Auto**.
9. Save the record.
10. Add any other record Support listed in the same way.

If your registrar does not allow a CNAME record on the root address, tell Support. Some registrars offer a different record type for the root address, and Support can say which to use.

> **Important:** Do not change your **nameservers**. Do not delete **MX** records. MX records send your email. Changing them can stop your email.

---

## Check it worked

1. Wait. Most changes finish within an hour. Some take up to 48 hours.
2. Open your domain in a private or incognito window.
3. You see your WebNesting site, and the address starts with `https://` with a padlock.

Your secure address turns on by itself once the domain points to your site. If your browser shows a security warning, wait a few minutes and try again.

---

## If something goes wrong

- **The domain still shows the old site or an error.** Wait longer. Then check the record at your registrar for typos in the name and the value.
- **Your browser shows a security warning.** The certificate may still be on its way. Wait up to an hour and try again.
- **A different site appears.** The record points somewhere else. Compare the value with what Support gave you.
- **The address works with "www." but not without it, or the other way round.** Add a record for both versions. Then open your site's **Settings** > **Site Settings** > **Site Configuration** and check **Should your address start with "www."?**.
- **Your email stopped.** An email record changed. Put the old MX records back at your registrar, then email Support.

Still stuck after 48 hours? Email Support at support@webnesting.com. Include your domain name and a screenshot of your DNS settings.

---

## Where to go next

- [Connecting a Custom Domain](custom-domains.md)
- [Site Settings](../dashboard/site-settings.md)
- [Troubleshooting](troubleshooting.md)
