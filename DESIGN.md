---
name: Andrew Rix · AI-Native Practice Lead
description: A dark, instrumented résumé site where a career reads as a value stream.
colors:
  ink: "#080f1a"
  ink-2: "#0b1524"
  panel: "#101d30"
  panel-2: "#152640"
  line: "#213650"
  line-soft: "#1a2c44"
  signal-teal: "#63d0d8"
  signal-teal-deep: "#2e979f"
  transformation-violet: "#9b82ff"
  transformation-violet-deep: "#6d54e0"
  paper: "#eef5f9"
  paper-dim: "#c7d5e2"
  muted: "#96abc0"
  muted-2: "#6a8298"
  status-green: "#3ad39a"
typography:
  display:
    fontFamily: "Bricolage Grotesque, ui-sans-serif, system-ui, sans-serif"
    fontSize: "clamp(2.3rem, 5vw, 3.8rem)"
    fontWeight: 700
    lineHeight: 1.08
    letterSpacing: "-0.035em"
  headline:
    fontFamily: "Bricolage Grotesque, ui-sans-serif, system-ui, sans-serif"
    fontSize: "2rem"
    fontWeight: 700
    lineHeight: 1.15
    letterSpacing: "-0.025em"
  title:
    fontFamily: "Bricolage Grotesque, ui-sans-serif, system-ui, sans-serif"
    fontSize: "1.25rem"
    fontWeight: 600
    lineHeight: 1.3
    letterSpacing: "-0.015em"
  body:
    fontFamily: "IBM Plex Sans, ui-sans-serif, system-ui, -apple-system, sans-serif"
    fontSize: "1rem"
    fontWeight: 400
    lineHeight: 1.65
    letterSpacing: "normal"
  label:
    fontFamily: "Bricolage Grotesque, ui-sans-serif, system-ui, sans-serif"
    fontSize: "0.72rem"
    fontWeight: 600
    lineHeight: 1.2
    letterSpacing: "0.24em"
rounded:
  marker: "3px"
  xs: "9px"
  sm: "12px"
  md: "16px"
  lg: "22px"
  pill: "100px"
spacing:
  xs: "9px"
  sm: "14px"
  md: "22px"
  lg: "42px"
  xl: "78px"
components:
  button-primary:
    backgroundColor: "{colors.signal-teal}"
    textColor: "#06121a"
    typography: "{typography.title}"
    rounded: "{rounded.pill}"
    padding: "14px 28px"
  button-primary-hover:
    backgroundColor: "{colors.transformation-violet}"
    textColor: "#06121a"
    rounded: "{rounded.pill}"
    padding: "14px 28px"
  button-ghost:
    backgroundColor: "{colors.panel}"
    textColor: "{colors.paper}"
    rounded: "{rounded.pill}"
    padding: "14px 28px"
  button-ghost-hover:
    backgroundColor: "{colors.panel}"
    textColor: "{colors.signal-teal}"
    rounded: "{rounded.pill}"
    padding: "14px 28px"
  chip:
    backgroundColor: "{colors.panel}"
    textColor: "{colors.paper-dim}"
    rounded: "{rounded.pill}"
    padding: "10px 17px"
  chip-ai:
    backgroundColor: "{colors.panel}"
    textColor: "#cabfff"
    rounded: "{rounded.pill}"
    padding: "10px 17px"
  card:
    backgroundColor: "{colors.panel}"
    textColor: "{colors.muted}"
    rounded: "{rounded.md}"
    padding: "24px 26px"
  nav-link:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.muted}"
    rounded: "{rounded.xs}"
    padding: "9px 13px"
  nav-link-active:
    backgroundColor: "{colors.panel}"
    textColor: "{colors.signal-teal}"
    rounded: "{rounded.xs}"
    padding: "9px 13px"
  logo-plate:
    backgroundColor: "#ffffff"
    rounded: "{rounded.sm}"
    padding: "0 20px"
    height: "46px"
---

# Design System: Andrew Rix · AI-Native Practice Lead

## 1. Overview

**Creative North Star: "The Value Stream"**

The system takes its governing metaphor from the work it describes. A career in flow and transformation is drawn as a stream: a single lit spine runs down the experience section, teal shading into violet as the timeline moves from scaled-Agile work into AI, with each role a stop along it. Everything else in the system serves that spine. The near-black ground is not a mood choice, it is the condition that lets a signal read; the ambient wash and 64px grid behind it are the noise floor the signal sits above.

The register is assured, curious, ahead. Two readers use this page: an executive skimming for altitude and a hiring manager reading the record line by line. The system serves both by keeping one strong hierarchy — display type and accent colour for position, body type and generous measure for depth — and by never decorating a thing that is not carrying information. A status dot, a pulsing ring, a flowing line, a count-up: each of these is reporting something. Nothing here is ornament dressed as instrumentation.

What the system rejects is stated plainly in PRODUCT.md and holds here. It is not the generic AI landing page: no gradient-orb hero, no glass cards, no purple-on-black SaaS template. It is not a LinkedIn profile clone: no endorsement bars, no undifferentiated wall of roles. And it is not a PDF poured into a browser. If a section could be lifted onto any AI product's launch page without changing a word, it is wrong.

**Key Characteristics:**
- Near-black ground (`#080f1a`) with tonal panels stacked over it; no bright surface anywhere in the dark theme
- Two accents only, each with an assigned meaning: teal for signal and position, violet for change and AI
- One display family carrying every heading, label and number; one body family carrying prose
- Motion that reports state rather than announcing arrival
- A complete second theme, not an inverted afterthought: light mode redefines all fifteen tokens
- Print is a first-class target — the page is also a CV

## 2. Colors

A cold, instrumented palette: two lit accents against a graded near-black, with everything else neutral so the accents stay meaningful.

### Primary
- **Signal Teal** (`#63d0d8`): the live-signal colour. Andrew's role line, the active nav item and its glowing dot, the eyebrow rules, the emphasised phrase in the hero headline, card titles, organisation names, timeline stops, the focus ring, and text selection. Where teal appears, something is current, active or being pointed at.
- **Signal Teal Deep** (`#2e979f`): the hover border on chips, and the light-theme accent's darker partner. Never used for text on dark.

### Secondary
- **Transformation Violet** (`#9b82ff`): the change colour. AI-flagged skill chips, the later stops on the timeline, the credo quote mark, the second half of the progress bar and the primary button's gradient. Violet marks the shift into new territory; it never carries body text.
- **Transformation Violet Deep** (`#6d54e0`): the light theme's violet partner, used where the bright value would not hold contrast.

### Tertiary
- **Status Green** (`#3ad39a`): one job only — the availability dot on the portrait. It is the single colour outside the two-accent system, and it stays that way.

### Neutral
- **Ink** (`#080f1a`): the page ground, and the fill inside timeline stop rings.
- **Ink 2** (`#0b1524`): the lower stop of every panel gradient; the darker half of a card.
- **Panel** (`#101d30`) and **Panel 2** (`#152640`): the two raised surface tones. Cards, the proof strip, the credo block and the CTA are built from gradients between these and Ink 2.
- **Surface 2** (`#0b1524` dark / `#f5f9fc` light): the lower stop of every surface gradient. It exists because light-theme `--panel` and `--ink-2` are both white, so the subtle top-to-bottom fall on cards, chips, the proof strip and achievement boxes needs its own token to survive the theme switch.
- **Line** (`#213650`) and **Line Soft** (`#1a2c44`): the border and the divider. Line draws the edge of a surface; Line Soft draws separation inside one, and paints the ambient grid.
- **Paper** (`#eef5f9`): primary text and headings.
- **Paper Dim** (`#c7d5e2`): the lede, body prose in About and the timeline, chip labels.
- **Muted** (`#96abc0`): supporting copy inside cards, proof captions, table cells.
- **Muted 2** (`#6a8298`): the small uppercase labels — dates, captions, table headers, footer.

### Named Rules

**The Two-Signal Rule.** Teal and violet are the entire accent vocabulary and they are not interchangeable. Teal means *this is live, this is where you are, this is the credential*. Violet means *this is the change, this is the AI end of the story*. A third accent is prohibited; Status Green is the one exception and it owns exactly one dot.

**The No-Bright-Surface Rule.** In the dark theme, no surface is lighter than `#152640`. Depth is achieved by stacking tones toward the panel end, never by introducing a light card. A white or near-white block on the dark theme is forbidden — with one deliberate exception: client logo plates are white, because that is what a logo needs to be legible, and their whiteness is what makes the client strip read as evidence rather than decoration.

**The Parity Rule.** Light mode is a full redefinition of all fifteen tokens on `:root[data-theme="light"]`, not a filter. Any new token added to the dark theme must be given a light value in the same commit, and that value must be measured against the light ground rather than translated by eye — three of the original fifteen were translated without re-measuring and landed under the AA bar.

## 3. Typography

**Display Font:** Bricolage Grotesque (variable, `opsz 12..96`, weight axis 400–700), falling back to `ui-sans-serif, system-ui, sans-serif`
**Body Font:** IBM Plex Sans (variable, weight axis 400–600), falling back to `ui-sans-serif, system-ui, -apple-system, sans-serif`

Both are self-hosted from `assets/fonts/` as `latin` and `latin-ext` variable subsets, declared inline with `font-display: swap` and preloaded. Nothing is fetched from a third-party origin — partly for the round trips, partly because government and defence readers shouldn't have to make a request to Google to read a CV. Both families are SIL OFL 1.1; see `assets/fonts/NOTICE.md`.

**Character:** Bricolage is a wide, slightly irregular grotesque with real optical-size variation — it has personality at display sizes without tipping into novelty, which is what lets a headline about organisational change avoid reading as consultancy boilerplate. Plex Sans underneath it is flatly neutral and workmanlike, and that contrast is the point: the voice is expressive in the headline and plain in the record. The two are far enough apart on the humanist/neo-grotesque axis to read as a deliberate pair rather than two similar sans-serifs.

### Hierarchy

Eight steps, every one a token (`--fs-micro` … `--fs-hero`). No literal `font-size` value appears anywhere in the stylesheet except the decorative quote glyph. The scale runs tight through the label range and opens up into display — a CV needs several distinguishable small sizes, and the page collapsed to eight steps from twenty-three ad-hoc values without a visible change, which is the proof the extra values were never carrying information.

- **`--fs-hero`** (700, `clamp(2.3rem, 5vw, 3.8rem)`, line-height 1.08, tracking -0.035em): hero headline only. Capped at `19ch` so it always breaks into three lines.
- **`--fs-display`** (700, 2rem, tracking -0.025em): the CTA heading.
- **`--fs-head`** (1.75rem): the sidebar name, and the proof-strip values.
- **`--fs-title`** (600, 1.25rem, tracking -0.015em): timeline role headings.
- **`--fs-lead`** (1.1rem): the hero lede at `60ch`, card titles in Signal Teal, the credo pull-quote.
- **`--fs-body`** (400, 1rem, line-height 1.65): prose.
- **`--fs-sm`** (0.92rem): the dense register — card bodies, timeline paragraphs (capped `70ch`), table cells, buttons.
- **`--fs-meta`** (0.85rem): secondary meta — credential issuers, contact rows, chips, captions.
- **`--fs-micro`** (600, 0.72rem, uppercase, tracking 0.13em–0.24em): section eyebrows, the hero kicker, dates and table headers — always the display family, never the body family.

### Named Rules

**The Display-For-Data Rule.** Every number, date, credential and label is set in Bricolage, not Plex. The body font handles sentences; the display font handles anything that is a fact. This is why the proof strip, the timeline dates and the table year column all share a texture that prose does not.

**The One-Value Rule.** A size that isn't on the scale doesn't go in. If a new element seems to need something between two steps, it belongs on one of them — the twenty-three values this replaced differed by as little as 2%, which no reader has ever seen. The same rule governs radius: five steps (`--r-marker` 3px, `--r-xs` 9px, `--r-sm` 12px, `--r-md` 16px, `--r-lg` 22px) plus `--r-pill`, and circles, which are a shape rather than a step.

**The Measure Rule.** No line of prose exceeds 70ch and the hero lede stops at 60ch. Headlines cap by character count (`max-width: 19ch`) rather than by percentage, so the break points survive every viewport.

## 4. Elevation

Flat at rest, lit on contact. Surfaces are distinguished by tone, not by shadow: a card is a gradient from Panel to Ink 2 with a one-pixel Line border, and at rest it casts almost nothing. Depth is a response to interaction. On hover a card lifts 4px, drops its border to transparent, and a masked gradient hairline — teal fading to nothing across 40% of the edge — fades in around it. The lift and the hairline arrive together, so the element appears to catch light rather than to rise.

The one persistent shadow is ambient and nearly invisible by design: it exists to keep large panels from floating flat against the ground, not to signal hierarchy.

### Shadow Vocabulary
- **Card ambient** (`0 1px 0 rgba(255,255,255,.03) inset, 0 18px 40px -24px rgba(0,0,0,.7)`): the resting state of every large surface — proof strip, credo, CTA. The inset top highlight is what stops the panel gradient from looking printed.
- **Card lifted** (`0 24px 46px -26px rgba(0,0,0,.8)`): hover only.
- **Accent glow** (`0 0 10px var(--glow-teal)` / `var(--glow-violet)`): reserved for lit points — the active nav dot, the kicker spark, timeline stop centres, the progress bar.
- **Plate shadow** (`0 8px 20px -12px rgba(0,0,0,.6)`): white logo plates, which need to sit on the dark ground without a halo.

### Named Rules

**The Sticky-Offset Rule.** Anything that sticks to the top of the viewport must be added to `--sticky-offset`, and every anchor target scrolls by `calc(var(--sticky-offset) + 16px)`. It is 0 on desktop, where the sidebar sits beside the content rather than over it, and the mobile header's measured height below 900px. Skip this and in-page navigation lands the reader behind the header — the heading they asked for is the one thing they can't see.

**The Contact Rule.** Shadow is a state, not a style. If an element is not hovered, focused or emitting a signal, it has no shadow beyond the ambient card value. Adding a resting drop shadow to make something "pop" is forbidden; raise its tone instead.

## 5. Components

Precise and quietly responsive. Every interactive element moves 2–4px and shifts colour; nothing bounces, nothing scales dramatically, and every transition uses `cubic-bezier(.22,.61,.36,1)` at 200–280ms.

### Buttons
- **Shape:** fully rounded pill (`100px`), padding `14px 28px`, display font at 600/0.95rem, optional 17px inline SVG icon.
- **Primary:** a 120° teal-to-violet gradient with a teal glow beneath (`0 12px 30px -12px`). The one place the two accents are allowed to blend. The label is near-black (`#06121a`) on the dark theme and white on the light one — the light accents are dark enough that near-black drops to 2.86:1 against the violet end.
- **Ghost:** translucent panel fill with a Line border and Paper text.
- **Hover / Focus:** both lift 3px. Primary swaps its glow from teal to violet; ghost shifts border and text to Signal Teal. Focus is the global ring: `2px solid var(--teal)`, offset 3px. The ring follows whatever radius the element already has — it must never set a radius of its own, or focusing an element changes its shape.

### Chips
- **Style:** pill with a Panel-to-Ink-2 gradient, Line border, Paper Dim label in the display font at 0.88rem.
- **State:** hover lifts 2px, border goes to Signal Teal Deep, text to Paper. Chips are non-interactive by design (`cursor: default`) — they are labels, not filters.
- **AI variant:** violet-tinted border, `#cabfff` text, and a leading 7px violet dot with a glow. This is how the skills section shows which capabilities are the new ones.

### Cards
- **Corner Style:** `16px`
- **Background:** vertical gradient, Panel to Ink 2
- **Shadow Strategy:** none at rest; see Elevation
- **Border:** 1px Line, replaced on hover by the masked gradient hairline
- **Internal Padding:** `24px 26px`
- Card titles carry a 9px teal-to-violet rounded square as a leading marker instead of an icon.

### Navigation
- **Style:** vertical list in a sticky full-height sidebar (312px), each item a 9px-radius row with a 5px leading dot.
- **States:** default Muted text and a Muted 2 dot; hover raises text to Paper over a Panel fill; active turns the text teal, fills with a left-to-right teal fade, and scales the dot 1.4× with a teal glow. Active state is driven by scroll position.
- **Mobile (≤900px):** the sidebar is replaced by a sticky blurred top bar with a horizontally scrolling nav strip, portrait thumbnail and name.

### The Value Stream (signature component)
The experience section is the system's centrepiece and its namesake. A 2px vertical spine runs the full section, filled with a teal-violet-teal gradient at 200% height, animated on a 6s linear loop so the fill appears to flow upward. Each role is a stop: a 20px ring in Ink with a teal border and a small glowing centre dot, offset into the spine. Later, AI-era roles take the `.violet` modifier and swap both to violet, so the stream visibly changes colour as it approaches the present. Hovering a stop scales the ring 1.15× and blooms a 6px teal halo. Achievements inside a role sit in a nested 12px panel with a small uppercase teal label and a gradient square marker.

### Proof Strip
Four cells in a 1px-gap grid whose gap colour is Line, so the borders are the grid itself. Each cell is a Panel-to-Ink-2 gradient with a display-font value and a Muted caption. The `750+` figure counts up once on first view; the highlighted first cell renders its value in teal. Collapses to 2×2 below 900px.

## 6. Do's and Don'ts

### Do:
- **Do** assign meaning before colour. Teal for live/position/credential, violet for change/AI. If a new element does not fit either meaning, it is neutral.
- **Do** set every number, date and label in Bricolage Grotesque and every sentence in IBM Plex Sans.
- **Do** keep prose to 70ch and the hero lede to 60ch.
- **Do** give each new token a light-theme value in the same change. The light theme is a full parity theme.
- **Do** verify contrast at 4.5:1 for anything under 18px, in both themes. Government and defence readers are in the audience and, per PRODUCT.md, *"accessibility is itself part of the credibility argument."*
- **Do** keep motion reporting state — a dot that pulses because he is available, a line that flows because it is a stream, a number that counts because it is a total.
- **Do** give every `<img>` explicit `width` and `height` attributes matching the file's intrinsic size. They are what reserve the space and stop the layout shifting as images arrive. **And pair them with `width: auto` in any CSS rule that sets only `height`** — otherwise the attribute supplies the used width and the image renders squashed. This is exactly how the credential badges broke.
- **Do** add any new top-sticky element's height to `--sticky-offset`. Anchors, and the skip link, depend on it.
- **Do** check the print stylesheet after any structural change. The page is also a CV, and `@media print` already strips the chrome and inverts to black-on-white.
- **Do** honour `prefers-reduced-motion`: the existing rule kills all animation, freezes reveals visible, and cancels every hover transform. Any new animation joins it.

### Don't:
- **Don't** build anything that reads as a **generic AI landing page** — gradient orb heroes, glass cards, "supercharge your workflow" copy, purple-on-black SaaS template. The page argues for AI leadership; looking like every AI product launch defeats the argument.
- **Don't** let it drift toward a **LinkedIn profile clone**: no endorsement bars, no skill-strength meters, no wall of undifferentiated roles.
- **Don't** let it flatten into a **plain PDF resume on the web**. The print stylesheet is where the document lives; the screen is where the argument lives.
- **Don't** introduce a third accent colour. Two signals, plus one green dot.
- **Don't** place a light or white surface on the dark theme. White is reserved for client logo plates, where it is doing legibility work.
- **Don't** add a resting drop shadow to lift an element. Raise its tone toward Panel 2 instead.
- **Don't** gate content visibility on the reveal class. The hidden state lives on `.js .reveal`, and `.js` is set on `<html>` before first paint, so a script-less or headless render never sees `opacity: 0` at all. Three guards back it up: reduced motion, a missing observer, and `document.visibilityState !== 'visible'` all reveal everything immediately, and a 1200ms watchdog reveals everything if the observer exists but never calls back. All four must survive.
- **Don't** re-lighten `--teal` (`#00717a`) or `--muted-2` (`#56687c`) in the light theme. Both sit just above 5:1 on the page ground by measurement; the earlier values were under the AA bar.
- **Don't** apply an eyebrow to a new section by reflex. Six already carry one, which is the system's cadence — a seventh should earn it or go without.
