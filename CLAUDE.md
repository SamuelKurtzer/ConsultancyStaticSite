# ConsultancyStaticSite

Single-page static site for samuelkurtzer.com, hosted on GitHub Pages from `main`.
All markup and CSS live in `index.html`; there is no build step.

## Checking visual changes

After any change to `index.html` or styles, check it in a real browser with the
Playwright MCP tools before saying the work is done:

1. Serve the site locally: `python3 -m http.server 8000` (run in the background),
   then open `http://localhost:8000/`.
2. Screenshot the full page at 375px (phone), 768px (tablet) and 1280px (desktop) wide.
3. Look for wrapped or squashed buttons, text running off the side, sideways
   scrolling and overlapping elements, and fix anything broken.
4. Stop the local server when finished.
