---
name: Outdoor Design Build
description: A cedar deck at the edge of winter; maple leaves land on the boards and the visitor sweeps them off.
colors:
  spruce: "#1b3a2f"
  spruce-2: "#234a3c"
  spruce-ink: "#0f2219"
  footer: "#15302a"
  siding: "#e8ece7"
  siding-2: "#dde3dd"
  cedar: "#c27a3f"
  cedar-deep: "#9a5528"
  cedar-hi: "#e8a167"
  cedar-hover: "#d38a4d"
  on-cedar: "#1d1109"
  brand-sub: "#e3a46d"
  maple: "#efb43c"
  focus-light: "#946008"
  rail: "#262b2e"
  rule: "#c5cec7"
  control-line: "#84928a"
  on-dark: "#f3f1ea"
  on-dark-soft: "#c9d6cd"
  on-light-soft: "#46524b"
typography:
  display:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(2.75rem, 12.4vw, 6rem)"
    fontWeight: 900
    lineHeight: 0.98
    letterSpacing: "-0.025em"
  headline:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(2rem, 8vw, 3.6rem)"
    fontWeight: 900
    lineHeight: 0.98
    letterSpacing: "-0.01em"
  title:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(1.25rem, 5.6vw, 1.6rem)"
    fontWeight: 900
    lineHeight: 0.98
    letterSpacing: "-0.005em"
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.55
  label:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Roboto, Helvetica Neue, Arial, sans-serif"
    fontSize: "17px"
    fontWeight: 800
    lineHeight: 1
rounded:
  sm: "8px"
  md: "10px"
  photo: "14px"
  pill: "999px"
spacing:
  gutter-phone: "20px"
  gutter-desk: "40px"
  section-phone: "96px"
  section-desk: "130px"
components:
  button-fill:
    backgroundColor: "{colors.cedar}"
    textColor: "{colors.on-cedar}"
    rounded: "{rounded.md}"
    padding: "0 24px"
    height: "56px"
  button-fill-hover:
    backgroundColor: "{colors.cedar-hover}"
  button-line:
    backgroundColor: "rgba(27,58,47,.55)"
    textColor: "{colors.on-dark}"
    rounded: "{rounded.md}"
    padding: "0 24px"
    height: "56px"
  button-line-hover:
    textColor: "{colors.maple}"
  service-row-arrow:
    backgroundColor: "{colors.siding-2}"
    textColor: "{colors.rail}"
    rounded: "50%"
    size: "44px"
  service-row-arrow-hover:
    backgroundColor: "{colors.cedar}"
    textColor: "{colors.on-cedar}"
  chip:
    backgroundColor: "#ffffff"
    textColor: "{colors.rail}"
    rounded: "{rounded.pill}"
    padding: "0 18px"
    height: "48px"
  chip-checked:
    backgroundColor: "{colors.spruce}"
    textColor: "{colors.on-dark}"
  input:
    backgroundColor: "#ffffff"
    textColor: "{colors.rail}"
    rounded: "{rounded.md}"
    padding: "14px"
    height: "54px"
  proof-bar:
    backgroundColor: "{colors.spruce}"
    textColor: "{colors.on-dark}"
    rounded: "{rounded.md}"
    padding: "12px 18px"
    height: "64px"
  proof-bar-hover:
    backgroundColor: "{colors.spruce-2}"
---

# Design System: Outdoor Design Build

## Overview

**Creative North Star: "The Deck Before the Snow"**

The page is the client's own cedar deck at dusk in late October. Spruce green is the yard and the sky; fresh-stained cedar boards, drawn live on canvas with real grain, screws and butt joints, are the structural material that ties every section together; pale siding grey carries the reading sections. Maple and elm leaves blow in on a gusty breeze and settle on the boards, and a finger or mouse sweeps them off like a leaf blower. That living deck is the signature; everything else stays plain so it can carry the page.

Density is low and phone-first: one column, big uppercase heads, 56px buttons, generous section padding. Type is a single heavy system sans. There is no card grid, no stock photo hero, no testimonial strip. Proof is the client's one real deck photo and their Facebook following.

**Key Characteristics:**
- Dark spruce ground alternating with light siding sections, joined by cedar plank seams.
- Cedar is the action color; maple gold appears only as focus/hover feedback.
- One family, weight 900, uppercase for every heading.
- Live canvas leaves over cached board drawings in hero, seams, photo ledge and close.
- Flat UI; the only real shadow sits under the photograph.

## Colors

A two-ground palette (spruce dark, siding light) with one material accent (cedar) and one feedback accent (maple).

### Primary
- **Fresh-Stained Cedar** (cedar): fill of the primary button, the service-row arrow on hover, link underlines in the footer, scrollbar thumb, the base stain of every canvas board. `cedar-hover` is its hover; `cedar-deep` is the darker stain for any cedar line work on light.
- **Cedar Light** (cedar-hi): cedar lifted for large text on spruce: the emphasized words of the hero headline and the step numerals.

### Secondary
- **Maple Gold** (maple): focus rings and hover text on dark grounds only, plus text selection. Never a fill for content.
- **Deep Maple** (focus-light): the same role on siding sections, deepened to hold contrast on light: focus outlines, chip/input hover and focus borders, the 3px focus halo on inputs.

### Neutral
- **Evergreen Dusk** (spruce): page ground, dark sections, checked chips, the proof bar. `spruce-2` is its hover/raised step, `spruce-ink` is text on maple, `footer` is the deepest band.
- **Pale Siding** (siding / siding-2): light reading sections; `siding-2` is the resting arrow circle and inset fills.
- **Black Baluster** (rail): body ink on siding.
- **Soft Light Ink** (on-dark, on-dark-soft): primary and secondary text on spruce.
- **Muted Ink** (on-light-soft): secondary text on siding (optional tags, form notes).
- **Rule Grey** (rule): hairline dividers between service rows. **Control Line** (control-line): 2px borders of chips and inputs (3:1 on white).

### Named Rules
**The Maple Means Focus Rule.** Maple gold (and Deep Maple on light) signals "you are here / you can press this". It is never decoration, never a heading color, never a resting fill.

**The Two Focus Colors Rule.** Default `:focus-visible` is a 3px maple outline at 3px offset; inside any `.light` section it switches to focus-light. Any new light surface must carry the `light` class so focus stays visible.

## Typography

**Display Font:** system UI sans (`-apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif`)
**Body Font:** same stack

**Character:** One family doing everything, carried by weight: 900 uppercase for heads like painted job-site lettering, 800 for buttons and labels, 400 body. Fast to load inside Facebook's in-app browser.

### Hierarchy
- **Display** (900, clamp(2.75rem, 12.4vw, 6rem), 0.98, -0.025em, uppercase): hero headline only; max 760px wide; soft dark text-shadow for legibility over leaves. Closing headline uses clamp(2.2rem, 10vw, 4.6rem).
- **Headline** (900, clamp(2rem, 8vw, 3.6rem), 0.98, uppercase, balanced wrap): section titles.
- **Title** (900, clamp(1.25rem, 5.6vw, 1.6rem), uppercase): service row labels; step titles at 1.25rem.
- **Body** (400, 17px phone / 18px at 900px+, 1.55): paragraphs; promise lines capped near 32-34ch.
- **Label** (800, 17px): buttons, form legends and labels, phone number (tabular numerals). Small notes are 15px.

### Named Rules
**The Plain Numeral Rule.** Steps are numbered with a bare cedar-hi numeral (900, 52px) from a CSS counter. No circles, badges or "Step 01" labels.

## Layout

Single centered container (max 1180px; 20px gutters, 40px at 900px+). Sections pad 96px/88px on phones and 130px/120px at 900px+. Breakpoints: 400px (buttons stop wrapping), 640px (hero buttons go side by side), 900px (two-column services/work grid with 72px gap, three-column steps, larger header), 1024px (form goes two columns; chip groups, notes and submit span full width). The hero is at least 640px and up to 100svh (cap 940px); copy sits top-left, the deck fills the lower part from just below the buttons.

The header is absolute over the hero, not sticky. Sections alternate dark / light / dark / light / dark close, and every boundary is a cedar plank seam overlapping both sections by half its height (96px tall, 120px at 900px+).

## Elevation & Depth

Flat UI. Depth comes from the canvas material (board gradients, dusk light, contact shadow where the deck meets the yard, small drop shadows under resting leaves) and from radial gradients on the hero and close grounds. The only box shadow is under the work photo, which sits on a cedar ledge like an object.

### Shadow Vocabulary
- **Photo lift** (`box-shadow: 0 22px 44px -18px rgba(30,40,34,.55), 0 4px 12px rgba(30,40,34,.18)`): the work photograph only.
- **Input focus halo** (`box-shadow: 0 0 0 3px rgba(148,96,8,.25)`): text fields on focus, with focus-light border.
- **Headline legibility shadow** (`text-shadow: 0 2px 24px rgba(15,34,25,.75)`): headlines and promise text sitting over leaf fields.

### Named Rules
**The Only the Photo Floats Rule.** No card or button shadows. If something needs separation, use a ground change or a 1px rule.

## Shapes

Gently rounded rectangles (10px) for buttons, inputs, proof bar and result panel; 8px for small secondary buttons and inset code blocks; 14px for the photo; full pills for chips; perfect circles for the arrow and Facebook badge. Rows are open, divided by hairline rules, never boxed. Borders are 2px on interactive controls, 1px on dividers.

## Components

### Header
Absolute over the hero. Left: SVG plank mark (three cedar boards with gaps, screws and grain) plus "OUTDOOR DESIGN BUILD" (900, uppercase) with "Windsor, Ontario" beneath in brand-sub (hidden under 430px). Right: the phone number as a tel link (800, tabular numerals), maple on hover. No nav menu.

### Buttons
- **Shape:** 10px radius, min-height 56px, 2px cedar border, 800 17px label, optional 20px leading icon.
- **Fill (primary):** cedar fill, on-cedar text; hover to cedar-hover. Active nudges down 1px (off for reduced motion).
- **Line (secondary, dark grounds):** translucent spruce fill, on-dark text, cedar border; hover turns border and text maple.
- **Hero pair:** fill "Get a free estimate" + line "Message us on Facebook", stacked on phones, side by side at 640px+, max 580px together.
- **Small secondary** (Copy message): 8px radius, 2px control-line border, 44px tall; focus-light border on hover/focus.

### Service Rows
A ruled list of uppercase title links, each 68px tall with a 44px arrow circle at the right. On hover/focus only the arrow circle changes (siding-2 to cedar fill); the row gets no background, outline or shadow, and the focus ring draws around the arrow. Clicking jumps to the form and pre-ticks the matching chip with a brief Deep Maple pulse.

### Proof Bar (Facebook)
Spruce bar under the photo: Facebook-blue round badge, an 800 line with a 500 subline in on-dark-soft, trailing arrow that nudges right and turns maple on hover; bar shifts to spruce-2.

### Steps
Three items, numeral column 52px + text; one column on phones, three at 900px+. Sit on spruce.

### Chips
Pill, 48px tall, white with 2px control-line border, 700 weight. Hover border focus-light; checked becomes spruce fill with on-dark text. Hidden native checkbox/radio keeps keyboard semantics; focus ring is a 3px focus-light outline on the pill.

### Inputs / Fields
- **Style:** white, 2px control-line border, 10px radius, 16px text (prevents iOS zoom), 54px min height; textarea 110px, vertical resize.
- **Focus:** border focus-light plus the 3px focus halo; no outline.
- **Error:** border #b3261e, message 700 15px in #9b2018 below, announced politely.
- **Submit:** full-width fill button (max 420px); hover/focus adds a 3px focus-light outline.

### Close
Spruce section with radial glow, closing headline, one line, a single line button to Messenger, and its own leaf field with a deck along the bottom 210px.

### Footer
Deepest green band, 15px on-dark-soft: name (900, uppercase), phone, Facebook, town. Links are underlined in cedar, maple on hover, 44px tap height.

### Leaf Field (Signature Component)
One engine (`Field`) runs every instance; edit tunables only in the `TUNE` object at the top of the script.
- **Two canvases per field.** `drawDeck` paints boards once per size onto an under-canvas inserted beneath the leaf canvas (six-tone cedar stain with board-to-board shift, wavy grain, cathedral arches, knots, screw pairs over joists, staggered butt joints, dusk light and a contact shadow). Each frame clears and redraws only the leaves on the top canvas. Resize redraws only when width/height actually change, so mobile address-bar resizes keep the visitor's sweep.
- **Instances.** Hero (deck starts below the copy, 34/84 leaves phone/desk); close (deck below the button, 26/60); plank seams between sections and the photo ledge (a narrow band of 14-18px boards with a dark gap line, 7/14 leaves, leaves 0.82 size). Leaves are 17px phone / 20px desk.
- **Leaves.** Maple and elm sprites prerendered front and back in seven late-October reds, rusts and browns; they flip, sway, settle with a slide and ease flat, cast a small shadow when resting, and gusts occasionally lift them.
- **Text avoidance.** Flying leaves fade near the field's top edge and fade out over the hero and close copy blocks (headline, promise, buttons) so no leaf crosses text.
- **Pointer blower.** Mouse or finger within 90/130px pushes leaves away with a share of pointer velocity. The hero deck area takes `touch-action:none` so drags work in any direction there; the text area and seams still scroll. Swept leaves return after 4-10s.
- **Reduced motion.** Every leaf is placed resting on the boards and one still frame is drawn; no loop, no pointer.
- **Performance.** DPR capped at 1.5; one shared rAF loop that sleeps when no field is intersecting the viewport or the tab is hidden.

## Do's and Don'ts

### Do:
- **Do** join every dark/light section boundary with a cedar plank seam field.
- **Do** keep cedar as the only action fill and maple (focus-light on siding) as the only hover/focus accent.
- **Do** set every heading 900 uppercase in the system stack, balanced wrap.
- **Do** keep tap targets at least 44px (buttons 56px, chips 48px, inputs 54px).
- **Do** add any new text block over a leaf field to that field's avoid list and give it the legibility text-shadow.
- **Do** keep the phone number top-right on the first screen and show it at most once per screen.
- **Do** make everything that looks pressable actually pressable (rows, chips, arrow circles, proof bar all link or toggle).

### Don't:
- **Don't** make the header sticky or add a sticky/floating call bar (client house rule).
- **Don't** repeat the phone number elsewhere on the first screen, or place it anywhere but top-right there.
- **Don't** add email links (none exists; if the owner supplies one, it goes in the footer only).
- **Don't** style non-interactive things to look clickable: no arrow circles, pills, underlines or button shapes on static content.
- **Don't** change the service row background or draw a box on hover; only the arrow circle responds.
- **Don't** add shadows to cards or buttons, or wrap rows and steps in cards.
- **Don't** add eyebrows, kickers or badges above headings, or step-number chips.
- **Don't** redraw the boards every frame or run the loop off-screen.
