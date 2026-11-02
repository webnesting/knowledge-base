# Billing and Usage

**Last verified:** 2026-11-01 6:35pm

WebNesting bills with plans and prepaid credits. You pick a plan for each part of WebNesting you use and pay for it on the 1st of the month. If you use more than a plan includes, prepaid credits pay for the extra. This page explains the details: what is included, what happens at a limit, and how to see and pay your bills. For the plan prices, how credits work and how a failed payment is handled, see [Usage and Billing](../account/usage-and-billing.md).

---

## Understanding Your Bill

Your bill has two kinds of charges:

1. **Plans and add-ons.** A flat monthly price for each plan you have (Websites for each site, Marketing, Helpdesk, Tasks, API) and each site add-on. They are all charged together on the 1st.
2. **Credits.** Money you add to your workspace to pay for use past your plans. You buy credits when you choose, or with auto top-up. Each purchase has its own invoice.

You pay in advance. Nothing is billed after the month, unless your workspace has an Enterprise contract.

---

## What Is Included

Each plan includes an amount that starts over on the 1st of every month. It is your **included amount**. The **Usage** page shows it as **Included this month**: what you used, what is left, and **Using credits** when you are past it.

Every site starts on the **Free** plan, which costs $0 and includes 5 pages, 500 MB of storage and 500 MB of website bandwidth each month. Contacts, team members and API tokens are unlimited on every plan. The full table of plans and prices: [Usage and Billing](../account/usage-and-billing.md#plans).

---

## What Counts as Usage

### Pages

A Free site can have 5 pages. A site on a paid Websites plan has unlimited pages.

On a Free site, these do not count toward the 5: the built-in system pages (like the 404 page), translations of a page, the sign-in pages, and the pages of blog posts, events and store products. If you make a 6th page, duplicate a page, or bring a deleted page back past 5, WebNesting says "Free sites have 5 pages. Upgrade to Starter for unlimited pages." and makes nothing. Your existing pages stay.

### Storage

All your storage is one pool for the whole workspace. It is the storage of each Websites plan, plus 2 GB for each paid Marketing, Helpdesk, Tasks or API plan. It covers your own uploads (images, videos, documents), helpdesk ticket attachments, and files visitors upload through your forms. A workspace with no paid plan has the Free site's 500 MB.

When the pool is full, credits pay for more storage. When the credits are gone too, uploads, imports and site publishing that add files are refused, and the message tells you what is used. Helpdesk attachments and form uploads are still stored and paid with credits.

Files belonging to a product you have turned off still count while they are kept, and stop counting once they are deleted.

> **Tip:** You can see and manage every stored file from the File Manager (click **Files** in the top bar) -- helpdesk attachments live in the managed **Helpdesk** folder and visitor uploads in **Form Uploads**. Deleting files you no longer need frees room in the pool.

### Website bandwidth

Website bandwidth is the data one site sends to its visitors: its pages, pictures, videos and files. **Each site has its own bandwidth,** set by its Websites plan: 500 MB on Free, 5 GB on Starter, 15 GB on Growth and 40 GB on Pro each month. The line is named **Website Bandwidth** on the **Usage** page.

- **What is not counted.** Visits to your WebNesting dashboard and the website builder, and API calls (those are API data). A request that fails, such as a page not found, is not counted. If a visitor stops a video partway, only about the part that was sent is counted.
- **It updates once a day.** The **Usage** page row says "Updated daily" and shows the date the count runs through. The newest hours can take a day to appear.
- **Past the included bandwidth,** each extra GB is paid from your credits.

**Emails about a site's bandwidth.** The workspace owner gets an email for each of these, once for each site and month:

| Email | When |
|---|---|
| **80% used** | The site has used 80% of its included bandwidth. |
| **All used** | The site has used all of its included bandwidth. The email tells you the credit price of an extra GB and your credit balance. |
| **The site is unavailable** | The site is held (see below). |
| **Unavailable for 30 days** | The site has been held for 30 days. |

**When a site is held.** When the bandwidth and the credits are used up, the site is held. A Free site is held right away. A paid site keeps working for a further 15% of its plan's bandwidth at no charge, and is held after that. A held site's pages show a page that says the site is **temporarily unavailable**. Your site, its pages and its files are safe, and you can keep editing in your dashboard. The hold ends when you buy credits, move the site to a bigger plan, or the month starts over and the plan's bandwidth starts again. Search engines can lower a site that stays unavailable for a long time, which is why we email you after 30 days.

While a site is held, its pictures, videos and other files stop loading too: on the site, and anywhere else they are linked. Your other sites keep working. When the hold ends, the site and its files come back within a few minutes. See [Website bandwidth for each site](../account/usage-and-billing.md#website-bandwidth-for-each-site).

**See where it went.** On the **Usage** page, click the **Website Bandwidth** row. It shows the GB each website sent (bytes that belong to no site show as **Workspace media library**), and **Files that sent the most**: your top 5 files, each with a small picture, its type and where it is.

**Ways to lower it:**

- **Put long videos on YouTube or Vimeo** and paste the link into the **Video** block. An embedded video costs nothing in website bandwidth.
- Look at **Files that sent the most**. If a video is at the top, use a shorter or smaller version of it.
- A visitor loads a video only when they press play. A video no one watches sends almost nothing.

When you upload a video over 50 MB in **Files**, a note reminds you that videos use website bandwidth.

### Emails, tickets, active tasks and API

Each of these has an included amount in its plan, and credits pay for more. What happens when both are used up is in [Usage and Billing](../account/usage-and-billing.md#what-happens-at-a-limit). In short:

- **Marketing emails.** A new campaign does not start. Automation emails wait.
- **Helpdesk tickets.** Tickets keep arriving. Up to 25% above your limit works as normal. Past that, new tickets are marked as over the limit and replies to them are locked.
- **Active tasks.** You cannot create, reopen or restore a task.
- **API requests.** They are refused with a "usage limit" message.

Buying credits, moving to a bigger plan, or the 1st of the month lifts each limit at once.

### People who sign up on your site

**No extra charge.** When someone creates an account on your site, they become one of your contacts. Contacts are unlimited on every plan, and there is no per-person fee for letting people sign in. Your team members are not charged either.

---

## Module Pricing

Site modules are add-ons with a flat monthly price for each site. Any site can turn an add-on on, a site on the Free plan too. A Free site stays on Free and pays only for its add-ons.

| Add-on | Price for each site | What it does |
|--------|---------------------|--------------|
| Blog (the Articles module) | $3 a month | Adds a blog/news section to your site |
| Events | $3 a month | Adds event listings with dates and details |
| Forms | $3 a month | Build custom forms for contact, surveys, and registrations |
| Store | $10 a month | Adds an online store with products and orders |
| Widget builder | $5 a month | Lets you create custom interactive elements |
| **All add-ons together** | **$15 a month** | Every add-on above |

Marketing, Helpdesk, Tasks and API are workspace plans, not site add-ons. See [Workspace Products](workspace-products.md) and the [plan table](../account/usage-and-billing.md#plans).

> **Tip:** An add-on costs the same every month, however much you use it. Blog costs $3 a month whether you have 2 articles or 200. A site on a paid plan has unlimited pages, so articles, events and products never cost extra.

---

## How Billing Works

### Monthly Billing Cycle

Your billing month is the calendar month. Every plan and add-on renews in one charge on the 1st, to your saved card. Bills are paid through your WebNesting account using a credit or debit card.

### Pro-Rated Charges

You are never charged for time you did not use. A new plan or add-on is charged for the time left in the month, down to the second, and you get the matching share of what it includes.

**Example:** If you turn on the Blog add-on halfway through a 30-day month, you pay about $1.50 instead of the full $3.

- **A bigger plan** starts right away. You pay the difference for the rest of the month.
- **A smaller plan** starts on the next 1st. You keep the bigger plan until then.
- **A part-month charge under $0.50** is not sent to your card. It is added to your next renewal.

If you turn a site add-on off, its content is **permanently deleted after 30 days** unless you turn it back on before then. A workspace product gives you a choice when you turn it off: see [Workspace Products](workspace-products.md#disabling-a-product).

### Payment Processing

The card fee is part of the price. No invoice has a separate processing fee line.

### Late Payments

If your card does not pay on the 1st, everything keeps working for 7 days. We try the card again on days 1, 3, 5 and 7 and email you each time. You can pay the invoice yourself at any time. After day 7, your paid plans move to Free and nothing is deleted. Paying the invoice brings everything back at once. An unpaid renewal invoice is cancelled on the next 1st. The details, and what a lapsed site shows, are in [Usage and Billing](../account/usage-and-billing.md#if-a-renewal-payment-fails).

### Paused sites and videos

WebNesting can pause part of your workspace for billing. The **Billing** page always says what is paused and how to turn it back on.

- **Your sites, for a review.** WebNesting reviews some new workspaces that have no payment method yet. During a review, WebNesting can pause all your sites. Visitors then see a "Temporarily unavailable" page in place of your site, and your videos are paused too. The workspace owner gets an email that says so. To turn your sites back on, add a payment method with the **Add Payment Method** button on the Billing page, or pay any overdue invoice. Your sites come back within a few minutes.
- **Your videos only, for a review.** WebNesting can also pause only your videos during a review, and keep your sites on. The Billing page then says "Video playback on your sites is paused while we review this workspace." Add a payment method with **Add Payment Method**, and the videos come back within a few minutes.

A pause deletes nothing. During a review you can still sign in and work in your dashboard. Each paused video shows a pause badge in **Files**. A site held at its bandwidth limit is a pause too: every file of that site shows a pause badge, see [Website bandwidth](#website-bandwidth).

---

## Viewing Your Billing

To see your current and past bills:

1. Open the workspace you want to look at.
2. Select **Settings** at the bottom of the left icon rail, then **Plans & Billing** under **Billing**. (You can also reach it from the **⋮** menu in the top bar → **Billing**.)
3. The **Billing** page shows **Your plans**, with the price and the date each one renews, and the **Next renewal**: what will be charged on the 1st, with each discount, special price, complimentary period or product credit as its own line. It also shows your **Credits** and balance. Past invoices are on **Invoice History**: select one to open it, or **Download PDF** for a copy. Anything outstanding appears in a banner at the top -- **Pay Now** pays a single invoice on the spot.
4. There is one invoice for each plan purchase or renewal and one for each credit purchase.

To see how much you have used, open the **Usage** page: **Included this month** shows each part of your plans, what you used and what is left, and your credit balance, with **Buy credits**.

### What WebNesting gives you

Sometimes WebNesting gives your workspace something extra. It is never mixed silently into your plan prices: your plans cost the same, and what you are given is a separate thing you can see. Prepaid credits you buy yourself are in [Usage and Billing](../account/usage-and-billing.md#credits).

**Bonus units.** Extra units on top of your plan's included amount, for example 5,000 bonus emails a month. They are added to what your plan includes, so you reach a limit later. They are used after the plan's own amount and before credits.

- **Every month.** A monthly bonus is given again each month. Unused units either end with the month or carry over until the bonus ends; the email you get says which.
- **All at once.** A one-time bonus is given in full the day it starts. It is used month by month until it runs out or ends.
- **Things you have a number of.** A bonus on pages, storage, active tasks or API tokens is a fixed extra amount every month. It always ends with the month.
- **Waiting.** If a bonus is for a product you do not have a plan for, nothing is used.

### Your price

WebNesting can set a lower credit price for your workspace, for one meter or one site. Where a message names the price of one more unit, such as the message when a limit is reached, it shows your price. A price can have an end date. After it, the list price applies again.

WebNesting can also set your own price for one plan, such as Marketing Growth, or for an add-on, on every site or on one site. Your plan invoice then lists the plan at its normal price and a separate **Your price** line under it, for example "Your price: Marketing Growth plan" with "$19.00 / month in place of $29.00 / month". You pay the difference less. If your price starts or ends during a month, that month's line takes off only its part of the month. On the **Billing** page, **Your plans** shows your price beside the list price, which is struck out. The **Next renewal** shows your price too, and so does the amount charged when you change a plan. When you choose a plan, the plan picker shows the price the 1st renews at, beside the list price.

**A later end date.** If WebNesting moves the end of your price to a later date, and you already paid a plan invoice for those days, the difference is added to your credit balance as prepaid credits. If that plan invoice is not paid yet, its total goes down instead. If the end then moves earlier again, only the credits for the days it no longer covers come off.

### Complimentary

WebNesting can make your whole account complimentary for a period. During a complimentary month, your limits are not applied and nothing is drawn from your credits. Your plans still renew on the 1st: the invoice lists each plan and a **Complimentary account** line that takes it to $0, and nothing is charged to your card.

WebNesting can also make one product complimentary, such as Marketing, from a date. Your plan invoice then shows a **Complimentary Marketing** line for the days it covers, and you pay only for the rest.

### Discounts

WebNesting can give your workspace a discount, as a percent or a fixed amount, for a set time. It can be for one product, for one product's monthly plan price only, for one site, or for the whole bill. On a plan invoice, the discount is its own line under the plans it is for. A discount comes off before a promotion and before product credit.

With two or more paid plans, you also get the multi-product discount: your highest-priced plan is full price, and every other plan is 20% off. It comes off after your price and before any other discount. See [The multi-product discount](../account/usage-and-billing.md#the-multi-product-discount).

### Credits from WebNesting

- **Product credit** is a dollar amount for one product, such as $20 for Marketing. It pays that product's plan on your next invoices until it is used up or ends. It pays only for that product.
- **Account credit** from WebNesting is added to your credit balance as prepaid credits. It works like credits you buy: it pays for use past your plans and it never expires. You see it on the **Billing** page with your balance, and the workspace owner gets an email that says how many credits were added.

**Given for days you already paid for.** WebNesting can give something from a date in the past, such as a complimentary period from the 16th. If you already paid a plan invoice for those days, the part you paid for them is added to your credit balance as prepaid credits. Nothing goes back to your card. If that plan invoice is not paid yet, its total goes down instead. If WebNesting then ends it early, the credits for the days it no longer covers come off your balance, as a line that starts "Ended early". Credits you already spent are not taken back.

### Where you see it

The **Usage** page has a **From WebNesting** section under **Usage this period**. It lists what WebNesting gave your workspace for the month your date range ends in. For bonus units it shows how many you earned, used and have left, and when they end. WebNesting emails the workspace owner when something is given, and 7 days before it ends.

The Usage page shows counts, never money.

### Refund policy

**What is refunded.** WebNesting refunds a charge it billed in error in full. An error is a bug, a duplicate charge or a wrong figure.

**What is not refunded.** A plan that was billed correctly is not refundable. Credits you bought are not refundable either.

**How long you have.** Ask within 30 days of the invoice date.

**How to ask.** Open a Billing ticket with Support. WebNesting approves each refund, and Support tells you the result. Step by step: [Asking for a refund](../account/asking-for-a-refund.md).

### How a refund reaches you

An approved refund goes back to the card that paid the invoice, or WebNesting can add it to your credit balance as prepaid credits. Your bank can take a few days to show a card refund. The earlier invoice does not change: its summary shows the amount under **Refunded**, and a refund can never be more than the invoice came to.

- **A plan invoice refunded in full** ends those plans on the next 1st. You keep them until then.
- **A credit purchase refunded** takes back the credits you have not spent first.

Your activity log records each refund.

### Promotion codes

A promotion code is a code from WebNesting that gives your workspace an offer, such as bonus units.

To use a code on a workspace you already have:

1. Open the workspace, then **Settings** → **Plans & Billing**.
2. On the **Billing** page, find **Promotion code** and click **Have a code?**
3. Type the code and click **Check code**. You see what the code gives you, for example "5,000 bonus Marketing emails a month for 3 months". Nothing is applied yet.
4. Click **Apply to this workspace**. To try another code, click **Use a different code**.

After you apply it, bonus units show on your **Usage** page. If the offer is a discount, it shows as its own line on your next plan invoice, after any discount from WebNesting. If the offer is account credit, it is added to your credit balance at once. When two offers apply to the same plan, you get the better one, unless the offer says it adds to others.

You can also enter a code when you sign up or when you create a workspace. See [Creating Your Account](../account/creating-your-account.md).

If a code is refused, the page says why:

- **"That code is not valid. Check the spelling and try again."** The code does not exist, or it is for a different place. A sign-up code works only on the sign-up page.
- **"… ended on …"** The offer or the code is over.
- **"… is already applied to this workspace. A code works once for each workspace."** You already used it here.
- **"This code has been fully used."** The offer had a limited number of uses and they are gone.
- **"This code isn't available for this workspace."** The offer is for other workspaces, for example new ones only.
- **"Too many tries. You can try again in … minutes."** After five wrong codes in 10 minutes, code entry is locked for a short time. Wait the number of minutes the message names, then try again.

You need permission to manage billing in the workspace to see the **Promotion code** section.

---

## Tips for Managing Costs

### Use What Your Plans Include

Your included amounts start over on the 1st, and unused included amounts do not carry over. Credits do. Check **Included this month** on the **Usage** page now and then to see whether a smaller or bigger plan would fit.

### Only Turn On Add-ons You Need

Each add-on adds to your monthly bill. If you are not using one, turn it off.

> **Important:** Turning off a module permanently deletes its content -- blog posts, events, products -- after 30 days, or right away if you choose **Delete now**. Turn the module back on before then to keep it. See [Modules and Features](modules-and-features.md#how-to-disable-a-module).

### Keep Website Bandwidth Low

To keep a site under its included bandwidth, put long videos on YouTube or Vimeo instead of uploading them. Check **Files that sent the most** on the **Usage** page now and then. See [Website bandwidth](#website-bandwidth).

### Manage Your Files

Storage can fill up if you upload large files. To keep room in your pool:

- Delete images and files you are no longer using on your site. Click **Files** in the top bar to browse everything your workspace stores.
- Resize large images before uploading. Photos straight from a camera can be 5-10 MB each, but a web-optimized version at 200-500 KB looks just as good on screen.
- Remove duplicate files.

### Turn On Auto Top-Up

With auto top-up, a site that uses all its bandwidth or a campaign that uses all its emails keeps going, because we add credits to your balance when it runs out. See [Credits](../account/usage-and-billing.md#credits).

---

## Where to Go Next

- **[Modules and Features](modules-and-features.md)** -- Learn more about each module and how to enable or disable them.
- **[Files (File Manager)](media-library.md)** -- Learn how to manage your uploaded files and keep storage under control.
- **[Managing Pages](managing-pages.md)** -- Learn how to create, edit, and organize your site's pages.
- **[Team and Permissions](team-and-permissions.md)** -- Learn how to manage admin users and team access.
