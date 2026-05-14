# The Caregiver's Survival Guide — v1 Website

This is the source code for **thecaregiverssurvivalguide.com** (or whatever domain you've registered).

It is a single static HTML page with no build step, no JavaScript framework, and no dependencies. You can edit `index.html` in any text editor (TextEdit, Notepad, VS Code, etc.) and the change will deploy automatically once committed.

---

## What's here

- **`index.html`** — the entire website. All content, structure, and styling live in this one file. Mobile responsive. Fast-loading.
- **`README.md`** — this file.
- **`CNAME`** — placeholder for the custom domain. Once you've registered your domain, replace the contents of this file with your bare domain (e.g., `thecaregiverssurvivalguide.com`). This is what tells GitHub Pages to serve the site under your custom URL.
- **`favicon.ico`** *(not yet added)* — place a 32×32 or 48×48 favicon here when you have one. It's the little icon that shows up in the browser tab.

---

## To edit the site

1. Open `index.html` in a text editor.
2. Make your changes.
3. Save the file.
4. Commit and push to GitHub (or, if you used the web upload flow, re-upload the file).
5. The site updates within ~1 minute.

The HTML is organized into clear sections — Hero, What I Made This For, Why This and Why Now, What's Actually Inside, The Community, About, and the CTA (email capture). Each section is wrapped in a `<section>` tag and you can find them by searching for the section names in the comments.

---

## Email capture form — where to connect your provider

Search `index.html` for `EMAIL CAPTURE FORM — REPLACE THIS`. There's a large comment block right above the `<form>` element explaining how to swap in your email service's embed code. The setup guide walks you through this.

The default form has an `action="https://example.com/replace-this"` placeholder that will fail until you replace it. **Until you connect a real email service, the form will not work.**

---

## Lead-magnet delivery (Root-Cause Investigation Checklist)

The PDF version of the Root-Cause Investigation Checklist should be uploaded to your email service as the welcome-email attachment, NOT hosted publicly on this site. That way the checklist serves as the conversion offer — the visitor enters their email, and the service delivers the file.

If you want a public mirror as a fallback, you can also drop the PDF into this repo (e.g., `/checklist.pdf`) and link to it directly, but the email-capture flow is the recommended primary route.

---

## What's NOT in v1 (intentionally)

- No blog, no podcast player, no community surface, no app download. The homepage references those pillars but links them as "coming online in stages" — the email capture is the only conversion path.
- No JavaScript. The site works without it.
- No tracking/analytics. Once you're ready, add Plausible (privacy-friendly) or Google Analytics 4 via a small script tag — the setup guide explains how.
- No login, no membership wall, no payment flow. Those come once the community and paid tier are ready to launch.

---

## Future versions

When the time comes, v2 will likely add:
- A real blog section with individual post pages
- A dedicated About page
- A pricing/membership page once the Inner Circle is ready to open
- An app waitlist landing page
- An audio/video embed page for the podcast

That work can stay on the same GitHub repo and the same domain.

---

*Built May 2026 with care, by Natasha Shevelyov, with help from Claude.*
