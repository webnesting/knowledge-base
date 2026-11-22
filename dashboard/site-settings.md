# Site settings

**Last verified:** 2026-11-21 8:40pm

Site Settings is where you control the behind-the-scenes details of your website -- things like your logo, search engine preferences, analytics, and social media links. Most of these are "set it and forget it" options that you configure once when you build your site.

---

## Where to Find Site Settings

1. Open your WebNesting dashboard.
2. In the site menu, open **Settings** and click **Site Settings**.
3. The page groups its settings in cards: **Your site**, **Appearance**, **Content**, **Connections** and **Advanced**. Click a card to open that page.

![The site menu with Settings open and Site Settings ringed](../images/dashboard/site-settings-site-menu.png)

![The Site Settings page with its cards for Site Configuration, SEO Defaults, Languages, Theme and more](../images/dashboard/site-settings.png)

Each page has its own **Save Changes** button. A **Settings** link at the top of each page takes you back to this list.

---

## Site Timezone

Your site's timezone decides which days this site counts in -- the days its analytics, form reports and published dates use -- and it is the clock your pages show dates and times in, like a post's publish date. To change it, open **Site Settings**, click **Site Configuration**, and scroll to the **Timezone** section.

- **Use workspace timezone** (the default for every new site) -- the site follows your workspace's timezone, and changes with it.
- **A specific timezone** -- pick one when this site serves customers somewhere else, for example a client's site in another country.

Click **Save Changes** to apply it. Team members who haven't set a timezone on their own profile also see this site's times in it.

---

## Clear Cache

Your site updates by itself after each save, so you do not need to clear anything. Use **Clear Cache** only when a page still looks out of date.

1. Open **Site Settings**.
2. Scroll to **Clear Cache** at the bottom of the page.
3. Click **Clear Cache**.
4. Wait up to about 30 seconds. The page shows "Clearing, this takes up to about 30 seconds".

To clear one page, open **Pages**, click the three dots on its row and choose **Clear Page Cache**. The choice shows only for published pages.

You can clear the whole site once a minute. If you try again sooner, WebNesting asks you to wait. You see these buttons only if you can edit pages.

---

## Languages

Your site can be written in one language or in several. Any language can be the main language, and you can add as many other languages as you want.

**Site language**

The **Site language** is the language your site is written in. You choose it when you create the site. Open **Site Settings**, then **General**, to see it. Browsers, screen readers and search engines read your pages in this language. While your site has one language, you can change it there. With more languages, use **Make Main Language** on the Languages list (see below).

**More languages**

To add more languages, turn on the **Language** module. It is off by default. It takes no module slot. Your plan sets how many extra languages a site can have; see [What each plan includes](../account/usage-and-billing.md#what-each-plan-includes). Open **Settings**, then **Modules**, and turn on **Language**.

Then open **Languages** in the site menu. The list shows each language, with a **Main language** column. Click **+ New Language**, pick a language, and click **Create**. Each language other than the main one gets its own address, like `/fr`. The **Language** switch at the top then lists every language.

![The Languages list with English as the main language, and German and French added](../images/dashboard/site-settings-languages.png)

If the module is off, your site has one language. Adding a language then says **Turn on Languages to add more languages.**

Each language you add gets its own address. Your main language stays at the root (`/about`), and a second language sits under its code (`/fr/about` for French). Adding a language never changes your existing addresses.

**What visitors see in a language**

- A page you have written in that language shows that text at the language address.
- A page with no text in that language shows your main language text at the language address, so a visitor never lands on "page not found". The header, menus and footer are in the visitor's language. Search engines are told that the main language page is the one to list.
- Your menus, breadcrumbs and lists of articles show each page in the visitor's language where text exists. Where it does not, they show the main language text.
- When you are signed in and open a page that has no text in that language, a small bar at the top says so. Visitors never see it.

**Change the main language**

1. Open **Languages** in the site menu.
2. On the language you want, click **Make Main Language**.
3. Read the count. If texts are missing, click **Show what is missing** to see the pages that miss them, or click **Close**.
4. Write the missing texts in that language, then click **Make Main Language** again.
5. Read what changes, then click **Make Main Language** to confirm.

Every page, article, setting and piece of code keeps its text in each language. Only which language is the main one changes. The layout stays the same. The main language moves to the root address (`/about`), and the old main language moves under its code (`/en/about`). Each old address sends visitors to its new one, so links and search results keep working. Your redirects to a page that moved point at its new address. While the change runs, the Website Builder closes and opens again with the new text. If the change fails, your site stays as it was.

**Things to know**

- Removing a language keeps its text. The language stops showing, and its addresses show "page not found", until you add the language back.
- Turning the **Languages** module off gives your site one language. Addresses such as `/fr/about` show "page not found". Your text stays stored. Turn the module on again to get it back.
- Your site does not switch language by itself from the visitor's browser. Visitors choose their language, or search engines send them to it.

**Multiple languages in your settings**

With more than one language, a row of language names sits under these settings. Click a language to write its words:

- **Header & Footer:** the header and footer each language shows. The announcement bar's words are in your header's **Settings** in the Website Builder, one row per language like the header's other words.
- **Site Messages:** the maintenance message.
- **SEO Settings:** the title and description search engines show.

A language you leave empty shows your main language's words. A hollow circle next to a language name means it has no words of its own yet. Empty link words show "Learn more" in the visitor's language. Removing a language keeps what you wrote for it.

To write pages in another language, see [Publishing Your Site in More Than One Language](managing-pages.md#publishing-your-site-in-more-than-one-language).

---

## SEO Settings

SEO stands for Search Engine Optimization. These settings help search engines like Google understand your site and display it correctly in search results.

All of these live on the **SEO Defaults** page: go to **Site Settings** and click **SEO Defaults**.

![The SEO Defaults page with the Title, Description and Image fields and a preview of the search result](../images/dashboard/site-settings-seo-defaults.png)

### Title

This is the name that appears in browser tabs and in search engine results for pages that do not have their own custom title.

1. On the **SEO Defaults** page, find the **Title** field.
2. Enter a clear, descriptive title for your website. For example: "Smith & Co. Accounting -- Tax Services in Portland."
3. Save your changes.

You can insert your site's name or the current page's title automatically by typing `{{ site.name }}` or `{{ page.title }}`. For example, `{{ site.name }} | {{ page.title }}` shows as "Smith & Co. Accounting | About Us" on your About Us page.

A title or description shows the same words to every visitor. `{{ user.first_name or "friend" }}` shows "friend" here, in search results too.

> **Tip:** Keep your title under 60 characters so it does not get cut off in search results.

### Description

This is the short summary that appears below your site's title in search engine results. It helps visitors decide whether to click through to your site. Every page with no **SEO Description** of its own shows this one, your homepage included until you write one for it.

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

To use a different picture for one page, open that page and choose a **Share Image** in its **SEO** group.

> **Tip:** Use an image that is at least 1200 x 630 pixels for the best results across all platforms.

### Your Business in Search Results

Your homepage can tell search engines who you are, so Google can show your business name, logo and contact details beside your result. WebNesting builds this from settings you already have and the few fields below.

1. On the **SEO Defaults** page, find the **Your business in search results** section.
2. Under **Kind of business**, choose **Company or organization**, or **Local business** if customers visit you or you serve your area.
3. Add your **Logo**. Without one, search engines use your site logo, then your site icon. A square picture at least 112 pixels wide works best.
4. Fill in your **Phone number**, **Email address** and address. Leave a field blank to share nothing for it.
5. Under **Link your social profiles**, choose **Yes, link them** to share the profiles from **Social**, or **No, keep them out**.
6. Save your changes.

Your business name is your **Site name** from Site Configuration. This information appears on your homepage only. Search engines decide whether and when to show it.

### Hiding Your Site from Search Engines

If your site is not ready for the public yet (for example, if you are still building it), you can tell search engines not to list any of its pages.

1. On the **SEO Defaults** page, find **Hide site from search engines**.
2. Click the **Hide my whole site** card. Because this affects every page, WebNesting asks you to confirm before it takes effect.
3. Save your changes.

While it is on, the setting shows a warning reminding you that the site is hidden, and your site tells search engines not to index it in two ways: its `robots.txt` file blocks everything, and every page carries a "noindex" instruction. Visitors can still open the site by typing its address.

![The Search engines choice with List my site and Hide my whole site ringed, above the Advanced sitemap and extra code settings](../images/dashboard/site-settings-hide-from-search.png)

**Important:** Remember to switch this back to **List my site** when your site is ready to launch. If you leave it on, people will not be able to find your site through Google or other search engines.

> **Tip:** This is a request that search engines honor, not a lock. Most major search engines respect it, but it is not a guarantee, and pages already listed can take a while to drop out of results.

### Sitemap Address Preferences

A sitemap is a file that lists all the pages on your site (at `yoursite.com/sitemap.xml`). Search engines use it to find and index your content more efficiently. WebNesting generates it for you automatically and keeps it up to date whenever you add, change, or remove pages.

Two on/off switches control how the addresses inside it are written:

- **Use secure (https) links in your sitemap** -- leave this on if your site uses a secure `https://` address (almost all do).
- **Start sitemap links with "www."** -- turn this on only if your site's address includes `www.`

Pick the form that matches how visitors reach your site so search engines see one consistent address for every page. These two switches only apply while **Always use a secure address?** or **Should your address start with "www."?** on the **Site Configuration** page is set to **Either works**. Otherwise the sitemap follows that choice.

### Publishing a List of Your Pages for AI Assistants (llms.txt)

AI assistants such as ChatGPT, Claude and Gemini can read a short, plain list of your pages. The file is called `llms.txt` and lives at `yoursite.com/llms.txt`. It is off until you turn it on.

1. On the **SEO Defaults** page, find **Publish an llms.txt file**, under **AI search**.
2. Turn it on.
3. Save your changes.

The file holds your site name and description, then one line for each page with its title, its address and the description you wrote for search engines. Pages that belong to a collection, such as blog posts, sit under the collection's name. It lists the same pages as your sitemap, so a page you left out of the sitemap or locked behind a login is not listed. It follows your changes as you publish them.

Visitors see "not found" at that address while the setting is off, while **Hide site from search engines** is on, and while a Coming soon page replaces your site.

> **Tip:** Open `yoursite.com/llms.txt` in your browser to see what AI assistants read.

### Keywords

The **Keywords** box, under **Advanced**, takes comma-separated words that describe your site. Google and Bing ignore them today, so most sites leave it blank.

### Extra Code for Every Page's Head

Services such as Google Search Console, Pinterest and Bing give you a verification tag to prove the site is yours. It goes in **Extra code for every page's `<head>`**.

1. On the **SEO Defaults** page, under **Advanced**, find **Extra code for every page's `<head>`**.
2. Paste the tag the service gave you, such as `<meta name="google-site-verification" content="…">`.
3. Click **Save Changes**.

WebNesting adds this code to every page exactly as typed. It runs on your published pages only, never while you edit your site.

Only people with the **Custom Code** permission can change this field, because its code runs for every visitor. Site owners and Admins have it. Other people see the field read-only, with the line "Only people with the Custom Code permission can change this code. Ask your site owner." They can still change and save the other SEO settings. To give the permission, see [Team and permissions](team-and-permissions.md#builder-access).

---

## Cookie Banner

The **Cookie banner** page asks visitors before your site uses cookies for tracking. Until a visitor chooses, tracking stays off. Open it from the **Your site** card on the Site Settings page.

1. Turn on **Show a cookie banner on this site**.
2. Under **Who do you ask before using cookies?**, pick one:
   - **Visitors in the EU and UK.** These visitors must say yes first. Everyone else is told about cookies and can say no. This is the default.
   - **Every visitor.** Every visitor must say yes first, wherever they are.
3. Click **Save Changes**.

The defaults work as they are, so for most sites the switch is the only step.

### See the banner before you publish

Under **How it looks to visitors**, the page shows the banner your visitors see, with your words. It changes as you type. Choose **EU and UK visitors** or **Everyone else** to see what each group sees. Click **Manage preferences** in the preview to see the choices behind it. To see the banner on your real site as a first-time visitor, click **Open my site and see the banner**. Save first, so your site has your latest changes.

### Customize the banner

Click **Customize the banner** to change the banner message, the button words, the privacy page link and the banner position. The message can include a link. The Reject button always looks the same as the Accept button. The privacy link defaults to `/privacy`. The banner sits as a bar along the bottom or as a card in the corner. Your theme sets its colors and fonts.

### What your visitors see

A visitor who has not chosen yet sees the banner at the bottom of the page. It sits on top of the page, so nothing on the page moves.

- A visitor in the EU or UK gets a question. Tracking stays off until they click **Accept all**, **Reject non-essential** or **Manage preferences**. The same applies when WebNesting cannot tell the visitor's country, or when the visitor's browser sends the Global Privacy Control signal.
- A visitor anywhere else gets a notice. Analytics and Marketing run, and the visitor can click **Reject non-essential** to stop them.
- **Manage preferences** opens one switch for Analytics and one for Marketing, each with a sentence about what it does. Necessary cookies stay on because the site needs them.
- The banner stays away on later visits. It comes back after you click **Ask everyone again**, or after the visitor clears their browser data.
- Every page has a **Cookie settings** link in the footer. It opens the choices so a visitor can change their mind. A page with no footer gets a small **Cookie settings** button in the bottom corner.
- A visitor using the keyboard stays inside the choices until they close them. The **Escape** key closes them.

### Your privacy choices

California law asks a site that shares visits with ad platforms for a **Your privacy choices** link. Once you add an ad tag on the **Ad tracking** page, your footer shows this link next to **Cookie settings**. It opens the choices with the keyboard focus on the **Marketing** switch.

- A visitor who turns Marketing off sees "Your opt-out is on." If your ad tags already started, the page reloads once to stop them. They stay off on later visits.
- Some browsers send a Global Privacy Control signal. For those visitors, Marketing stays off with no click, even after **Accept all**, and the banner says why.

A site with no ad tag shows only the **Cookie settings** link.

### Ask everyone again

After you change what your site does with cookies, click **Ask everyone again** and confirm. Everyone who already chose sees the banner on their next visit.

If you use Google Analytics or Tag Manager, your cookie banner decides when that tracking starts. [Google Settings](#google-settings) links to this page.

### What waits for the visitor's choice

With the banner on, WebNesting's built-in analytics and your Google Tag Manager container start after a visitor accepts **Analytics**. Google Analytics on its own starts at once, but saves no cookie until the visitor agrees. Maps, YouTube and Vimeo videos, booking forms, social posts, Disqus comments and your ad tags start after a visitor accepts **Marketing**. Until then, a card tells the visitor what will load.

Your own pasted code can wait too. Change its opening tag to `<script type="text/plain" data-consent-category="marketing">`. Use `analytics` for visitor counting. The code starts after the visitor agrees. With the banner off, everything loads at once.

---

## Google Settings

**Google Settings** (under **Connections** on the Settings page) adds Google's tracking code to your site and holds the reCAPTCHA keys that protect your forms from spam. It has two sections: **Visitor tracking** and **Spam protection**.

![The Google Settings page with Visitor tracking and Spam protection](../images/dashboard/site-settings-google.png)

### Google Analytics and Tag Manager (Visitor tracking)

- **Google Analytics ID** -- your GA4 measurement ID, from Google Analytics → **Admin** → **Data streams**. Type the part after `G-`; the box already shows the `G-`. WebNesting adds Google's tracking code to every page.
- **Google Tag Manager container** -- your container ID, shown next to the container's name in Tag Manager. Type the part after `GTM-`. Click **Check** to ask Google whether that container exists and is published -- an unpublished container does nothing on your site.
- **Wait for the visitor before starting Google's tracking** -- makes your pages load faster. Google's tracking starts when the visitor scrolls, taps or presses a key, or after 10 seconds. Google does not count someone who leaves sooner. WebNesting's own analytics still does, while it is on.

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

## Code from Other Services

**Code from Other Services** adds code that other services give you to your live site: a verification tag from Google Search Console, Pinterest or Bing, an analytics or ad pixel, or a chat or booking widget. To open it, go to **Site Settings**, find **Connections**, and click **Code from Other Services**.

The code never runs while you edit your site. It runs on your published pages only. To see it run before it goes live, use **Preview with Code**.

### Adding code from a service

![The Code from Other Services page with the Top of every page and Bottom of every page boxes, Preview with Code and Publish](../images/dashboard/site-settings-code-from-other-services.png)

The page has two places:

- **Top of every page** -- code that runs before the page shows. Verification tags, analytics and ad pixels go here. A service may call this "the `<head>`".
- **Bottom of every page** -- code that runs after the page's content. Chat and booking widgets go here. A service may call this "before `</body>`".

1. Open **Site Settings → Code from Other Services**.
2. Paste the code the service gave you into **Top of every page** or **Bottom of every page**.
3. Read the lines under the code. They say in plain words what the code loads and sends. Nothing runs while you paste.
4. Optional: click **Preview with Code** to see your Homepage run the code in a safe preview. Click **Close preview** to go back.
5. Click **Publish**.

The code has no draft: **Publish** puts it on your live site at once. Each place then shows when, and by whom, it was published. A place that you changed and did not publish yet says **Not published yet**. Each place can hold up to 256 KB of code.

To remove code, delete it from the box, then click **Publish**.

When your site has more than one language, pick a language in the **Language** switch. Each place then says, for example on a German site with French open, **Runs the German code. Type here to use other code in French.** Type code to use other code in that language. Click **Use the German code** to go back. The style code and the security setting are the same in every language.

A verification tag at the bottom is refused when you publish, because services look for it at the top. Put it in **Top of every page**.

Code in **SEO Defaults → Extra code for every page's `<head>`** (see [above](#extra-code-for-every-pages-head)) runs first, before the code at the top of every page.

> **Tip:** Showing a form? Use the **Form** block in the **Site modules** group of the Web Builder instead. It needs no code. For a map, paste your map service's embed code into an **HTML** block in the Web Builder.

Using the keyboard? After **Publish**, focus moves to the line that says what is live. While **Publish** works, focus stays on it.

If you leave the page with code you did not publish, it asks first.

### Version history

Each place keeps its last 50 versions. Click **History** beside a place to see them in a side panel, newest first.

- A **Live** tag marks the version your live site runs.
- Click a version to see what it did, who did it and when, the lines it changed, and its code.
- **The code before history started** is the code a place held before its first recorded change. It has no author.
- After 50 versions, each new change deletes the oldest one kept.

To bring an earlier version back:

1. Click **History** beside the place.
2. Click the version.
3. Click **Load into Editor**, read the review, then click **Load into Editor** again.
4. The panel closes, and the code is in the editor. Nothing is saved yet.
5. Click **Preview with Code** to check it, then click **Publish**.

If you have typed changes in a place that you did not publish, publish them or undo them first. **Load into Editor** stays off until you do.

### Code for one page only

A page can have its own code too. Open the page in **Pages**, scroll to its **Custom Code** group after **SEO**, then click **Edit Custom Code**. Your site's code runs first, then the page's own code. See [Managing pages](managing-pages.md#custom-code-for-one-page).

### Who can change this code

Only people with the **Custom Code** permission can add or change this code. Site owners and Admins have it. People who may only view it see the code and can preview it, but cannot change it. The page says: "Only people with the Custom Code permission can change this code. Ask your site owner." People without the permission do not see **Code from Other Services** in Site Settings. To give the permission, see [Team and permissions](team-and-permissions.md#builder-access).

---

## Security Policy

Your live site has a security policy. It says which scripts may run on your pages. Scripts you add in **Code from Other Services**, and the scripts WebNesting adds, are allowed. The policy does not allow code inside an HTML attribute, such as `onclick`, code that builds more code from text, or a script added to a page some other way.

To open it, go to **Site Settings**, find **Advanced**, and click **Security Policy**. Most sites never need to change it.

![The Security Policy page in Report only mode, with Switch to Enforce and See Details](../images/dashboard/site-settings-security-policy.png)

### What the page says

The first line says what the policy would block, in plain words:

- "Nothing on your site would be blocked."
- "3 things on your site would be blocked if you turned on Enforce."
- With Enforce on: "Enforce is on. 2 things were blocked in the last 7 days."

Under it, **Now** shows the mode: **Report only** (nothing is blocked; visitors' browsers tell you what would be blocked) or **Enforce** (scripts the policy doesn't allow are blocked on your live site). At first the mode is **Report only**.

### Seeing the details

Click **See Details**. Each line says what would be blocked and on which page, such as "Code inside an onclick attribute on /contact", where it came from, and how often. The list shows the last 7 days and keeps the 200 most recent reports. Some reports are noise: a browser extension can cause one.

Click a line to see how to fix it. The technical names a developer needs are at the bottom, under **For a developer**.

**Fix code inside an attribute.** Move the code into a script, and give the element an `id`. For example, change this:

```html
<button type="button" onclick="location.hash = 'preorder-form'">Pre-order a loaf</button>
```

to this:

```html
<button type="button" id="preorder-button">Pre-order a loaf</button>
<script>
  document.getElementById('preorder-button').addEventListener('click', () => {
    location.hash = 'preorder-form';
  });
</script>
```

### Switching to Enforce

1. Click **See Details** and look at what would be blocked. **Switch to Enforce…** is offered after that.
2. Click **Switch to Enforce…**.
3. Read the list of scripts that will stop running, grouped by page.
4. Click **Switch to Enforce**.

After the switch, a report seen while Enforce is on shows **Blocked**.

**Go back.** Click **Switch Back to Report Only**. It takes one click and needs no confirm. Nothing is blocked after that.

Click **History** beside **Now** to see each switch: who made it and when.

Only people with the **Custom Code** permission can switch the mode. People who may only view it see the page, and the switch is off with the reason beside it. People without the permission do not see **Security Policy** in Site Settings.

---

## Social Media Profiles

Add your social media links so they can appear in your site's header, footer, or anywhere you use social media components.

### Adding Your Social Media Links

![The Social Settings page with a box for each network and Add another network](../images/dashboard/site-settings-social.png)

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

> **LinkedIn:** a name such as `yourcompany` links to your company page (`linkedin.com/company/yourcompany`). For a personal profile, type `in/yourname`, or paste the whole link. On a **Team member** card, a LinkedIn name links to that person's profile (`linkedin.com/in/…`).

---

## Site Images

These are the key images that represent your brand across your website. They live on the **Site Images** page, under **Content** in Site Settings. Each image on the page says where it appears, and the pictures are shown two to a row.

![The Site Images page with Fallback image, Logo and Favicon, and Add your own image](../images/dashboard/site-settings-site-images.png)

### Setting Your Logo

Your logo appears in your site's header and anywhere else your theme displays it.

On a phone, the header shows your logo picture by itself. If your site has no logo picture, the phone header shows your site's name instead. A new site starts with no logo picture, so its header and footer show the site's name until you choose a logo.

The header and the footer each choose whether they show the picture, your site's name, or both: click the header or the footer in the Website Builder and open **Settings → Logo**. One logo picture serves both.

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

These settings control foundational aspects of how your website works -- its name, description, business name, visibility, and web address. They live on the **Site Configuration** page, under **Your site** in Site Settings.

### Launching Your Site (Visibility)

A new website starts in **Coming soon** mode: visitors see a "Coming Soon" page instead of your site, while you keep building. When you are ready for people to see it:

1. Go to **Site Settings**, open **Your site**, and click **Site Configuration**.
2. Under **Visibility**, click the **Live** card.
3. Save your changes.

![The Visibility choice on Site Configuration with the Live and Coming soon cards ringed](../images/dashboard/site-settings-visibility.png)

To take the site back down later, choose **Coming soon** and save. Either way, you always see your real site while you are signed in -- open it in a private browser window to see what visitors see.

While your site is in **Coming soon** mode, only your home address shows the Coming Soon page as a normal page. Any other address shows the same Coming Soon page, marked as "page not found", so search engines do not list those addresses. Your sitemap lists only your home address until you go live.

### Business Name

**Business name** appears in the copyright line at the bottom of every page ("Copyright © 2026 Your Business"). Leave it blank to use your Site Name instead. To show a different name in one footer, use **Name in the copyright line** in that footer's settings.

### Choosing a Theme

Your theme has its own page now. The **Design** section of Site Configuration links to it: click **Change your theme in Appearance → Theme**. You can also open it from Site Settings: under **Appearance**, click **Theme**. There you can switch themes and make a theme's colors your own (see [Themes and customization](themes-and-customization.md)). Under **Appearance**, **Color Mode** picks light or dark mode for your site and turns on a light / dark switch for your visitors (see [Light and Dark Mode](themes-and-customization.md#light-and-dark-mode)).

### Secure (HTTPS) Addresses

A secure address starts with `https://` instead of `http://`, and visitors see a lock icon in their browser.

1. Go to **Site Settings**, open **Your site**, and click **Site Configuration**.
2. Find **Always use a secure address?**
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

### Site Messages and HTML Blocks

**Site Messages** (under **Content**) holds your maintenance message. Your header and footer words are on the header and footer themselves: click them in the Website Builder and open **Settings** (see [Choosing what your header and footer show](../website-builder/layouts-and-structure.md#choosing-what-your-header-and-footer-show)). **HTML Blocks** (under **Advanced**) holds named blocks of formatted text that your theme shows by name. Both keep your formatting: headings, bold and italic text, lists, tables, links, images and embedded videos or maps.

Code does not run there. If you paste a script, or a tag with code inside it, WebNesting removes the code when you save, and your visitors never run it. To add code from another service, such as a chat widget or a tracking tag, use **Code from Other Services**.

### Site Image Groups

**Site Image Groups**, under **Advanced**, manages named collections of pictures that galleries and sliders on your pages can show.

### All Settings (power-user view)

**All Settings**, under **Advanced**, lists every raw setting on your site in one place. Values there are saved exactly as typed, with no checks, except that code in site messages and HTML blocks is removed -- so if a setting has its own page (SEO Defaults, Site Images, Social, Google), edit it there instead. Use All Settings for the custom values you have added yourself -- the **Add your own setting** form at the bottom of the page is where you add them.

> **Tip:** After making changes to any settings, visit your live site in a new browser tab to confirm everything looks the way you expect.

---

## Custom Domain

When you go live, your website is available on a WebNesting address. A custom domain is a web address you own, like `www.yourcompany.com`.

Site Settings has no screen to connect a domain yet. You can enter a domain in the **Custom Domain (optional)** box when you create a site, and **Site Configuration** decides how the address is written (see **Secure (HTTPS) Addresses** and **WWW Preferences** above). To connect or change a domain later, email Support. The steps, and what to expect at your domain registrar, are in [Connecting a custom domain](../getting-started/custom-domains.md).

## Sites Overview

Click **Sites** in the left bar, then **Overview**. It shows visits, where visitors come from and which sources bring signups, form results, orders, site health and storage. With more than one site, each widget asks you to pick a site. A form or orders widget tells you when that site does not use forms or a store. Change the overview with **⋯ → Use as Sites Overview** on any dashboard. See [Dashboards and Reports](dashboards-and-reports.md).
