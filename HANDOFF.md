# Outdoor Design Build — handoff at ~60%

**Live:** https://10elizabethbell.github.io/outdoorDesignBuild/ · **Repo:** https://github.com/10elizabethbell/outdoorDesignBuild · **Built:** 2026-10-17 from Muse brief (run 2026-10-17, Essex County Contractor Referrals post)

## What's built
- One page, phone first: header (plank mark + name, 226-260-8133 top-right) → hero "Your deck, done before winter." with **Get a free estimate** + **Message us on Facebook** → What we build (5 tappable rows that pre-tick the form) → Our work (their real deck photo on a cedar ledge + "Click to see more of our work." Facebook card) → How it works (3 steps) → Free estimate form → "Get it built before the snow." close → footer (name, phone, Facebook, Windsor).
- **World:** spruce-green dusk, fresh cedar decking with real grain, joints and screw lines, pale siding grey for reading sections, maple gold only on focus/hover.
- **Signature element:** maple and elm leaves blow in on a gusty breeze and settle on the cedar boards (hero, plank seams between sections, under the photo, closing scene). Finger or mouse works like a leaf blower; drag on the hero deck works in every direction on phones (`touch-action:none` on the deck only, so the text area still scrolls). Swept leaves drift back after 4–10 s. Tunables: `TUNE` at the top of the leaves script.
- **Contact:** form composes a text to 226-260-8133 (`sms:` with encoded body; "Didn't open?" panel with copy button and a Messenger link). Messenger via `https://m.me/ODB.windsor`. Call via the header number.
- Impeccable: detector, finish reviewer, and all modes except live (critique, audit, harden, clarify, adapt, optimize, polish, typeset, layout, colorize, animate, delight, bolder, quieter, distill, overdrive) run as review sweeps; fixes applied.

## Assumptions I made
- **Their real Facebook page is facebook.com/ODB.windsor**: Facebook's own `og:url` for the brief's `profile.php?id=100063737972732` is that vanity URL (checked 2026-10-17), so Messenger links use `m.me/ODB.windsor`. Page intro: "strives to build custom project designs that exhibit a premier level of workmanship."
- **Services list is inferred**: Decks, Pergolas, Railings & stairs (from their one deck photo), Patios and Landscaping (from the Houzz directory categories). They publish no list. Confirm with owner.
- **Crew voice ("we")**: they sign off "Team ODB".
- **Colors**: no logo or brand colors exist; cedar is sampled from their own deck photo; spruce green chosen as a non-black ground.
- **Seasonal headline** ("before winter") follows their 2026-10-17 post. Swap in spring, e.g. "Your deck, ready for summer." and close "Get it built before the heat."
- How-it-works steps are generic design-build steps, nothing promised beyond "free estimate" (which they offer).
- "2,600+ people follow our builds" = 2,635 Facebook followers (page meta, 2026-10-17).
- Audience treated as general homeowners, not 40+ (brief doesn't say); motion kept.
- Houzz address (1632 Morningstar Ave) left off the page: probably a home address.
- Impeccable's concept roll (seed 794cc240) assigned "end-grain rings"; I built the cedar-and-leaves direction instead because rings read as a topo map and the leaves carry their own "before winter" hook. The rings' discipline survives as real grain in every board.

## Placeholders and gaps
- **No logo.** Header mark is three cedar boards drawn in SVG; favicon and iPhone icon (`img/icon-180.png`) use the site's own lettering, "ODB" in heavy sans on a cedar tile. Replace both with their logo if they have one.
- **One photo only** (their Facebook profile picture, 1536px). Need 3–6 more job photos; the post video wasn't fetchable.
- No email (footer has none — add it there and only there if they have one), no hours, no reviews, no prices, no owner name.
- **Confirm 226-260-8133 takes texts** (brief: unknown). The form hands off by text; Messenger and the header call link back it up.

## Questions for the owner
- Do you take texts on 226-260-8133?
- Which services matter most (and do you do fences, interlock, sod, snow work)?
- Owner/crew names, years in business, insured? Towns you cover beyond Windsor?
- Can we use 4–6 more job photos, ideally before/after pairs?
- Logo or colors you already use on the truck/signs?
- Any reviews customers left on Facebook we can quote?

## Ideas not built (yours to pick)
- **Runner-up world:** a blueprint drafting sheet whose plan lines draw a deck, then fill in as cedar as you scroll (the "design → build" story).
- Leaves swept off the hero deck land in the first seam (carry-through physics).
- Desktop hero: the right ~40% is open green with only flying leaves. Options: their deck photo as a framed print leaning on the deck, or a pergola beam silhouette casting dusk shadows across the boards.
- Deck detail: a fascia board along the front edge and visible board ends/end grain at the butt joints.
- Leaf lift/drag by flip angle (flat leaves glide, edge-on drop); resting leaves curl in gusts.
- Before/after slider once pairs exist; a small gallery from more photos.
- Short "Who you'll deal with" line with the owner's name and photo.
- Atkinson Hyperlegible or a sourced display face if the system stack feels too plain.

## Not verified
- Real-device touch on iPhone/Android, inside Facebook's in-app browser.
- Real `sms:` handoff on iOS and Android; `m.me` opening Messenger from the in-app browser.
- Frame rate on older phones (34 leaves + boards cached; loop sleeps off screen).
- WebKit audit (only headless Chrome was used).
