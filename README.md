# Email Signature HTML Templates

9 free, copy-and-paste HTML email signature templates. Table-based layouts with inline CSS, built for Outlook, Gmail, Apple Mail and other major email clients.

Want to change colors, add your logo, or manage signatures for a team without touching code? **[Edit any of these templates visually at SignatureForEmail.com](https://signatureforemail.com/site/visual-editor?utm_source=github&utm_medium=readme&utm_campaign=templates-header)**

## Contents

- [Templates](#templates)
- [How to use a template](#how-to-use-a-template)
- [Compatibility notes](#compatibility-notes)
- [Customizing](#customizing)
- [License and attribution](#license-and-attribution)
- [Contributing](#contributing)

## Templates

Each template is a single `.html` file in the [`templates/`](templates/) folder.

### Basic: simple and the most compatible

| Template | Description | File | Edit visually |
|---|---|---|---|
| Basic | Text only: name, title, phone, email, website | [basic.html](templates/basic.html) | [Open](https://signatureforemail.com/site/visual-editor?utm_source=github&utm_medium=readme&utm_campaign=basic) |
| Basic with photo | Photo on the left, contact details on the right | [basic-photo.html](templates/basic-photo.html) | [Open](https://signatureforemail.com/site/visual-editor?utm_source=github&utm_medium=readme&utm_campaign=basic-photo) |
| Basic with icons | Photo, contact details and a row of social icons | [basic-icons.html](templates/basic-icons.html) | [Open](https://signatureforemail.com/site/visual-editor?utm_source=github&utm_medium=readme&utm_campaign=basic-icons) |

### Advanced: business signatures

| Template | Description | File | Edit visually |
|---|---|---|---|
| Advanced, logo on top | Company logo, photo and details, social icons, promo banner, legal disclaimer | [advanced-logo-top.html](templates/advanced-logo-top.html) | [Open](https://signatureforemail.com/site/visual-editor?utm_source=github&utm_medium=readme&utm_campaign=advanced-logo-top) |
| Advanced, logo below photo | Photo with logo underneath, details and social icons, promo banner, legal disclaimer | [advanced-logo-below-photo.html](templates/advanced-logo-below-photo.html) | [Open](https://signatureforemail.com/site/visual-editor?utm_source=github&utm_medium=readme&utm_campaign=advanced-logo-below-photo) |

### Modern: designed layouts

| Template | Description | File | Edit visually |
|---|---|---|---|
| Modern blue | Card layout with a round photo, icon contact lines, color social icons, company logo row and disclaimer | [modern-blue.html](templates/modern-blue.html) | [Open](https://signatureforemail.com/site/visual-editor?utm_source=github&utm_medium=readme&utm_campaign=modern-blue) |
| Minimal mono | Black and white, uppercase name, grayscale social icons, "View Portfolio" button, banner | [minimal-mono.html](templates/minimal-mono.html) | [Open](https://signatureforemail.com/site/visual-editor?utm_source=github&utm_medium=readme&utm_campaign=minimal-mono) |
| Modern teal | Vertical social icon column, "Schedule a Call" button, full-width bottom banner | [modern-teal.html](templates/modern-teal.html) | [Open](https://signatureforemail.com/site/visual-editor?utm_source=github&utm_medium=readme&utm_campaign=modern-teal) |
| Modern purple | Rounded photo, contact info box, outlined "Get Started" button, banner | [modern-purple.html](templates/modern-purple.html) | [Open](https://signatureforemail.com/site/visual-editor?utm_source=github&utm_medium=readme&utm_campaign=modern-purple) |

## How to use a template

1. Open the `.html` file and replace the placeholder text (name, title, phone, links) with your own.
2. Replace the placeholder images (`placehold.co` and icon URLs) with images hosted on your own server or CDN. Email clients can't load local file paths.
3. Replace the `example.com` / `yourcompany.com` links with your real links.
4. Open the file in a browser, select the rendered signature, and copy it.
5. Paste it into your email client's signature settings.

Pasting the rendered signature works better than pasting raw source code in most clients.

## Compatibility notes

- Layout uses nested tables, because Outlook (Windows) ignores most modern CSS.
- Styles are inline. `<style>` blocks and external stylesheets are stripped by many clients.
- The **Basic** and **Advanced** templates use the simplest markup and are the safest choice for older Outlook versions.
- The **Modern** templates use rounded corners, shadows and round photos. Outlook (Windows) shows these as square corners with no shadow; the signature still works. The call-to-action buttons include an Outlook-specific fallback.
- Use PNG or JPG for images. Avoid SVG and WebP, which several clients don't render.
- Set `width` and `height` on every image and always include `alt` text, since some clients block images by default.
- Always test by sending a message to yourself in the clients your recipients use.

## Customizing

Edit the HTML directly, or skip the code and use the **[visual editor](https://signatureforemail.com/site/visual-editor?utm_source=github&utm_medium=readme&utm_campaign=customizing)**: change colors and fonts, upload a logo and photo, and get a ready-to-paste signature.

Teams can also use it to keep every employee's signature consistent and to see how many people click the links in them.

## License and attribution

These templates are licensed under [Creative Commons Attribution 4.0 (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

You may use, modify and share them for personal and commercial purposes, **provided you give credit**. For use in your own email signature, no credit is needed in the signature itself. If you republish or redistribute the templates (in a repo, template pack, blog post or product), include this credit with a link:

```
Email signature templates by SignatureForEmail.com (https://signatureforemail.com)
```

## Contributing

Pull requests are welcome. Please:

- Keep templates table-based with inline CSS.
- Test in at least Outlook (Windows), Gmail and Apple Mail.
- Use placeholder text and images only; no real personal data.
- Name files in lowercase with hyphens (`my-template.html`).

Found a rendering bug in a specific client? [Open an issue](../../issues) and include the client name and version.

---

Maintained by [SignatureForEmail.com](https://signatureforemail.com/?utm_source=github&utm_medium=readme&utm_campaign=footer) · Email signature generator with tracking
