# Connecting an AI Tool

**Last verified:** 2026-10-22 12:03pm

You can connect an AI assistant — like Claude Desktop, Claude Code, or Cursor — directly to your WebNesting workspace. Once connected, you can ask the AI to look things up and make changes for you in plain language: "list my draft articles," "create a new event for next Friday," "what's my current usage this month." The AI works **as you**, with **your** permissions, and never sees your password.

This is free. Using an AI assistant does not put you on the paid API plan.

---

## What You'll Need

- An AI app that supports connectors (Claude Desktop, Claude Code, Cursor, the Claude Code VS Code extension, or any MCP-compatible client).
- Your WebNesting sign-in.
- Your WebNesting connection address:

  **`https://webnesting.app/mcp`**

---

## Connecting

The exact button labels vary by app, but the flow is always the same:

1. In your AI app, open its **Connectors** (sometimes called "MCP servers" or "Integrations") settings and choose to **add a connector**.
2. Paste the WebNesting address: `https://webnesting.app/mcp`.
3. Your browser opens to **WebNesting**. Sign in the way you normally do (your browser may already have you signed in).
4. You'll see a short approval screen: **"Connect {your AI app} to act as you."** Pick **which workspaces** the AI may access — tick one or several. If you only have one workspace, it's selected for you.
5. Click **Connect**. You're sent back to your AI app, which is now linked. That's it — no token to copy, nothing to keep secret.

Changed your mind, or don't recognise the app asking? Click **Cancel** instead. You're sent back to the AI app, nothing is connected, and the app is told you said no.

> **Tip:** start a new conversation in your AI app and ask "what can you do in WebNesting?" — it will tell you which workspaces and sites it can reach and what it's allowed to do.

---

## What "Acts as You" Means

The AI is signed in as **your** WebNesting account, so:

- **It can only do what you can do.** If you can't edit a site, neither can the AI. If your access changes later, the AI's access changes with it — instantly.
- **It only touches the workspaces you picked** when connecting. It can never reach a workspace you didn't select, and never one you're not a member of.
- **Your changes are labelled.** Anything the AI does shows up in your **Activity Log** marked with the app that made it — for example "via Claude Desktop" — right next to changes you made yourself in the browser.
- **Teammates in the Builder see the AI work.** When the AI changes a page someone has open in the Builder, they see the change live, with a chip that names the AI. They can revert its last change or pause AI edits on that page. See [When an AI Tool Edits the Page](../website-builder/builder-overview.md#when-an-ai-tool-edits-the-page).

---

## What an AI Tool Can and Can't Do

**It can:**

- Read your content, sites, contacts, usage, and billing summary. It is told your timezone and each site's, so when it tells you when something happened, it can say it in your time.
- Create and update content — pages, articles, events, products, and other module records.
- Turn on a content module for a site — but only after it shows you the monthly price and you say yes.
- Delete a record — but only after it describes what will be removed and you confirm.
- Work with your contacts, companies, lists and tags; your Marketing campaigns, automations and templates; your Help Desk tickets and settings; your Tasks projects, tasks and time; and your Internal Docs — the same things you can do on those pages.
- Change an element on a page, a layout, a widget or an email that is built in the Builder: its text, its settings, or its HTML. Anyone with that page open in the Builder sees the change as it happens. They can revert it or pause AI edits on that page. While a page is paused, the AI tells you it cannot change that page or the styles of its elements.
- Add, move, copy, group, ungroup and remove elements on a page, a layout, a widget or an email built in the Builder, one at a time, the way you do with the Add panel, by dragging, or with **Duplicate**, **Group**, **Ungroup** and **Delete**. A new element comes with the same starting content as one you drop in yourself. Removing an element needs your yes first, after the AI tells you what goes. Anyone with the page open sees each change at once and can revert it.
- Fill a widget and place it on your pages, even before the widget's first publish. A placed widget shows what you last published in it, and a change to the widget shows everywhere it is placed. A widget has one content for every place it is used.
- Read a whole page, layout, widget or email built in the Builder, rewrite it, and save it back as a draft — but only after it lists what it will add, change and remove, and you say yes. Anyone with it open in the Builder sees the change at once and can revert it. Something a teammate adds after the AI showed you its plan stays, unless you approve a new plan that removes it.
- Read your site's styles — what the Builder's Style panel sets, such as colours, text sizes, spacing and borders, and the values for each screen size — and change them, but only after it lists how many settings it will add, change and remove, and you say yes. It changes only the styles it names, and it tells you when a change can affect other pages too. It cannot change the styles of an element on a page someone paused; a class style, which other pages share, can still change. Anyone with the Builder open sees the new look at once and can revert it. This is how an AI can copy a page's design from one of your sites to another.
- List the animations your elements can use, and see where each of your own animations (your **Keyframes**) is used: on which element, on which page, and whether it plays as an entrance effect or from a style. It can rename one of your keyframes, and every element and style that uses it follows the new name, so nothing stops moving. Anyone with the Builder open sees the new name at once. If some elements could not follow, the AI tells you how many, and asking it again finishes them.
- Look at a page. It takes a picture of the page at desktop, tablet or phone width, as your draft or as published, and sees what your visitors would see. It can look at the page in light or dark mode, so it can check a theme's dark colours without changing what your visitors see. A long page comes as several pictures, from top to bottom. Code from an HTML component shows as a placeholder until the page is published. It can also check the page, as the Builder's **Full report** does, see which parts of the page fail a check and why (for example, which text is too light on its background), and list the colours and sizes set as fixed values instead of your theme's settings, so it can fix them. Each answer has a link to the page in the Builder. Each person can run 10 checks an hour, shared with the **Full report** button, and the AI can take 120 pictures an hour.
- Publish a page, layout, widget or email — after it tells you what goes live and where it shows. Publishing a page also publishes your site's styles, as the **Publish** button does, and takes any elements the AI removed off your live page.
- Read your site's theme, make a custom theme from it with your own colours, and switch your site to a theme — after it tells you that the whole site's look changes and you say yes.
- Do what the buttons on those pages do: add a contact to a list, assign or close a ticket, add an internal note, mark a task done, start a timer, copy a campaign, and more.
- Send a campaign's test email — always to your own email address, never to anyone else.
- Send a campaign, schedule it, pick an A/B test's winning version, email a ticket reply, merge two tags, or remove a contact from a site — but only after it shows you exactly what will happen (who gets the email, what it says, what is removed) and you say yes.
- Read your Help Desk, Tasks and campaign reports, and your Activity Log. A change the AI makes shows in the Activity Log with the name of the AI app, for example "via Claude Desktop".
- Read and change your Site Settings: your social links, search and sharing text, Google tracking IDs, site messages, and your site's time zone. It sees the same settings you see in **Settings** and changes them one at a time by name. A secret, such as a reCAPTCHA key, is never shown to it. Hiding your whole site from search engines needs your yes first.
- Add, change and list your **URLs and Redirects**: send an old address to a new page, show a page at a second address, or send visitors to another website. It checks that the page exists and that an outside address is a full web address, so a redirect never silently does nothing.
- Remove a redirect — but only after it shows you the rule and you say yes. A removed redirect cannot be brought back, but the AI can add it again.
- Build your own collections on a site's **Database** page, such as "Menu Items" or "Team Members": create one, rename it, choose how its records list, and add or change its fields. Then it can add records to it.
- Add fields of your own to contacts, campaigns, Help Desk tickets, internal docs, projects and tasks, and fill them in on those records. This needs the workspace **Settings** permission, the same as the workspace **Database** page.
- Remove a field or delete a whole collection — but only after it shows you what goes, and how many records the collection holds, and you say yes. The **Database** page cannot bring a removed field or a deleted collection back. A collection that belongs to a module, and the built-in workspace tables such as Contacts, cannot be deleted.
- Create a new site — after it shows you the name and address and you say yes. Setting the site up takes a few minutes.
- Add a picture to your **Files** from its web address. Ask for this only for a picture you have the right to use. The AI can give it a description (alt text) and put it in one of your folders or in one site's files. The same picture added twice is kept once.
- Find the pictures in your **Files** that still need alt text, and change a picture: its alt text, title, description (the caption shown with it on your site), whether it is decorative (screen readers skip it) and where it crops from. The change shows on your site at once. It needs your permission to edit files, the same as changing them yourself.
- Turn on a workspace product, such as Help Desk or Tasks — but only after it shows you the monthly price and you say yes.

**It can't** (these always stay in your hands):

- Delete a site.
- Change members, roles, or permissions.
- Change billing or payment details.
- Turn off a module or a workspace product (which would delete its data).

For any of those, the AI won't act — it will hand you a direct link to the right page in WebNesting so you can do it yourself.

---

## Ready-Made Requests

WebNesting gives your AI app a few ready-made requests. Each one tells your AI, step by step, how to do a job well in WebNesting. Your AI does the work, and nothing happens until you start one.

- **Build a website.** Describe your business in a sentence or two. Your AI plans the pages and what goes on each, builds them with the Builder's own elements and writes the words, then makes your look (colours, spacing, text sizes), and checks every page at desktop and phone width. For photos, it uses your own pictures in **Files** first. If none fit, it can add a photo from a web address that you have the right to use, and it gives every picture a description. It does not make up facts you did not give, such as opening hours, prices or a phone number. It marks them for you to fill in. It publishes nothing until you say so.
- **Add a section to a page.** Say what the section is for and where it goes. Your AI builds it to match the rest of the page.
- **Fill in missing alt text.** Your AI finds every picture in your **Files** with no alt text, looks at each one and writes its alt text. A picture that only adds looks, such as a texture or a divider, it marks decorative instead, and it tells you which ones. Name a folder to do only that folder.
- **Restyle a page.** Say how you want it to look, for example "warmer and more rustic". Your AI changes only the look, never your words or the page's layout. A new theme changes every page of your site, so your AI tells you first.

**Where to find them:** in your AI app's list of commands or prompts. In Claude Code they are slash commands, such as `/mcp__webnesting__build_site` (the middle part is the name you gave the connection). If your app takes one word for each box, type your full description anyway: your AI reads everything you typed.

You do not have to use them. If you just ask your AI to build you a site, it follows the same order: first the pages and their words, then the look, then a check of every page.

Your AI can also read your theme's settings list (the colours, spacing, text sizes, corners, shadows and fonts a theme sets). With it, your AI styles pages with your theme's values instead of fixed ones, so your pages follow when you change your theme.

---

## Using an AI App That Only Supports Local Connectors

Some older AI apps can only connect to tools running on your own computer (a "stdio" connector) and can't add a web address directly. For those, a small free open-source helper called **`mcp-remote`** bridges the gap — it runs locally and forwards to `https://webnesting.app/mcp`, handling the sign-in for you. Most current apps (Claude Desktop, Claude Code, Cursor) support web connectors directly and don't need it.

---

## Disconnecting

A **Connected apps** page — where you'll see every AI tool you've connected and remove any one of them yourself — is still being built. Until it's ready, here's what's true today:

- **Removing the connector inside your AI app** stops that app from using WebNesting. Some apps also tell WebNesting they've disconnected, which cancels the connection on our side straight away — but not every app does, and nothing on screen tells you which happened. If you're switching tools, removing the connector is usually all you need. If you're worried about who can reach your workspace, it isn't enough on its own.
- **A connection you stop using expires by itself.** Access is short-lived and renews quietly while the tool is in use; once it goes unused for 30 days, it stops working and the tool has to be reconnected with your approval.
- **To cancel a connection right away** — a lost laptop, a tool you no longer trust — contact support and we'll revoke it for you immediately. Revoking one connection never affects your other connections or your own sign-in.

---

## Frequently Asked

**Is this the same as the API plan?**
No. Connecting an AI tool this way is free. The paid **API Access** plan is a separate product for developers who paste an access token into their own code.

**Can a teammate's AI tool act as me?**
No. Each connection is signed in as the person who approved it, acting only as themselves. There's no way to connect an AI tool "as" someone else.

**What if I leave the workspace?**
The connection stops working — it only ever had your access, so when your access ends, so does the AI's.
