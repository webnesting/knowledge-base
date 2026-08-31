# Troubleshooting and Common Issues

**Last verified:** 2026-08-31 12:10pm

Every website owner runs into the occasional hiccup. The good news is that most issues have simple fixes. This guide walks you through the most common problems you might encounter and how to solve them quickly.

---

## Can't Log In

If you are having trouble signing in to your WebNesting dashboard, try these steps in order.

### Wrong Password

1. On the login page, click the **Forgot Password** link.
2. Enter the email address you used to create your account.
3. Check your email for a password reset link.
4. Click the link and create a new password.

### Account Not Verified

When you first create your account, WebNesting sends a verification email. If you have not verified your account yet, you will not be able to log in.

1. Check your email inbox for a verification message from WebNesting.
2. If you do not see it, check your spam or junk folder -- it sometimes ends up there.
3. Click the verification link in the email.
4. Try logging in again.

> **Tip:** If the verification email has expired or you cannot find it, use the **Resend Verification** option on the login page to get a fresh one.

### Two-Factor Authentication Issues

If you have two-factor authentication enabled and your authentication app is not working:

1. Try using one of the **recovery codes** you were given when you first set up two-factor authentication.
2. If you have lost your recovery codes, contact our support team (see the bottom of this guide) and we will help you regain access to your account.

### Browser Cache Problems

Sometimes your browser holds onto old login information that causes issues.

1. Clear your browser's cookies and cache.
2. Close and reopen your browser.
3. Try logging in again.
4. If that does not work, try opening a **private** or **incognito** window and logging in from there.

---

## Changes Not Appearing on the Live Site

You made updates, but your visitors are still seeing the old version of your site. Here is what to check.

### Changes Not Published Yet

In WebNesting, **saving** and **publishing** are two different things. Saving stores your work as a draft that only you can see. Publishing makes it live for your visitors.

1. Open the page in the **Website Builder**.
2. Click the **Publish** button in the top toolbar.
3. Confirm that you want to publish.

Your changes should now be live. For more details, see [Saving and Publishing Your Site](../website-builder/saving-and-publishing.md).

### Your Browser Is Showing a Cached Version

Your browser sometimes stores a copy of your site to load it faster. After publishing changes, you might need to tell your browser to fetch the latest version.

If changes are not appearing, try a hard refresh to clear your browser's cache:

1. On the page that looks outdated, do a hard refresh:
   - **On Windows:** Hold **Ctrl + Shift** and press **R**
   - **On Mac:** Hold **Cmd + Shift** and press **R**
2. The page should reload with your latest published changes.

### CDN Cache Is Still Updating

After you publish, it may take a few minutes for the changes to appear everywhere. This is because your site uses a content delivery network that stores copies of your pages in different locations around the world.

1. Wait two to five minutes after publishing.
2. Refresh the page.
3. Your updated content should now appear.

> **Tip:** If changes still are not showing after several minutes, try the hard refresh method described above, or open the page in a private browsing window.

---

## Images Not Loading

If images on your site appear broken or are not showing up, here are the most common causes.

### File Is Too Large

Every site has a maximum file size for uploads. If your image exceeds that limit, it will not upload or display properly.

1. Open **Files** from your dashboard.
2. Check the maximum upload size shown on the upload screen.
3. If your image is too large, resize it using an image editor before uploading it again.

### Unsupported File Format

WebNesting supports the most common image formats: **JPG**, **PNG**, **GIF**, **SVG**, and **WebP**. If your image is in a different format, it will not display.

1. Check the file extension of your image.
2. If it is not one of the supported formats, convert it to JPG or PNG using any image editing tool or free online converter.
3. Upload the converted image to your **Files**.

### Image Was Deleted from the File Manager

If you (or a team member) deleted an image from the File Manager, any page that used that image will show a broken image.

1. Open **Files** and search for the image.
2. If it is no longer there, upload the image again.
3. Open the affected page in the **Website Builder**.
4. Select the broken image element and replace it with the newly uploaded file.

> **Tip:** Before deleting files from the File Manager, check if they are being used on any pages. Deleting a file that is in use will break those pages. For more on managing your files, see [Files (File Manager)](../dashboard/media-library.md).

---

## Page Looks Broken on Mobile

Your page looks great on a computer but something is off on a phone or tablet. Here is how to fix it.

### Responsive Styles Not Set

If you designed your page on a desktop view and did not check how it looks on smaller screens, some elements may not fit properly.

1. Open the page in the **Website Builder**.
2. Use the **Frame Sizer** at the top of the builder to switch between desktop, tablet, and mobile views.
3. At each size, look for elements that are too wide, overlapping, or hard to read.
4. Adjust the styles for each breakpoint until the page looks right at every size.

For a full walkthrough, see [Making Your Site Look Great on All Devices](../website-builder/responsive-design.md).

### Content Is Too Wide for the Screen

Images, containers, or other elements set to a fixed width may overflow on narrow screens.

1. Switch to the mobile view in the builder.
2. Select the element that is too wide.
3. In the **Styler**, change its width to a percentage (like 100%) instead of a fixed pixel value.
4. Check that the element now fits within the screen at all sizes.

### Always Preview at Every Screen Size

The builder's responsive preview is the best way to catch mobile issues before they go live.

1. Design your page on the desktop view first.
2. Switch to tablet view and adjust anything that looks off.
3. Switch to mobile view and make final adjustments.
4. Publish only after you are happy with how the page looks at every size.

> **Tip:** For the most accurate check, open your published site on an actual phone or tablet. The builder preview is very close, but testing on a real device gives you the full picture.

---

## Can't Find a Module or Feature

You are looking for a feature -- like a blog, events calendar, or online store -- but it does not appear in your dashboard.

### Module Not Enabled

Many features in WebNesting are provided by modules that you need to turn on.

1. Open your site menu, open **Settings**, and click **Modules**.
2. Browse the list of available modules.
3. Find the one you need and click to enable it.
4. Once enabled, the module's section will appear in your sidebar, and its components will become available in the builder.

For more details, see [Modules and Features](../dashboard/modules-and-features.md).

### Feature Requires a Different Module

Some features are part of a specific module. For example, product listings require the Store module, and blog posts require the Blog module.

1. If you are not sure which module provides the feature you need, browse the **Modules** section and read the description of each one.
2. Enable the module that matches the feature you are looking for.
3. The new feature will appear in your dashboard and builder after the module is activated.

---

## Custom Domain Not Working

You have connected a custom domain to your site, but it is not loading properly.

### DNS Changes Are Still Propagating

When you update your domain's DNS records, the changes can take time to spread across the internet. This is completely normal.

1. After making DNS changes, wait up to 48 hours for full propagation.
2. During this time, your site may work on some networks but not others.
3. Be patient -- this is a one-time wait. Once DNS propagation is complete, your domain will work reliably.

### DNS Records May Be Incorrect

If your domain is still not working after 48 hours, double-check that your DNS records are set up correctly.

1. Log in to your domain registrar (the company where you purchased your domain).
2. Compare the DNS records you entered with the values provided in your WebNesting **Settings** under your domain configuration.
3. Make sure the **A record** or **CNAME record** matches exactly.
4. Save any corrections and allow time for the changes to take effect.

### SSL Certificate Is Still Being Set Up

After your DNS connects successfully, WebNesting automatically sets up an SSL certificate so your site loads securely. This process may take a few minutes.

1. Wait five to ten minutes after your DNS connects for the first time.
2. Refresh the page.
3. If you see a security warning, wait a bit longer and try again.

> **Tip:** If your SSL certificate has not appeared after an hour, contact our support team. There may be a DNS configuration that needs adjusting.

---

## Accidentally Deleted Something

We have all been there. Here is what you can do depending on the situation.

### Just Happened in the Builder

If you just deleted something and are still in the builder, undo it right away.

1. Press **Ctrl + Z** on Windows or **Cmd + Z** on Mac.
2. The deleted element will reappear.
3. You can press undo multiple times to go back several steps.

### Already Saved or Published

If you saved or published after deleting something and can no longer undo it:

1. Contact our support team as soon as possible (see [How to Contact Support](#how-to-contact-support) below).
2. Let us know your site URL and what was deleted.
3. We can check our backups and help you restore the content.

> **Tip:** Save your work frequently while you are building. The more often you save, the more checkpoints you create. This makes it much easier to recover if something goes wrong.

---

## Builder Loading Slowly

The builder feels sluggish or takes a long time to load. Here is how to speed things up.

### Use a Supported Browser

The builder works best on the latest version of these browsers:

- **Google Chrome**
- **Mozilla Firefox**
- **Apple Safari**
- **Microsoft Edge**

If you are using an older browser or one not listed here, updating or switching may solve the problem.

### Optimize Your Images

Pages with many large images take longer to load in the builder.

1. Before uploading, resize images to the dimensions you actually need (there is no need for a 5000-pixel-wide image if it only displays at 800 pixels).
2. Use compressed image formats like JPG or WebP for photographs.
3. Use PNG only when you need transparency.

For more on managing images, see [Files (File Manager)](../dashboard/media-library.md).

### Clear Your Browser Cache

Old cached files can sometimes slow things down.

1. Clear your browser's cache and cookies.
2. Close the browser completely.
3. Reopen it and load the builder again.

### Check Your Internet Connection

A slow or unstable internet connection will affect how quickly the builder responds.

1. Try loading other websites to see if they are also slow.
2. If your whole internet feels sluggish, try restarting your router or switching to a more stable connection.
3. If possible, use a wired connection instead of Wi-Fi for the most reliable experience.

> **Tip:** If the builder is still slow after trying all of the above, contact our support team. We can check if there is anything on our end that might be affecting performance.

---

## How to Contact Support

If you have tried the steps in this guide and are still stuck, our support team is here to help.

### What to Include in Your Support Request

When reaching out, the more information you provide, the faster we can help.

1. **Your site URL** -- so we can look at your specific site.
2. **A description of the issue** -- what is happening and what you expected to happen.
3. **Screenshots** -- a picture is worth a thousand words. Capture what you see on your screen.
4. **Steps you have already tried** -- let us know what you have done so far so we do not repeat the same troubleshooting.

### How to Reach Us

Send an email to our support team with the details listed above. We aim to respond as quickly as possible and will work with you until the issue is resolved.

> **Tip:** The more details you include upfront, the fewer back-and-forth messages it takes to solve the problem. A screenshot and a brief description of what happened go a long way.

---

## Next Steps

Now that you know how to handle the most common issues, here are some guides that can help you avoid problems in the first place:

- [Saving and Publishing Your Site](../website-builder/saving-and-publishing.md) -- Understand the difference between saving and publishing so your changes always go live when you want them to.
- [Making Your Site Look Great on All Devices](../website-builder/responsive-design.md) -- Learn how to design for every screen size so your pages never look broken on mobile.
- [Files (File Manager)](../dashboard/media-library.md) -- Manage your images and files effectively to avoid broken images and slow load times.
- [Modules and Features](../dashboard/modules-and-features.md) -- Explore all the features available for your site and learn how to enable them.
