# Outdoor Design Build — handoff at ~60% (calm-style revamp)

**Live:** https://10elizabethbell.github.io/outdoorDesignBuild/ · **Repo:** https://github.com/10elizabethbell/outdoorDesignBuild · **Built:** 2026-10-17 from Muse brief (run 2026-10-17, Essex County Contractor Referrals post) · **Revamped:** 2026-10-19 to the calm band style · **Call Sheet:** URL confirmed on the sheet at 21:44 (script: UNCHANGED); two re-runs after the final push got `LOCK BUSY: held by muse 2026-10-19 21:56`, but the URL doesn't change, so nothing is pending

## What changed in the revamp (2026-10-19)
- **Look:** the spruce-green dusk world with cedar deck boards and blowing maple leaves is gone (it's in git history at `8cea9cb`). The page now uses the house calm band style from lpmr.co.uk: paper header, photo hero, navy services band, paper work band, deep-navy "How it works" with the faint line texture, paper form, navy close, deep-navy footer.
- **Palette:** slate navy `#223d5e` and deep navy `#14243b` (from the dark posts and black rails of their deck), paper `#f4f6fb`, one fresh-cedar accent `#dc955a` used as a fill with navy text on it; `#8f4a17` when cedar has to be text on light. There is no logo or brand colour, so this is a choice, not their brand.
- **Type:** Cal Sans headings (Google Fonts), system body at 16/1.7. The old build used the heavy system stack.
- **Hero:** their own deck photo (the only photo) under a navy overlay, cropped separately for phones (tall, centred on the stairs) and desktop (wide, pergola and railings; lighter on the right so the deck shows). White text measures ≥8.8:1 and the cedar line ≥3.5:1 against the brightest pixels behind it.
- **Headline:** "Windsor decks, done before winter." (place in the H1, per the calm rules). It bounces in letter by letter, then restores to the plain heading.
- **Motion:** leaf physics and the drag-to-sweep hero removed (now opt-in under the new rules). Only the H1 bounce-in and a 12px fade-up for content below the first screen. Reduced motion and no-JS show everything at once.
- **New:** floating text circle (bottom right, appears after the hero; hidden over the service rows, over the Facebook row on phones, and while the form card is on screen), eyebrow pills on the hero and the form, service rows that pre-tick the form, form composes a text with a "Didn't open?" panel (copy button, number, Messenger link).
- **Icons:** favicon and iPhone icon are now "ODB" in cedar on navy (`img/favicon.svg`, `img/icon-180.png`); `og.jpg` re-rendered with the new headline over the deck photo.
- **Removed:** the SVG plank mark, the leaf canvas and its script, `img/deck-01-640.webp`.

## What's built
- Header: "ODB / Outdoor Design Build" wordmark left, 226-260-8133 tap-to-call top right (the only number on the first screen).
- Hero: eyebrow "Team ODB is on the job" (their own sign-off), H1, "Custom designs, built like it's our own backyard.", **Get a free estimate** (cedar, jumps to the form) + **Message us on Facebook** (outlined, `m.me/ODB.windsor`).
- What we build: Decks, Pergolas, Railings & stairs, Patios, Landscaping; each row jumps to the form with that job ticked. Only the arrow changes on hover.
- Our work: the deck photo as a 24px card ("Deck, stairs & pergola") and the **Click to see more of our work.** Facebook card under it (beside it on desktop).
- How it works: three steps (send the idea, free estimate, we build it).
- Free estimate form: job chips (required), town or street (required), when (optional), details (optional), name (optional) → "Text this to Team ODB". Under the button: "Rather use Facebook? Message us there." (always visible, because texting is unconfirmed).
- Close: "Get it built before the snow.", "Outdoor Design Build, Windsor, Ontario.", "Not sure we come out to your street? Call and ask.", big phone number. Footer: name, Windsor, phone, Facebook. No email (none exists).

## Assumptions I made
- **Facebook page is facebook.com/ODB.windsor** (Facebook's own `og:url` for the brief's profile id, checked 2026-10-17); Messenger links use `m.me/ODB.windsor`.
- **Services list is inferred** from their one deck photo (decks, pergolas, railings & stairs) and the Houzz categories (patios, landscaping). They publish none.
- **Crew voice ("we")**: they sign off "Team ODB".
- **Seasonal copy** follows their 2026-10-17 "before winter" post. Spring swap, four places: H1 "Windsor decks, ready for summer.", close "Get it built before the heat.", the "Before winter" chip in the form, and `og:title` (plus re-render `img/og.jpg`).
- **Navy instead of the old spruce green:** the calm style's default roles, and it keeps this site distinct from Maple Outdoor Builds (also a deck crew, built in forest green).
- Audience treated as general homeowners, not 40+ (brief doesn't say), so the bounce-in and fade-up stay.
- Houzz street address left off the page (probably a home address).

## Placeholders and gaps
- **No logo.** Wordmark and icons use "ODB" lettering; replace with their logo if they have one.
- **One photo only**, used twice (hero background and the work card). 3–6 more job photos would let the hero and the work section show different jobs.
- No email, hours, reviews, prices, owner name.
- **Texts to 226-260-8133 are unconfirmed.** The form and the floating circle hand off by text; the header number (call) and Messenger back them up.

## Questions for the owner
- Do you take texts on 226-260-8133?
- Which services matter most, and do you do fences, interlock, sod or snow work?
- Owner or crew names, years in business, insured? Towns you cover beyond Windsor?
- Can we use 4–6 more job photos, ideally before/after pairs?
- Logo or colours on the truck or signs?
- Any Facebook reviews we can quote?

## Impeccable pass (2026-10-19)
- Ran the detector, a review sweep in every mode except `live` and `onboard` (critique, audit, harden, clarify, adapt, optimize, polish, typeset, layout, colorize, animate, delight, bolder, quieter, distill, overdrive, extract, document), and the finish reviewer. Applied: lighter hero overlay (white text still ≥7.7:1 and the cedar line ≥3.1:1 at the worst pixel on phones), step 3 no longer repeats the hero promise, Facebook row names Facebook, footer split into lines, float hidden without JS / over the Facebook row on phones / whenever the form card shows, letter-spacing on Cal Sans buttons and labels, `text-wrap:pretty`, one-tap select on the fallback message, brand link name includes "ODB", form named by its heading, eyebrow no longer repeats the button, Messenger line under the submit button, shorter town placeholder (it clipped at 360px), Landscaping row spans both columns on desktop, desktop work section lines the heading up with the photo's top and the Facebook link with its bottom.
- **Kept by house rule** (Impeccable flags them): eyebrow pills (the craft floor bans eyebrows outright), the H1 letter bounce-in (its overshoot and up to 900ms font wait), the floating text circle (its `sms:` link does nothing on most desktops), Cal Sans, the diagonal band texture (detector `repeating-stripes-gradient`, suppressed for index.html), the phone number shown in both the close band and the footer (the rule allows the close and footer to repeat it), and the text-first form although texts are unconfirmed.
- **Left for you:** the form fields' `#e6ecf5` fill is about 1.2:1 on the white card (the house fix; WCAG 1.4.11 wants 3:1). Try `#d5deeb` if you want them stronger. On desktop the work section's left column is mostly air between the heading and the Facebook link; a second or third photo would fill it. The kit's header shadow on scroll isn't built because the header doesn't stick.
- Detector: 0 findings against the new DESIGN.md, with two ignores in `.impeccable/config.json` for index.html: `repeating-stripes-gradient` (the house band texture) and `flat-type-hierarchy` (it can't read the clamp() heading sizes). The old leaf world's ignores were removed.
- No concept roll this time: the house rule fixes the calm band style, so Impeccable's seeded world choice didn't apply.

## Ideas not built (yours to pick)
- **Opt-in signature motion (runner-up worlds from their trade):** (1) the old maple leaves landing on cedar boards and swept off by a finger (git `8cea9cb`, best fit for "before winter"); (2) a blueprint sheet whose plan lines draw a deck, then fill in as cedar as you scroll; (3) deck boards laid one by one under the hero as the page loads; (4) a pergola's shadow sweeping across the hero like the sun moving.
- Before/after slider once pairs exist; a small gallery from more photos.
- A short "Who you'll deal with" line with the owner's name and photo.
- If Messenger turns out to be their main channel, the floating circle could open Messenger instead of a text.

## Not verified
- Real-device touch on iPhone/Android inside Facebook's in-app browser (checked in Playwright Chromium and WebKit at 360/390/430/1440).
- Real `sms:` handoff on iOS and Android; `m.me` opening Messenger from the in-app browser.
