# Usage and Billing

**Last verified:** 2026-09-28 8:30pm (added "Credits, discounts and refunds" section — staff-client-money-operations Phase 7). Earlier 2026-09-28 6:29pm (Marketing $10/month, contacts $5 per 1,000). Earlier 2026-09-28 12:45pm (Usage ranges: This Month / Last 3 Months / Last 12 Months / Custom; bill summary starts from the charges as shown). Earlier 2026-09-28 11:49am (Usage tab: counts only, Show / Where controls, how things are counted). Earlier 2026-09-28 11:21am (itemized charges list price + allowance; click a charge for its breakdown). Earlier 2026-09-28 11:02am (invoices now group charges by workspace/website with a Show itemized toggle — usage-billing-correctness Phase 7). Earlier 2026-09-28 12:12am (exact hourly rates; scheduled turn-off at month end vs turn off now; API data transfer priced per GB — usage-billing-correctness Phase 6). Earlier 2026-09-27 8:02pm (turning off warns: data deleted after 30 days, free allowance stops). Earlier 2026-09-27 7:59pm (plain pricing wording — no turn-off reassurance). Earlier 2026-09-27 7:49pm (free pages/allowances updated for page-module grants + hourly-earned allowances). Earlier 2026-09-26 6:59pm (added "Turning a product or module off"). Earlier 2026-09-22 2:20pm

WebNesting uses simple, usage-based pricing. This guide explains how pricing works, how to view your usage and bills, and how to pay.

---

## How Pricing Works

### You pay for what you use

WebNesting charges based on what you actually use -- things like the number of pages on your site and how much storage you need. If you use more, you pay more. If you use less, you pay less.

### Free tier

Every site comes with free resources to get you started:

- **5 free pages** -- Your first 5 pages are included at no charge. System pages (your homepage, the 404 page, and other built-in pages) are always free. Turning on the Articles, Events, or Store module adds 10 more free pages to that site for as long as the module stays on -- so a site with Store gets 15 free pages, and 25 with Store and Articles both on.
- **2 GB of free storage** -- Covers your own uploads, helpdesk attachments, and form uploads across your whole workspace.

Many small sites fit entirely within the free tier.

### Usage-based pricing

When you go beyond the free tier, you pay for what you use:

| Resource | Rate | Free Allowance |
|----------|------|----------------|
| Pages | $0.50/page/month | First 5 pages free, +10 more per page module you turn on (Articles, Events, Store) |
| Storage | $1/GB/month | First 2 GB free |
| Contacts | $5 per 1,000/month | First 500 free |

People who create an account on your site are counted as contacts in the row above. There is no separate charge for letting them sign in, and your team members are always included.

### Module add-ons

Some optional features are available as add-ons. These have a flat monthly rate, so you always know what they cost. You only pay for the ones you choose to turn on.

| Add-on | Monthly Cost |
|--------|-------------|
| Articles module | $5/month |
| Events module | $5/month |
| Forms module | $10/month |
| Store module | $20/month |
| Widget Builder | $20/month |
| API Access (REST API tokens) | $10/month |
| Remove Branding | $5/month |

Workspace-level products are also available on a separate monthly rate. Each one also has an exact hourly rate -- the figure your bill actually multiplies by for every hour it's on:

| Product | Rate While On |
|---------|---------------|
| Marketing | $0.013698630136986/hour -- about $10.00/month |
| Helpdesk | $0.020547945205479/hour -- about $15.00/month |
| Tasks | $0.013698630136986/hour -- about $10.00/month |
| API Access | $0.013698630136986/hour -- about $10.00/month |

Some of these products also include per-unit usage (e.g. emails, tickets, active tasks, API requests, API data transfer -- priced per GB) once you exceed the included free allowances. For emails, tickets, and API requests/data transfer, that free allowance builds up hour by hour while the product is turned on, instead of all being granted the moment the month starts -- so the exact amount for a given month follows how many hours are in it. A product earns no free allowance while it's off. Active tasks and API tokens work differently: their free amount is a fixed number (25 tasks, 5 tokens) that's simply always available while the product is on, not something that builds up over time. See [Billing and Usage](../dashboard/billing-and-usage.md) for the full breakdown, including how "earned so far" and "estimated by month end" work while the current month is still open.

### Turning a product or module off

**A site module always turns off right away** -- it has no earned allowance worth keeping. Its data is **permanently deleted after 30 days** unless you turn it back on before then; until then, any files it stored still count toward your storage total until they're deleted, either by you (**Delete now**) or automatically once the 30 days are up.

**A workspace product gives you a choice.** The default, **Turn off on {date}**, schedules it for the end of the current billing month -- it keeps working, keeps being billed, and keeps earning its free allowance until then, so you don't give any of this month's allowance up. **Turn off now** stops it immediately instead, and gives up whatever free allowance it would otherwise have earned for the rest of the month. Either way, once it's off, its data is **permanently deleted after 30 days** unless you turn it back on, and any files it stored still count toward your storage total until deleted.

**Turning the same workspace product off a third time in one billing month is different.** Your first two turn-offs of a product each month work as above. A third one has no choice of timing -- the product keeps working, and keeps being billed and earning its allowance, until the 1st of next month, when it finally turns off. This is a fairness rule, not a way to squeeze extra charges out of you: it exists so you can't flip a product on and off around the clock to dodge billing. The count resets to zero on the 1st of each month.

---

## Viewing Your Usage

### Where to find it

1. Go to your **account portal** and open the **Workspaces** card.
2. Open the workspace whose usage you want to see.
3. Click **Settings** at the bottom of the left icon rail, then **Usage** under **Billing**. (The **⋮** menu in the top bar has a shortcut to **Usage** too.)

### What you'll see

The Usage tab shows how much you use over time -- counts only, no prices. (Everything to do with money, including your free allowances and what this month will cost, is on the **Billing** page.)

- **Show** picks one thing to chart at a time -- for example emails sent, tickets created, contacts or pages.
- The chart covers every day of the range you picked, up to today, including days with nothing on them, so you can see exactly when things happened.

### Choosing date ranges

Pick **This Month**, **Last 3 Months** or **Last 12 Months**, or **Custom** to choose a From and To month. Ranges are always whole months. In the current month, the chart stops at today -- days that haven't happened yet are never drawn as zero -- and for emails, tickets and API calls a lighter bar estimates the rest of the month.

### How things are counted

- **Emails, tickets and API calls** add up: the number is everything that happened in the range.
- **Contacts, active tasks, pages, storage and API tokens** are what you have right now (or, for a past range, what you had at its end) -- they don't add up day after day.

### Usage by where it's used

The **Usage this period** table lists your workspace first, then each of your websites, so you can see which site is driving your usage. Use **Where** to narrow it to one website or your workspace.
---

## Viewing Your Bills

### Where to find them

1. Go to your **account portal** and open the **Workspaces** card.
2. Open the workspace whose bills you want to see.
3. Click **Settings** at the bottom of the left icon rail, then **Plans & Billing** under **Billing**. (The **⋮** menu in the top bar has a shortcut to **Billing** too.)

### What you'll see

Your billing period runs from the 1st to the last day of each month. Bills are generated on the 1st of the following month and are due by the 15th.

Your monthly invoices are listed by month. Each invoice groups its charges by your workspace and by each of your websites:

- **Grouped totals** first -- your workspace and each website, collapsed to one line with a total for each.
- Click a group's name to open it, or **Show itemized** to open every group -- each charge is listed with its price and free allowance. Click a charge to see exactly how it was worked out.
- At the bottom, **Charges** (those amounts added up, each already after its free amount), the **Processing fee**, the **Total**, and a **Refunded** amount if any of this invoice has been refunded.

Anything still outstanding appears in a banner at the top of the Billing page, so unpaid invoices never hide in your history.

### Credits, discounts and refunds

WebNesting support can add a credit or a discount to your account, or issue a refund -- each always shows up as its own line on your invoice, such as "Account credit applied," "Helpdesk discount," "Promotional discount," or "Late fee waived" (shown struck through against the fee it cancels). A refund shows as a **Refunded** amount, and the invoice's status becomes **Refunded** once the full amount is returned -- a partial refund keeps the invoice's normal status. You'll get an email whenever a credit or a refund is added. None of this ever changes what your products cost.

---

## Paying Your Bill

When you have an outstanding balance, you'll see a **Pay Bill** button.

1. Click **Pay Bill**.
2. Enter your payment details. WebNesting accepts credit and debit cards.
3. Your payment is processed securely through Stripe.
4. You'll see a confirmation once your payment goes through.

If several invoices are outstanding, you can pay one at a time or settle all of them at once with a single card payment and a single receipt.

### Autopay

To stop thinking about bills altogether, turn on autopay under **Billing → Settings**. Your bill is then paid automatically each month and late fees never apply to you.

> **Tip:** Your payment information is handled by Stripe, a trusted payment processor. WebNesting never sees or stores your full card number.

---

## What Happens If You Don't Pay

If a bill isn't paid by the due date (the 15th), it is automatically marked overdue. You'll get an email reminder, and a one-time 5% late fee is added to the outstanding balance. Turning on autopay avoids this entirely.

---

## Free Months

If your usage stays within the free tier for a given month, your bill will be $0. These bills are automatically marked as paid, so you don't need to do anything.

> **Tip:** With 5 free pages (more if you have Articles, Events, or Store turned on), 2 GB of storage, and 500 free contacts, many personal and small business sites fit within the free tier. You might not owe anything at all!
