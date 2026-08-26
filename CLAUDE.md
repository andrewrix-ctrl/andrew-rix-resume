# andrew-rix-resume

Single-page personal résumé site for Andrew Rix. `index.html` carries its own CSS and JS inline; images live in `assets/`. No build step.

GitHub Pages publishes `main` with its built-in Jekyll builder ("Deploy from a branch") — `.github/workflows/pages.yml` runs but its artifact is never deployed. `_config.yml` is therefore what keeps PRODUCT.md, DESIGN.md, CLAUDE.md and `.impeccable/` off the public site.

## Design context

Read **[PRODUCT.md](PRODUCT.md)** before changing anything visual or editorial, and **[DESIGN.md](DESIGN.md)** before touching CSS. The short version:

- **Register:** brand. How it looks and reads *is* the argument, not decoration around a CV.
- **Audience:** enterprise clients and executives, plus hiring managers and recruiters. It has to survive a thirty-second skim and a line-by-line read.
- **North star:** *The Value Stream* — the career drawn as a lit spine that shifts from teal (scaled Agile) to violet (AI) as it reaches the present.
- **Two accents, two meanings:** Signal Teal for live/position/credential, Transformation Violet for change/AI. No third accent.
- **Never:** a generic AI landing page, a LinkedIn profile clone, or a PDF résumé poured into a browser.
- **Accessibility:** WCAG 2.2 AA, non-negotiable — defence and government readers. Known gap: `--muted-2` in the light theme is under the small-text bar.

Both themes are first-class, and so is `@media print` — the page is also a CV.
