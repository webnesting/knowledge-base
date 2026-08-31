# Integrations

**Last verified:** 2026-08-31 12:10pm

Integrations connect WebNesting to the other tools you already use — your Google or Microsoft account for email and analytics, and GitHub for content. Everything lives on one page: **Workspace Settings → Integrations**. You can also reach the same page from a site's settings, where it shows just the connections that power that site.

---

## What You Can Connect

| App | What it powers |
|-----|----------------|
| **Google** | A Gmail inbox for your helpdesk, and Google Analytics reports for your sites |
| **Microsoft** | An Outlook / Microsoft 365 inbox for your helpdesk |
| **GitHub** | Content for your workspace's Internal Docs or a site's Knowledge Base, kept in a repository |

Each connection shows which products it powers, when it was last used, and whether it's healthy. More apps are on the way.

---

## Connecting an App

1. Open **Workspace Settings → Integrations**.
2. Find the app under **Browse** and click it. A panel opens showing exactly what the app will be able to access, in plain English.
3. Click **Connect**. You'll be taken to the provider to approve — for Google and Microsoft that's the familiar account-consent screen; for GitHub it's the app-install screen (about 30 seconds, see below).
4. You land back on the Integrations page with your new connection ready to set up.

You can connect more than one account from the same provider — for example one Google account for your support inbox and another for Analytics. Connected apps show a **Connect another account** option.

---

## Connecting GitHub

GitHub works a little differently from Google and Microsoft — instead of signing in with your account, you install the **WebNesting app** on your GitHub organization or personal account:

1. Click **GitHub** on the Integrations page, then **Connect GitHub**.
2. GitHub asks where to install the WebNesting app and which repositories to grant. Pick only the repositories you want WebNesting to use — you can change this any time from your GitHub settings.
3. Approve. You're back in WebNesting with the connection set up.

Once connected, open the connection's **Content sync** feature to choose what each repository powers:

- **Workspace Internal Docs** — your team's internal documentation
- **A site's Knowledge Base** — the help articles on one of your sites

Each row picks a repository, a branch, and optionally a folder within the repository. One GitHub connection can power several destinations.

> **Heads up:** choosing repositories today sets up where content will flow. The two-way syncing itself (push a file to your repo, see the article update — and the other way around) arrives in an upcoming update.

If you remove a repository from the app's access in GitHub, any setup rows using it pause automatically and show that access was revoked — re-grant the repository in GitHub to resume.

---

## Testing a Connection

Every connection has a **Test** button that performs a real round-trip — sending a test email to the connected inbox, reading your Analytics account, or checking which repositories WebNesting can reach. If something is wrong, the connection shows **Needs attention** with a **Reconnect** button; your settings are kept while you reconnect.

---

## Disconnecting

Open the connection and click **Disconnect** at the bottom of the panel. Anything the connection powers stops working until you connect again — WebNesting keeps your setup so reconnecting the same account picks up where you left off.
