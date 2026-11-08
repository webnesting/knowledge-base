# Managing Pages in the Builder

**Last verified:** 2026-11-08 4:26pm

The Website Builder is where you design and edit your pages visually. But it is also where you can switch between pages, create new ones, and manage how they are organized -- all without leaving the builder. This guide covers everything you need to know about working with pages inside the builder.

---

![The Pages panel in the builder, listing the site's pages and system pages, with the gear on a page's row ringed](../images/website-builder/pages-panel.png)

## The Pages Panel

The pages panel is your home base for navigating between pages while you work in the builder. It lives in the panel rail down the **right** side of the screen.

### Opening the Pages Panel

1. Open the Website Builder.
2. Look at the column of icons down the right side. 
3. Click the **Pages** icon (it looks like a small document).
4. The pages panel opens, showing a list of all your pages. Click the icon again to pin the panel open so it stays put while you work.

The panel shows your pages organized into groups. Your main site pages are under **Pages**. Pages that belong to a module, such as blog articles, have their own groups. You will also see a **System Pages** group for the built-in pages every site needs (**Page Not Found** and **Coming Soon**). You can edit them, but you cannot delete them. Each row shows the page name, and pointing at it shows the page address, such as `/index`.

---

## How Many Pages a Site Can Have

A site on the **Free** plan can have **5 pages**. If you try to make a 6th page, WebNesting says "Free sites have 5 pages. Upgrade to Starter for unlimited pages." and does not make it. This holds for every way of making a page: **New page**, **Duplicate**, and bringing back a page you deleted. Sites on a paid plan have unlimited pages.

These do not count toward the 5:

- Translations of a page into another language.
- The sign-in pages (**Login**, **Register** and the others) that WebNesting makes when you turn on site accounts.
- The pages that belong to a blog post, an event or a store product.
- The built-in pages you cannot delete, such as your homepage and **Page Not Found**.

To make room on a Free site, delete a page you no longer need, or upgrade the site to Starter.

---

## Switching Between Pages

You can jump to any page on your site directly from the builder.

1. Open the **Pages** panel.
2. Browse the list of pages.
3. Click the name of the page you want to edit.
4. The builder will load that page in the main editing area.

The page you are currently editing is highlighted in the list so you always know which one you are working on.

> **Tip:** In Canvas View you can skip switching altogether -- add several pages as frames and edit them side by side on one canvas.

---

## Viewing the Page Hierarchy

If your site has parent and child pages (for example, a "Services" page with sub-pages like "Web Design" and "Consulting"), the pages panel shows this structure visually.

### Expanding Child Pages

1. Open the **Pages** panel.
2. Look for pages that have a small arrow button next to their name. These pages have child pages beneath them.
3. Click the arrow button (its name is **Expand** followed by the page name) to reveal the child pages.
4. Click it again to collapse the list.

Child pages are indented beneath their parent, making it easy to see how your site is organized. You can expand multiple levels to see deeply nested pages.

If you delete a page that has child pages, the child pages will move up to the top level of your page hierarchy.

> **Tip:** If a page has a lot of child pages, they load on demand when you expand the parent. This keeps the pages panel fast and responsive even on large sites.

---

## Creating a New Page from the Builder

You do not need to go back to the dashboard to add a page. You can create one right from within the builder.

### Creating a Top-Level Page

1. Open the **Pages** panel.
2. Click the **New page** button at the top of the panel.
3. A form will appear where you can set the page details (title, URL, layout, and more).
4. Enter a **Title**, pick a **Layout**, and fill in anything else you need.
5. Select **Create**. Any unsaved canvas work is saved first, then you land on the new page, ready to edit.

![The New page window with a title entered and the Create button ringed](../images/website-builder/page-management-new-page-dialog.png)

### Creating a Child Page (Sub-Page)

1. Open the **Pages** panel.
2. Find the page that you want to be the parent.
3. Point at the page's row and click **New sub-page under** that page (the arrow icon at the end of the row).
4. A form will appear with the parent page already selected.
5. Fill in the page details and select **Create**.
6. The new child page will appear nested under the parent in the list.

---

## Editing Page Properties

Each page has a set of properties that control its title, URL, layout, and other settings. You can edit these properties without leaving the builder.

### How to Open Page Properties

1. Open the **Pages** panel.
2. Find the page you want to edit.
3. Point at the page's row and click the **gear icon** (**Page settings for** that page).
4. A window opens with all of the page's settings. Select **Save** to keep your changes or **Cancel** to drop them.

![The Page settings window with the Sub-Menu choices ringed, above the Navigation settings](../images/website-builder/page-management-page-settings.png)

### Page Title

The page title is the name that appears in browser tabs, search results, and your site's navigation menus. Keep it clear and descriptive.

1. Open the page properties.
2. Find the **Title** field.
3. Type the new title.
4. Save your changes.

### Page URL (Slug)

The URL slug is the part of the web address that comes after your domain. For example, if your site is `yoursite.com` and the slug is `about-us`, the full address will be `yoursite.com/about-us`.

1. Open the page properties.
2. Find the **Page URI** field.
3. Enter the slug you want.
4. Save your changes.

> **Tip:** Keep URL slugs short, lowercase, and use hyphens instead of spaces. A slug like `our-services` is clearer and more search-friendly than `Our_Services_Page`.

### Choosing a Layout

Layouts control the overall structure of your page -- where the header appears, where the main content goes, and what the footer looks like. Every page is assigned a layout.

1. Open the page properties.
2. Find the **Layout** field. It is searchable, so you can type to filter a long list.
3. Browse the available layouts. Layouts are organized into groups.
4. Select the layout you want. As you pick, the page behind the window previews under the new layout so you can see the change before committing.
5. Click **Save** to make it real, or **Cancel** to put everything back exactly as it was.

> **Tip:** If the layout you want does not exist yet, just type a new name into the Layout picker -- it will be created for you when you save.

### Menu Visibility

You can control which navigation menus include a link to this page.

1. Open the page properties.
2. Find the **Menu Visibility** checkboxes.
3. Check or uncheck the menus where you want this page to appear:
   - **Header** -- The main navigation at the top of your site
   - **Header Secondary** -- A secondary navigation area in the header
   - **Footer** -- The navigation in your site's footer
   - **Footer Secondary** -- A secondary footer navigation area
   - **Footer Important** -- A highlighted footer section
   - **Include on Sitemap** -- Whether this page appears in your sitemap for search engines
4. Save your changes.

The **Sub-Menu** setting, just above **Menu Visibility**, has two choices: **Normal** and **Children**. **Children** shows this page's own pages in the header menu, on this page and every page under it.

### Menu Link

A page can send visitors somewhere else. Enter an address in the **Menu Link** field, such as `https://shop.example.com` or `/sale`. Menus then link there, and visitors who open this page go there too. Leave the field empty for a normal page.

### Page Icon

You can assign an icon image to a page. This icon may appear in navigation menus or other areas of your site depending on your theme. In a menu, a simple line icon in SVG format looks best. Use a square icon with no words in it: a menu shows it small, so a wide logo with its name becomes too small to read. An SVG drawn in "currentColor" takes the menu's text color, in light and dark mode.

1. Open the page properties.
2. Find the **Page Icon** field.
3. Click **Add image** and select an image.
4. Save your changes.

### Menu Description

A menu description is one short line about the page, up to 80 characters, such as "See every visit, source and sale as it happens". It shows under the page's name in your header's drop-down or mega menu, next to its **Page Icon**.

1. Open the page properties.
2. Find the **Menu Description** field, under **Navigation**.
3. Type one line.
4. Save your changes.

To show it, click your header in the Website Builder, open **Settings** and set **Page details** to **Icon and description** (see [Layouts and structure](layouts-and-structure.md)). The top items of a menu never show a description. On a site in more than one language, give each language its own menu description.

### Lock Page

If you want to hide a page from visitors, you can lock it so only your team can see it.

1. Open the page properties.
2. Find the **Lock Page** setting.
3. Check **Site Admin**.
4. Save your changes.

A locked page shows only in the builder's preview, and only to team members who can use the Website Builder on that site. Everyone else, on your published site too, sees your **Page Not Found** page.

---

## Planning Your Site Navigation

Your site's navigation menus are built automatically from your pages. Understanding how this works helps you create a clear, organized site that visitors can navigate easily.

### How Header Navigation Is Generated

The main navigation menu at the top of your site is generated from your pages list. Any page with the **Header** menu visibility checkbox turned on will appear in the header navigation.

1. Open the **Pages** panel in the builder.
2. Click the **gear icon** on a page's row to open its properties.
3. Under **Menu Visibility**, check or uncheck **Header** to control whether the page appears in the main navigation.

Pages appear in the navigation in the same order they appear in your pages list. To change the order of your navigation items, rearrange your pages in the dashboard.

### Creating Dropdown Menus with Page Hierarchy

When you create child pages under a parent page, the child pages automatically appear as a dropdown menu under the parent in the header navigation.

For example, if you have a "Services" page with child pages "Web Design," "Branding," and "Consulting," visitors will see a "Services" dropdown in the navigation with those three options underneath.

1. Create a parent page (like "Services").
2. Create child pages under it (see "Creating a Child Page" above).
3. Make sure both the parent and child pages have the **Header** menu visibility turned on.

> **Tip:** Keep dropdown menus to one or two levels deep. Deeply nested menus are hard to use, especially on mobile devices.

### Footer Navigation Strategy

Footer navigation serves a different purpose than header navigation. While the header holds your main pages, the footer is a good place for:

- Legal pages (Privacy Policy, Terms of Service)
- Contact information
- Sitemap links
- Secondary pages that do not need to be in the main menu

Use the **Footer**, **Footer Secondary**, and **Footer Important** menu visibility checkboxes to control which pages appear in each footer area.

> **Tip:** Keep your header navigation focused on your most important pages (7 items or fewer is ideal). Move less critical pages to the footer to keep the main menu clean and easy to use.

---

## Search Engine Optimization (SEO)

Each page has its own SEO settings that help search engines understand and display your page in search results. These settings are found in the page properties, in the **SEO** group.

### Available SEO Fields

- **Show on search engines**: Choose **Yes** to let search engines find and list this page, or **No** to hide it. A new page starts on **No**, so change it to **Yes** when the page is ready for visitors.
- **SEO Title**: The title that appears in search engine results. If left blank, your page title is used.
- **SEO Author**: The author name shown in search results for this page.
- **SEO Description**: A short summary of the page that appears below the title in search results. Keep it under 160 characters for best results.
- **SEO Keywords**: Words and phrases related to the page's content that help search engines categorize it.
- **Share Image**: The picture shown when someone shares this page on social media. Leave it empty to use the image from your site's SEO defaults.

![The SEO group in Page settings with the Show on search engines choice ringed](../images/website-builder/page-management-seo-fields.png)

> **Tip:** The SEO description is what people see in Google or other search engines before they click on your link. Write a clear, inviting summary that tells visitors what the page is about.

---

## Page vs. Widget Editing Mode

The builder supports two different editing modes. Most of the time you will be working in page mode, but it is good to know the difference.

### Page Mode

This is the standard editing mode. When you open the builder or click on a page in the pages panel, you are in page mode. You see the full page with its layout, header, content area, and footer. You can add components, edit text, and style elements.

### Widget Mode

Widgets are reusable content blocks that can appear on multiple pages. When you edit a widget, you are working on that block in isolation -- separate from any specific page. Changes to a widget will update everywhere that widget is used.

If the Widget Builder module is enabled on your site, open **Widgets** in the site menu on the left (next to **Website Builder**), then pick a widget to edit it.

To return to page editing, open **Website Builder** and click a page in the **Pages** panel.

---

## Working with Page Layouts

Layouts define the structural framework of your pages. They determine where the header, content area, footer, and any sidebars are placed.

### What Layouts Are

Think of a layout as a blueprint. While the page content (text, images, components) is different on every page, the layout defines the "skeleton" that holds that content. For example:

- A **full-width layout** might have a header at the top, a wide content area in the middle, and a footer at the bottom.
- A **sidebar layout** might have the same header and footer, but split the middle section into a main content area and a sidebar.
- A **landing page layout** might remove the header and footer entirely, giving you a clean canvas.

Your site can have as many layouts as you need. Different types of pages can use different layouts.

### How to Change a Page's Layout

1. Open the **Pages** panel in the builder.
2. Click the **gear icon** on the row of the page you want to change.
3. Find the **Layout** field in the page properties.
4. Select a different layout.
5. Click **Save**.

The page will reload with the new layout applied. Your content will be placed within the new layout structure.

### How Layouts Define the Structure

Each layout controls which areas appear on the page:

- **Header** -- The top section of your page, often containing your logo and navigation menu. This is shared across all pages that use the same layout.
- **Content Area** -- The main body of the page where your unique content goes. This is where you add and arrange your components.
- **Footer** -- The bottom section of your page, often containing links, contact information, and copyright text. Like the header, this is shared across pages using the same layout.

When you edit a page in the builder, you are mainly working in the content area. The header and footer come from the layout and are consistent across all pages that share it.

> **Tip:** If you want a page to have a completely unique look that is different from all your other pages, ask your site administrator about creating a new layout for it.

---

## The Top Toolbar

The top toolbar runs across the top of the builder. The full tour of it is in the [Website Builder Overview](builder-overview.md#the-top-toolbar). The parts that matter for pages:

- **Page**, **Layout** and **Unlocked** -- Choose whether you edit the page, its shared layout (the header and footer), or everything at once.
- **Undo** and **Redo**.
- **Mobile**, **Tablet**, **Laptop**, **Desktop** and **Auto** -- Preview the page at different screen widths. Click one to resize the editing area and see how your page adapts.
- **Saved** pill -- Shows whether your changes are saved. It reads **Unsaved** or **Saving…** while a save is due or running.
- **Preview** -- Hides the editing tools so you see the page as a visitor does.
- **Save draft** and **Publish** -- Save your work as a draft, or put it on your live site.

> **Tip:** Always check your page at the smallest screen size before publishing. Mobile visitors often make up a large portion of your site traffic, so you want to make sure everything is easy to read and use on a phone.
