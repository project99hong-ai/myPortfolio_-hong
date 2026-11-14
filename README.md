# sohee — my work

An original, airy portfolio inspired by the whitespace, folder navigation, and categorized work grid in the supplied reference. No reference artwork, photographs, source code, or fonts are copied. All illustrations are local CSS or original inline SVG, and fonts are system fonts.

## Preview

Install [Node.js LTS](https://nodejs.org/) if needed. From this folder:

```powershell
node server.mjs
```

Open **http://127.0.0.1:8124**. Stop with Ctrl+C. There is no install command, package dependency, or build step. Use a current Chrome, Edge, Firefox, or Safari.

## Personalize

- [site/content.js](site/content.js): name, intro, contact links, cards, and the writing outlines shown in each card's dialog.
- [site/index.html](site/index.html): section headings, navigation, footer, and page metadata.
- [site/style.css](site/style.css): colors, layout, responsive breakpoints, and illustrations.
- [site/app.js](site/app.js): filters, folder navigation, dialog behavior, and rendering.

The only named employers are **McKinsey & Company — Business Analyst** and **Google**. Google's role, all dates, and all achievements are intentionally left for you to fill in. Project and leadership cards are explicit writing outlines, not claims about completed work. `example: false` hides an outline label; it does not replace the text for you.

All six cards open. Experience, projects, and leadership filters and folder buttons show the matching work and update the heading from “my work!” to the selected category. “Say hello” links directly to the contact footer; there is no About section. Dialogs support Escape, backdrop dismissal, keyboard focus containment, and return focus to their card. Reduced-motion preferences are respected.

Keep `email`, `linkedin`, `resume`, and each card's `href` empty until real destinations exist. LinkedIn and email icons remain visible as non-clickable placeholders until you fill in your details in `content.js`; no fake contact details are published. Empty résumé and card links are omitted. A local résumé can be placed at `site/resume.pdf` and linked as `"./resume.pdf"`.

## Publish

Deploy **only the `site` folder**, whose root contains `index.html`, to [Netlify Drop](https://app.netlify.com/drop). Do not upload the parent folder: it contains the guide and local preview server.

Before sharing on a résumé, replace or remove unfinished cards and the “product builder @Company” intro, add contact details, verify every factual claim and destination, update the HTML description/Open Graph metadata, and check the live site on mobile. There is no social-preview image until you add your own.

## Korean walkthrough

[GUIDE.ko.md](GUIDE.ko.md) is a separate, Notion-friendly tutorial with setup steps, screenshot-based prompts, editing guidance, tests, deployment, and a résumé checklist.
