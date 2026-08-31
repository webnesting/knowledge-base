# Connecting an AI Tool

**Last verified:** 2026-08-31 12:10pm

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

> **Tip:** start a new conversation in your AI app and ask "what can you do in WebNesting?" — it will tell you which workspaces and sites it can reach and what it's allowed to do.

---

## What "Acts as You" Means

The AI is signed in as **your** WebNesting account, so:

- **It can only do what you can do.** If you can't edit a site, neither can the AI. If your access changes later, the AI's access changes with it — instantly.
- **It only touches the workspaces you picked** when connecting. It can never reach a workspace you didn't select, and never one you're not a member of.
- **Your changes are labelled.** Anything the AI does shows up in your **Activity Log** marked with the app that made it — for example "via Claude Desktop" — right next to changes you made yourself in the browser.

---

## What an AI Tool Can and Can't Do

**It can:**

- Read your content, sites, contacts, usage, and billing summary.
- Create and update content — pages, articles, events, products, and other module records.
- Turn on a content module for a site — but only after it shows you the monthly price and you say yes.
- Delete a record — but only after it describes what will be removed and you confirm.

**It can't** (these always stay in your hands):

- Delete a site.
- Change members, roles, or permissions.
- Change billing or payment details.
- Turn off a module (which would delete its data).

For any of those, the AI won't act — it will hand you a direct link to the right page in WebNesting so you can do it yourself.

---

## Using an AI App That Only Supports Local Connectors

Some older AI apps can only connect to tools running on your own computer (a "stdio" connector) and can't add a web address directly. For those, a small free open-source helper called **`mcp-remote`** bridges the gap — it runs locally and forwards to `https://webnesting.app/mcp`, handling the sign-in for you. Most current apps (Claude Desktop, Claude Code, Cursor) support web connectors directly and don't need it.

---

## Disconnecting

You're always in control:

1. Open **Workspace Settings → Connected apps**.
2. Find the AI app in the list — each shows its name, the workspaces it can reach, and when it last did something.
3. Click **Disconnect**.

The AI loses access immediately. The next time it tries to do anything, it's signed out and would have to be reconnected (with your approval) to work again. Disconnecting one app never affects your other connections or your own sign-in.

---

## Frequently Asked

**Is this the same as the API plan?**
No. Connecting an AI tool this way is free. The paid **API & AI Access** plan is a separate product for developers who paste an access token into their own code.

**Can a teammate's AI tool act as me?**
No. Each connection is signed in as the person who approved it, acting only as themselves. There's no way to connect an AI tool "as" someone else.

**What if I leave the workspace?**
The connection stops working — it only ever had your access, so when your access ends, so does the AI's.
