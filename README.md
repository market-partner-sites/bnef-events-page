# BNEF Events Page — Design Concept

A static, self-contained HTML mockup of a redesigned events landing page for [about.bnef.com](https://about.bnef.com/), built for internal review as part of the BNEF Summit Site Redesign work.

**This is a design concept, not the live BNEF site.** It reuses the real site's navigation structure and footer links (pointing back to the real about.bnef.com pages), but the "Events" nav item has been changed to a plain link (no dropdown), and the main content area shows a new card-based events listing with working Region and Event Type filters.

Event cards for the 9 confirmed upcoming BNEF Summits/Forums link out to their real registration pages on about.bnef.com. The 6 cards under "Other Energy Events" are clearly marked **Sample** — illustrative placeholders added to preview that filter category, not confirmed listings.

## Viewing it

Open `index.html` directly in a browser, or, if GitHub Pages is enabled for this repo (Settings → Pages → Deploy from branch → `main` / root), view it at:

```
https://<your-github-username>.github.io/<repo-name>/
```

## Notes

- Typeface is set to `Avenir Next` / `Avenir` (Bloomberg's brand font), falling back to Poppins/Inter via Google Fonts for viewers who don't have Avenir installed locally (e.g. non-Mac machines).
- No build step — it's a single plain HTML file with inline CSS and vanilla JS, so it works as-is on GitHub Pages, Netlify, or any static host.
