# Making Your Site Accessible

**Last verified:** 2026-08-31 12:10pm

Accessibility means making sure everyone can use your website, regardless of how they browse the web. Some visitors use screen readers, some navigate with a keyboard instead of a mouse, and some have difficulty seeing certain colors. This guide explains what accessibility is, why it matters, and how you can make your WebNesting site welcoming to all visitors.

---

## Check Your Page with Site Audit

The builder has a built-in **Audit** panel that checks the page you are working on and scores it in four categories: **Performance**, **Accessibility**, **Best Practices**, and **SEO**.

1. Open the page in the **Website Builder**.
2. Click **Audit** in the panel rail on the right.
3. Run the audit and review the findings. Each one points at the element it is about, so you can jump straight to the problem and fix it.

Running the audit before you publish is the quickest way to catch issues while you can still do something about them, rather than discovering them later.

---

## What Is Accessibility and Why Does It Matter?

Web accessibility means designing your website so that people with disabilities can use it effectively. This includes visitors who are blind or have low vision, people who are deaf or hard of hearing, people with motor disabilities who cannot use a mouse, and people with cognitive disabilities.

But accessibility does not only help people with disabilities. It makes your site easier to use for everyone -- older visitors, people on slow internet connections, and people browsing on small phone screens all benefit from a well-structured, accessible site.

Following these guidelines helps your site meet the Web Content Accessibility Guidelines (WCAG), the international standard for web accessibility.

There are also legal considerations. Many countries have laws requiring websites to be accessible, particularly for businesses and organizations that serve the public. Making your site accessible helps you meet these requirements.

> **Tip:** Think of accessibility as good design. The same practices that help a screen reader user also make your site clearer and easier to use for all your visitors.

---

## Adding Alt Text to Images

Alt text (short for "alternative text") is a written description of an image. It serves two important purposes: screen readers read it aloud so visitors who cannot see the image know what it shows, and search engines use it to understand your images.

### How to Add Alt Text

1. Open your page in the Website Builder.
2. Click on the image you want to describe.
3. Find the **Alt** field in the image settings panel.
4. Type a clear, brief description of what the image shows.
5. Save your changes.

For a detailed walkthrough of image settings, see **[Editing Content](editing-content.md)** -- the Working with Images section.

### Tips for Writing Good Alt Text

- **Describe what you see.** Write a short sentence or phrase that tells someone what the image shows. "A family sitting around a dinner table" is much better than "image1.jpg" or "photo."
- **Be specific but concise.** One or two sentences is usually enough. You do not need to describe every tiny detail.
- **Include important context.** If the image shows a product, mention the product name. If it shows a person, mention who they are if it is relevant.
- **Skip "image of" or "picture of."** Screen readers already announce that something is an image, so starting with "Image of..." is redundant.

### Decorative Images

Some images are purely decorative -- they add visual interest but do not convey important information. For example, a swirling background pattern or a decorative border. In these cases, you can leave the alt text field empty. This tells screen readers to skip the image entirely, which keeps the experience clean for those users.

---

## Using Headings Properly

Headings are not just a way to make text bigger. They create a structure for your page that helps all visitors understand how your content is organized. Screen readers use headings to let visitors jump between sections, much like a table of contents.

### Heading Levels

Headings come in levels from Heading 1 (the largest and most important) to Heading 6 (the smallest). Here is how to use them:

- **Heading 1** -- The main title of the page. Use it once per page for the primary topic.
- **Heading 2** -- Major sections of the page. Use these to divide your content into big topics.
- **Heading 3** -- Subsections within a Heading 2 section. Use these for smaller topics within a larger section.
- **Heading 4 through 6** -- Further subsections, if needed. Most pages will not need to go beyond Heading 3.

### How to Set Heading Levels

1. Click into a text block on your page.
2. Select the text you want to turn into a heading.
3. Open the **Block** dropdown in the text toolbar.
4. Choose the heading level you want (Heading 1, Heading 2, and so on).

For a full guide to the text toolbar, see **[Editing Content](editing-content.md)** -- the Block Type section.

### Common Mistakes to Avoid

- **Do not skip levels.** Going from Heading 1 directly to Heading 4 confuses the structure. Go in order: Heading 1, then Heading 2, then Heading 3.
- **Do not use headings just for visual size.** If you want text to look bigger but it is not actually a section title, use the font size controls instead of making it a heading. Headings should reflect the structure of your content, not just its appearance.

> **Tip:** Think of headings like an outline. If someone read only your headings, they should get a clear picture of what your page covers and how it is organized.

---

## Color Contrast

Color contrast is the difference in brightness between your text and its background. When contrast is low -- like light gray text on a white background -- many visitors will struggle to read it, including people with low vision and people with color blindness.

### Why Contrast Matters

About one in twelve men and one in two hundred women have some form of color blindness. Many more people have low vision, especially older visitors. Even visitors with perfect eyesight will find low-contrast text harder to read in bright sunlight or on a dim screen.

### Best Practices for Readable Colors

- **Dark text on light backgrounds** works well in most situations. Black or dark gray text on a white or light background is the easiest to read.
- **Light text on dark backgrounds** also works well, as long as the contrast is strong. White text on a dark blue or black background is clear and readable.
- **Avoid light text on light backgrounds** or dark text on dark backgrounds. These combinations are hard to read for everyone.
- **Be careful with color alone.** Do not use color as the only way to communicate something. For example, if you highlight required form fields in red, also add a text label like "required."

### Checking Your Colors

Use the responsive preview in the builder to view your site on different screen sizes and at different zoom levels. This can help you spot areas where text might be hard to read.

For details on changing colors and backgrounds, see **[Styling Your Page Elements](styling-elements.md)**.

> **Tip:** When choosing colors for your site, try squinting at the screen. If you cannot read the text while squinting, the contrast may be too low for some of your visitors.

---

## Writing Descriptive Link Text

Links are how visitors move between pages on your site and out to other websites. The text you use for a link matters more than you might think.

### Why Link Text Matters

Screen readers can pull up a list of all the links on a page so visitors can jump directly to the one they need. If every link says "click here" or "read more," that list becomes useless -- the visitor has no idea where each link goes.

### Good vs. Poor Link Text

- **Poor:** "Click here to see our services."
- **Good:** "View our full list of **services**."
- **Poor:** "Read more."
- **Good:** "Read our **guide to choosing the right plan**."

The key is that the link text itself should make sense even if you read it on its own, without the surrounding sentence.

### Tips for Better Links

- Make the link text describe where the link goes. "Download the pricing guide" is clear and helpful.
- Keep link text concise. A few words is ideal. Linking an entire paragraph makes it hard to tell what is clickable.
- Avoid generic phrases like "click here," "learn more," or "read more" on their own. Add enough context so the destination is clear.

---

## Keyboard Navigation

Not every visitor uses a mouse. Some people navigate websites entirely with their keyboard, using the Tab key to move between interactive elements like links, buttons, and form fields. This includes people with motor disabilities, power users, and visitors who prefer keyboard shortcuts.

### What You Can Do

- **Use proper components.** When you add a button from the component palette, it is automatically reachable by keyboard. The same goes for links created in the text toolbar. These built-in components are designed to work with keyboard navigation.
- **Avoid using styled text as a fake button.** If something looks like a button but is really just bold, colored text, keyboard users will not be able to reach it or click it. Always use a real Button component for clickable actions.
- **Test it yourself.** Open your published site in a browser and try pressing the Tab key repeatedly. You should be able to reach every link, button, and form field on the page. If you cannot, something may need to be adjusted.

> **Tip:** When you press Tab and move to an element, you should see a visible outline or highlight around it. This is called a focus indicator, and it shows keyboard users where they are on the page.

---

## Form Accessibility

If your site includes forms, make sure every form field has a visible label. Placeholder text alone is not enough, as it disappears when visitors start typing. A visible label above or beside each field ensures that all visitors -- including those using screen readers -- can understand what information is being requested.

---

## Quick Accessibility Checklist

Use this checklist to review your site before publishing. It covers the most impactful things you can do to make your site accessible.

- Every image has descriptive alt text (or empty alt text for purely decorative images)
- Headings are used in proper order (Heading 1, then Heading 2, then Heading 3) without skipping levels
- Text has strong contrast against its background (dark on light or light on dark)
- All links have descriptive text that makes sense on its own
- Interactive elements (buttons, links, form fields) are reachable using the Tab key
- Color is not the only way information is communicated
- Your site is readable and usable on all screen sizes, including phones
- Page titles are clear and descriptive

Going through this checklist each time you publish an update will help you catch common issues before your visitors encounter them.

---

## Next Steps

- **[Editing Content](editing-content.md)** -- Learn how to add alt text to images and set heading levels
- **[Styling Your Page Elements](styling-elements.md)** -- Adjust colors and contrast for better readability
- **[Making Your Site Look Great on All Devices](responsive-design.md)** -- Ensure your site is usable on every screen size
- **[Site Settings](../dashboard/site-settings.md)** -- Configure SEO settings that overlap with accessibility best practices
