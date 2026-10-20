---
name: Outdoor Design Build
description: Calm paper and slate-navy bands, their own cedar deck under a navy overlay, fresh cedar as the one warm fill.
colors:
  cedar: "#dc955a"
  cedar-2: "#e8ab78"
  cedar-ink: "#8f4a17"
  navy: "#223d5e"
  deep: "#14243b"
  paper: "#f4f6fb"
  card: "#ffffff"
  field: "#e6ecf5"
  ink: "#14243b"
  body: "#2a3748"
  soft: "#4a5668"
  on-dark: "#f4f6fb"
  on-dark-soft: "#c8d4e4"
  focus: "#223d5e"
  error: "#b3261e"
  overlay-slate: "#182b44"
  photo-shade: "#0e1a2c"
typography:
  display:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(42px, 12vw, 84px)"
    fontWeight: 400
    lineHeight: 1.02
    letterSpacing: "-0.005em"
  headline:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(30px, 7.6vw, 48px)"
    fontWeight: 400
    lineHeight: 1.08
    letterSpacing: "-0.005em"
  phone-display:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(30px, 9vw, 52px)"
    fontWeight: 400
    lineHeight: 1
  title:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "clamp(21px, 5.6vw, 24px)"
    fontWeight: 400
    lineHeight: 1.2
  wordmark:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "22px"
    fontWeight: 400
    lineHeight: 1
    letterSpacing: "0.02em"
  wordmark-wide:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "25px"
    fontWeight: 400
    lineHeight: 1
    letterSpacing: "0.02em"
  button:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "18px"
    fontWeight: 400
    lineHeight: 1
    letterSpacing: "0.015em"
  field-label:
    fontFamily: "Cal Sans, Avenir Next, Segoe UI, system-ui, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.2
    letterSpacing: "0.015em"
  promise:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(17px, 4.7vw, 20px)"
    fontWeight: 400
    lineHeight: 1.5
  lede:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "clamp(17px, 4.6vw, 19px)"
    fontWeight: 400
    lineHeight: 1.7
  body:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "16px"
    fontWeight: 400
    lineHeight: 1.7
  caption:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "15px"
    fontWeight: 400
    lineHeight: 1.5
  small:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "14px"
    fontWeight: 500
    lineHeight: 1
    letterSpacing: "0.02em"
  wordmark-sub:
    fontFamily: "-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial, sans-serif"
    fontSize: "12px"
    fontWeight: 600
    lineHeight: 1
    letterSpacing: "0.08em"
rounded:
  card: "24px"
  field: "10px"
  pill: "999px"
  focus: "6px"
  circle: "50%"
spacing:
  gutter: "20px"
  gutter-wide: "40px"
  section: "64px"
  section-wide: "96px"
  card-pad: "clamp(20px, 5vw, 32px)"
  stack: "20px"
  block: "28px"
  column-gap: "64px"
components:
  button-primary:
    backgroundColor: "{colors.cedar}"
    textColor: "{colors.ink}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  button-primary-hover:
    backgroundColor: "{colors.cedar-2}"
    textColor: "{colors.ink}"
  button-ghost:
    backgroundColor: "transparent"
    textColor: "{colors.on-dark}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0 26px"
    height: "56px"
  button-link:
    backgroundColor: "transparent"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    padding: "0 18px"
    height: "44px"
  input-field:
    backgroundColor: "{colors.field}"
    textColor: "{colors.ink}"
    typography: "{typography.body}"
    rounded: "{rounded.field}"
    padding: "13px 14px"
    height: "52px"
  chip:
    backgroundColor: "{colors.field}"
    textColor: "{colors.ink}"
    rounded: "{rounded.pill}"
    padding: "0 18px"
    height: "48px"
  chip-selected:
    backgroundColor: "{colors.ink}"
    textColor: "{colors.card}"
  form-card:
    backgroundColor: "{colors.card}"
    rounded: "{rounded.card}"
    padding: "{spacing.card-pad}"
  service-row:
    textColor: "{colors.on-dark}"
    typography: "{typography.title}"
    height: "68px"
  row-arrow-hover:
    backgroundColor: "{colors.cedar}"
    textColor: "{colors.ink}"
    rounded: "{rounded.circle}"
    size: "44px"
  facebook-row:
    backgroundColor: "{colors.navy}"
    textColor: "{colors.on-dark}"
    rounded: "{rounded.card}"
    padding: "14px 16px 14px 22px"
    height: "84px"
  work-card:
    backgroundColor: "{colors.deep}"
    rounded: "{rounded.card}"
  step-number:
    backgroundColor: "{colors.cedar}"
    textColor: "{colors.ink}"
    rounded: "{rounded.circle}"
    size: "48px"
  float-text:
    backgroundColor: "{colors.cedar}"
    textColor: "{colors.ink}"
    rounded: "{rounded.circle}"
    size: "60px"
  sent-panel:
    backgroundColor: "{colors.field}"
    textColor: "{colors.ink}"
    rounded: "{rounded.field}"
    padding: "16px"
---

# Design System: Outdoor Design Build

## Overview

**Creative North Star: "The Finished Deck at Dusk"**

The page is a calm stack of full-bleed bands taken from one real job: off-white paper, the slate navy of the deck's dark posts, the deeper navy of its black rails, and fresh cedar from the boards as the only warm colour. Every section is a band, and light and dark alternate so a new section is obvious on a phone held in one hand inside Facebook's browser. The crew's own photo carries the first screen under a navy overlay; everything below it is quiet, soft-cornered and borderless.

Density is low and the rhythm is generous: 64px bands on phones, 96px on desktop, a 20px phone gutter. Shapes are soft (24px cards, 10px fields, full pills) and nothing has a border except form controls on hover and focus. Depth is tonal: bands, a white form card on paper, a navy overlay on a photo. There is one shadow on the page, under the floating text circle.

Motion is limited to three moments: the hero headline bounces in letter by letter, content below the first screen rises 12px as it arrives, and the floating text circle slides up once the hero is gone. All three switch off under reduced motion, and the page is fully visible without JavaScript.

**Key Characteristics:**
- Full-bleed bands: paper, navy, paper, deep navy with a faint 135deg line texture, paper, navy, deep footer.
- One warm accent, used as a fill; cedar text on light grounds always uses the darker Stained Cedar.
- Cal Sans at weight 400 for every heading, button, label and phone number; the system stack for running text at 16/1.7.
- Soft borderless geometry: 24px cards, 10px tinted fields, 999px pills, circles for arrows, step numbers and the text button.
- Hover changes one small thing: the arrow circle on a row, the fill on a button, an outline on a control.

## Colors

Cool paper and two slate navies with a single fresh-cedar fill; the warmth is rationed to buttons, arrows, step numbers and the closing phrase of each dark-band heading.

### Primary
- **Fresh Cedar** (cedar): the one accent, always a fill. Primary buttons, the arrow circle on hover or focus, step numbers, the floating text circle, the eyebrow dot, focus outlines on dark grounds, icons and accent phrases on navy and deep bands, text selection. Text on it is Post Navy Ink.
- **Sanded Cedar** (cedar-2): the hover fill for the primary button, nothing else.
- **Stained Cedar** (cedar-ink): cedar as text or icon on light grounds (the header phone icon, accent phrases on paper, the header number on hover). Exists because Fresh Cedar on paper fails contrast.

### Secondary
- **Rail Slate** (navy): the mid band (services, close), the hero's base colour under the photo, the Facebook row. Doubles as the focus colour on light grounds.
- **Post Navy** (deep): the darkest band (how it works, footer), always carrying the line texture; also the placeholder fill behind the work photo.

### Neutral
- **Morning Paper** (paper): page ground, header, light bands, theme colour.
- **Card White** (card): the quote form card; the hero and photo-card headline white.
- **Field Mist** (field): input, textarea and chip fills on the white card, and the post-submit panel. Distinct from paper so fields read against white.
- **Post Navy Ink** (ink): headings on light, text on cedar, selected-chip fill, link-button stroke.
- **Slate Body** (body): running text on light.
- **Weathered Slate** (soft): ledes, placeholders, the wordmark subline, small notes.
- **Paper on Dark** (on-dark): headings, rows and buttons on navy and deep.
- **Dusk Blue Text** (on-dark-soft): running text on navy and deep bands.
- **Signal Red** (error): inline error sentences (15px) and the invalid field border. The only red.
- **Overlay Slate** (overlay-slate): never a solid; the lighter middle stop of the hero overlay (70% on phones, 42% at the right edge from 760px), letting the deck show through.
- **Photo Shade** (photo-shade): never a solid; the 78% foot of the work-card gradient under the white caption.

### Named Rules
**The Cedar Is a Fill Rule.** Fresh Cedar never sits as text on paper or white; on light grounds cedar-coloured text is Stained Cedar, and text on a cedar fill is Post Navy Ink.

**The Last Phrase Rule.** On navy and deep bands (and the hero) the closing phrase of a heading may be set in Fresh Cedar ("before winter.", "build.", "works.", "before the snow."). On paper the heading stays ink.

**The Texture Belongs to Deep Rule.** The 135deg line texture (`repeating-linear-gradient(135deg, transparent 0 22px, rgba(255,255,255,.035) 22px 23px)`) appears on the deep band and the footer only, and stays at 3.5% white so it never reads as lines through text.

## Typography

**Display Font:** Cal Sans (with Avenir Next, Segoe UI, system-ui)
**Body Font:** system stack (-apple-system, BlinkMacSystemFont, Segoe UI, Helvetica Neue, Arial)

**Character:** One geometric display face at a single weight does all the talking (headings, buttons, labels, phone numbers, the ODB wordmark) while the native system face carries reading text, so the page loads one webfont and still has a voice.

### Hierarchy
- **Display** (400, clamp 42-84px, 1.02): the hero headline only, white, max 11ch, letter-by-letter bounce-in.
- **Headline** (400, clamp 30-48px, 1.08): section headings, balanced wrapping.
- **Phone Display** (400, clamp 30-52px, 1): the big tap-to-call number in the closing band.
- **Title** (400, clamp 21-24px, 1.2): service rows; the same register at 20-23px for the Facebook row, 21px (22px desktop) for step titles, 22px/1.15 for the photo-card caption.
- **Wordmark** (400, 22px; Wordmark Wide 25px from 760px; 0.02em): "ODB", over a **Wordmark Sub** line (system 600, 12px, 0.08em, uppercase) reading "Outdoor Design Build".
- **Button** (400, 18px, 0.015em): pill buttons; 16px on the link button, 17px (20px desktop) on the header number.
- **Field Label** (400, 17px, 1.2): form labels and legends.
- **Promise** (system, clamp 17-20px, 1.5): the one line under the hero H1, max 30ch on phones.
- **Lede** (system, clamp 17-19px): text under a section heading, max 38ch.
- **Body** (system 400, 16px, 1.7): running text; inputs and chips are 16px so iOS does not zoom.
- **Caption** (system, 15px): error sentences, the note under the submit button, the composed message.
- **Small** (system 500, 14px, 0.02em): "(optional)" notes beside labels, and the eyebrow pill text.

### Named Rules
**The One Weight Rule.** Cal Sans is only ever set at 400. Hierarchy comes from size and colour, never from weight.

**The Bounce Is for the H1 Rule.** Only the hero headline animates letter by letter; no other heading gets a letter effect.

## Layout

Single column on phones with a 20px gutter (40px from 760px), content capped at 1160px. Bands pad 64px vertically on phones and 96px from 760px; the hero pads 56px/64px, then 112px/120px. Inside bands, a heading block sits 28-36px above its list, and grids use 28px gaps on phones and 64px column gaps on desktop.

- **Header:** paper strip, 64px tall (76px desktop), wordmark left and tap-to-call number right, respecting the safe-area inset.
- **Hero:** photo with `object-fit: cover` (focus 50% 60% on phones), copy stacked on a 20px grid; buttons stack full width on phones and sit side by side at 240px minimum from 760px.
- **Services:** one column of rows; two columns with a 64px gap from 1024px, an odd last row spanning both.
- **Work:** heading, square photo, then the Facebook row on phones; from 1024px a 0.8fr / 1.2fr split with the heading level with the photo's top and the Facebook row (max 520px) level with its bottom.
- **How it works:** stacked steps, three columns with 40px gaps from 1024px.
- **Ask:** heading block above the form on phones; from 1024px a 1fr / 1.2fr split with the heading block sticky at 40px. The form caps at 600px.
- **Close:** heading and lines, then the big number; from 1024px the number aligns to the bottom right.
- **Footer:** stacked lines with a 6px gap, extra bottom padding (96px plus safe area) so the floating circle never covers it.

Breakpoints: 340px (header tightens, phone icon drops), 380px (chips narrow), 760px (desktop rhythm), 1024px (two-column layouts), plus a hover-capable media query that gates every hover style.

## Elevation & Depth

Flat and tonal. Depth comes from band changes, the white form card on paper, and overlays on photographs. The single shadow belongs to the one fixed element.

### Shadow Vocabulary
- **Float lift** (`box-shadow: 0 10px 28px rgba(10,20,36,.3)`): the floating text circle only, so it reads above any band it crosses.

### Overlays
- **Hero overlay, phones** (`linear-gradient(180deg, rgba(20,36,59,.8) 0%, rgba(24,43,68,.7) 55%, rgba(20,36,59,.82) 100%)`): darkens the whole portrait crop so white text holds 4.5:1 everywhere.
- **Hero overlay, 760px up** (`linear-gradient(90deg, rgba(20,36,59,.9) 0%, rgba(20,36,59,.8) 45%, rgba(24,43,68,.42) 100%)`): heavy under the left-hand copy, opening up to show the deck on the right.
- **Photo-card foot** (`linear-gradient(180deg, transparent, rgba(14,26,44,.78))` over the bottom 40%): lets the white caption sit on the photo.

### Named Rules
**The One Shadow Rule.** Only the floating text circle casts a shadow. Cards, buttons, rows and the header stay flat; hover never adds a shadow.

## Shapes

Soft and borderless. Containers round to 24px (form card, work photo, Facebook row), fields to 10px (inputs, textarea, sent panel), and every button, chip and eyebrow is a full pill (999px). Arrow buttons, step numbers and the floating text button are circles. Focus outlines round at 6px. The only lines are hairlines between service rows (rgba(255,255,255,.12)) and the 2px control strokes that appear on hover, focus and error.

Icons are inline SVG line icons (arrow, phone, chat) at a 2.2-2.6 stroke with round caps, plus the filled Facebook and Messenger marks; every icon draws in `currentColor` and takes its colour from its context (cedar on dark, Stained Cedar beside the header number, ink on cedar fills).

## Components

### Buttons
Rounded, roomy and quiet.
- **Shape:** full pill, 56px tall, 26px side padding, Cal Sans 18px, 20px icons with a 10px gap.
- **Primary:** Fresh Cedar fill, ink text ("Get a free estimate", "Text this to Team ODB"). Full width inside the form.
- **Ghost:** transparent with a 2px stroke of paper at 70% and on-dark text; used on the hero beside the primary, carrying the Messenger mark.
- **Hover / Focus:** primary shifts to Sanded Cedar; ghost firms its stroke to white over a 10% white wash; the form's submit and link buttons gain a 2px navy outline offset 2px. Press scales to 0.98 over 0.12s. Colour transitions run 0.2s.
- **Link button:** 44px pill with a 2px ink stroke, Cal Sans 16px ("Copy message").

### Chips
- **Style:** Field Mist pill, 48px tall, 18px side padding (14px under 380px), system 16px ink text, 2px transparent stroke.
- **State:** hover draws the navy stroke; checked fills ink with white text, and checkboxes add a drawn tick; keyboard focus is a 3px navy outline offset 3px so it shows on the ink fill.

### Cards / Containers
- **Form card:** white, 24px radius, clamp(20px, 5vw, 32px) padding, 20px gap between fields, no border, no shadow.
- **Work photo card:** square photo, 24px radius, deep-navy placeholder, bottom gradient and a white Cal Sans 22px caption 20px in from the edges. No caption below the photo.
- **Facebook row:** navy pill-cornered bar (24px radius), 84px tall, the cedar Facebook mark at 30px, the line "Click to see more of our work on Facebook." and an arrow circle; only the arrow reacts.
- **Sent panel:** Field Mist, 10px radius, 16px padding; holds the composed message and the Copy button.

### Inputs / Fields
- **Style:** Field Mist fill, 2px transparent stroke, 10px radius, 52px minimum (textarea 120px), 13px/14px padding, system 16px ink, soft placeholder, navy caret.
- **Focus / Hover:** the stroke turns navy; no glow.
- **Error:** the stroke turns Signal Red and stays red while focused; the fix is written as a plain 15px sentence under the field.

### Navigation
A slim paper header: the ODB wordmark (with its uppercase subline) left, the tap-to-call number right in Cal Sans with a Stained Cedar phone icon. No menu. The footer repeats name, area, phone and Facebook as 44px tap targets on the deep band, turning cedar on hover.

### Service Rows
Each row is the whole link: Cal Sans title left, a 44px arrow circle (10% white) right, hairlines between, 68px minimum. On hover or focus only the arrow changes, filling with Fresh Cedar and turning its arrow ink; focus adds a 3px cedar ring around the arrow. Tapping a row pre-selects the matching chip in the form.

### Numbered Steps
Three steps, each a 48px Fresh Cedar circle with an ink Cal Sans 20px numeral beside a Cal Sans title and a one-line system-text explanation, on the deep band.

### Floating Text Circle
A 60px Fresh Cedar circle, ink chat icon at 26px, fixed 16px from the bottom-right safe-area corner, opening a pre-written text. It slides up from 120px below (0.35s, cubic-bezier(.2,.8,.2,1)) once the hero leaves, and hides over the service rows, while the form is on screen, and on phones while the Facebook row sits low on screen. When hidden it is untabbable and aria-hidden. Focus: a 3px white outline plus an 8px ink ring. It is absent without JavaScript.

### Hero Headline Bounce-In
After Cal Sans loads (900ms limit, else the plain heading shows), the H1 is split into letters inside no-wrap word wrappers, keeping its measured line breaks. Each letter travels from 50px right at opacity 0 to rest over 1s on cubic-bezier(.34,1.56,.64,1), 20ms apart. The H1 carries an aria-label meanwhile; when the last letter lands the original markup returns.

### Fade-Up
Elements that start below the first screen rise 12px and fade in over 0.4s ease-out as they enter (8% bottom margin). Everything already on screen, everything without JavaScript, and everything under reduced motion is visible at rest.

### Carried Exception: Eyebrow Pills
The build carries two eyebrow pills ("Team ODB is on the job" above the hero H1, "Free estimate" above the form heading): a `<p>` pill with a 7px cedar dot, 14px system 500 text, 9px/14px padding, an ink-at-6% fill on paper and a white-at-12% fill on dark. This is the owner's house-style call, recorded so the shipped values are documented; it is not a pattern for new surfaces. See Don'ts.

## Do's and Don'ts

### Do:
- **Do** alternate full-bleed bands so each section change is visible, with the line texture only on the deep band and footer.
- **Do** use Fresh Cedar as a fill with ink text on it, and Stained Cedar whenever cedar has to be text or an icon on paper or white.
- **Do** set every heading, button, label and phone number in Cal Sans at 400, and running text in the system stack at 16px/1.7.
- **Do** keep fields and chips on Field Mist inside the white card, with a navy 2px stroke on hover and focus and Signal Red on error.
- **Do** keep tap targets at 44px or more (rows 68px, buttons 56px, chips 48px).
- **Do** gate hover styles behind a hover-capable pointer query, and switch off the bounce-in, fade-up, float slide and smooth scroll under reduced motion.
- **Do** draw icons in currentColor so they take the band's colour.
- **Do** let the photo carry the hero under a navy overlay dark enough for 4.5:1 white text.

### Don't:
- **Don't** put Fresh Cedar text on paper or white, or white text on a cedar fill.
- **Don't** add shadows to cards, rows, buttons or the header; the floating circle owns the only shadow.
- **Don't** change a whole service row or the Facebook row on hover; only the arrow circle fills.
- **Don't** animate any heading other than the hero H1, and never leave content at opacity 0 when JavaScript is off or motion is reduced.
- **Don't** raise the line texture above 3.5% white or put it on paper or navy bands.
- **Don't** add borders to cards or fields at rest.
- **Don't** add new eyebrow pills; the two in the build are a carried owner exception, not a heading treatment to repeat.
- **Don't** stretch or distort photos; crop with object-fit cover.
