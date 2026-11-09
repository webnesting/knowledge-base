# How to put a form on another website

**Last verified:** 2026-11-08 9:13pm

You can show a form from your WebNesting site on any other website, such as your blog or a partner's page. The form keeps your site's look. Every answer arrives on the form's **Submissions** tab, the same as an answer sent on your own site.

## Before you start

- You need the **Forms** module on your site. See [Modules and Features](modules-and-features.md#forms).
- The form must be published, and its **Status** must be **Active**. A draft, **Paused** or **Closed** form does not show on another website.
- You need a way to add HTML to the other website's page. Most site builders call this an "HTML", "Embed" or "Custom code" block.

## Steps

1. In your site menu, click **Forms**.
2. Open the form you want to share.
3. Click the **More actions** button (three dots) at the top right.
4. Click **Embed Externally**.
5. Under **Display Mode**, choose how the form appears:
   - **Inline** puts the form in the page.
   - **Popup** adds a button that opens the form over the page.
   - **Slide-In** adds a button that opens the form from the side of the page.
6. For **Popup** or **Slide-In**, type the words for the button in **Button Text**.
7. Choose a code and click its **Copy** button:
   - **HTML Embed (iframe)** works on any website. With **Popup** or **Slide-In**, this code is a link that opens the form in a new tab.
   - **JavaScript Embed** makes the form grow to fit, so it has no scroll bar of its own. Use it when the other website lets you add a script.
   - **Direct Link** opens the form on a page of its own. You can share it in an email or a post.
8. Paste the code into the other website's page, where you want the form.
9. Save or publish that page.

## Check it worked

1. Open the other website's page in your browser.
2. Fill in the form and send it.
3. On your site, open the form and click the **Submissions** tab.

The new answer is at the top. Its page is the address of the other website's page, so you can see where each answer came from.

## If something goes wrong

- **The dialog says "This form is not live yet."** Publish the form and set its **Status** to **Active**. The code then shows the form.
- **The page shows nothing where the form should be.** Check that the form is still published and **Active**. Then check that you pasted the whole code.
- **The form has a scroll bar inside it.** The **HTML Embed (iframe)** code has a fixed height. Use the **JavaScript Embed** code, which grows to fit the form.
- **A visitor who sends the form leaves the other website.** The form has a **Success Redirect URL**, so it sends visitors to that page after they submit. That page opens in the whole browser tab, in place of the other website's page. To keep visitors on the other website, clear **Success Redirect URL**. The form then shows its success message in place.
- **The other website does not accept a script.** Use the **HTML Embed (iframe)** code.
