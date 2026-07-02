# q — Build Brief

Generated from the approved Kavi creative direction. This is the primary
document to build the full site from in Claude Code.

## Business overview

**Name / what they do:** a

**Practice:** (unspecified)

**Years doing this work:** asdasd

**Origin story:** asdasd

**Existing domain:** https://awesomesite.com

## Audience & positioning

**Who they serve:** asdasd

**How a friend would describe it:** adasd

**Positioning:** A calming, hands-on wellness practice offering restorative bodywork and personalized care in an unhurried, deeply human setting. Premium yet approachable, rooted in touch and presence.

**Audience insight:** Serves people carrying tension and depletion who need to feel genuinely seen, safe, and cared for — not processed. They want warmth and expertise in equal measure, and permission to slow down.

**Tone:** warm, grounded, calming, sophisticated

## Brand voice

**Corpus strength: thin** — treat this profile as directional only; lean on the Audience & positioning above rather than forcing thin voice signal into every line.

# Brand-Voice Profile

**Note:** The submitted corpus contains no usable content. It consists entirely of placeholder keystrokes ("a", "asdasd", "adasd") — filler text with no real words, sentences, or first-person expression. There is nothing here to analyze.

## 1. Tone
Cannot be determined. No genuine language present.

## 2. Vocabulary & phrasing
Cannot be determined. No real words were submitted.

## 3. Sentence rhythm
Cannot be determined. No sentences were submitted.

## 4. Values
Cannot be determined. No content reveals what this client cares about.

## 5. Do / Don't
- **Do** collect a real corpus before any voice work begins.
- **Don't** write copy based on this submission — there is no voice to match.

## 6. Quote bank
No usable quotes exist in the corpus.

---

**Recommendation:** To build an authentic brand-voice profile, please resubmit with real material. The most useful inputs are:
- Onboarding answers written in the client's own words (aim for 200+ words).
- A transcript of the client speaking about their practice, their clients, or why they do this work.
- Even a few honest paragraphs about who they help and how they'd describe what they do.

Once real content is available, I can produce a genuine profile.

## Offerings

asdasd

**Primary offering to feature:** asdasd
**Delivery:** both · **Location:** adasd

## Testimonials

asasd

## Visitor goals

**Primary (the hero CTA):** (unspecified)
**Secondary (supporting CTAs elsewhere on the site):** _(none)_

## Sitemap (recommended navigation)

- Home
- About
- Services
- Testimonials
- Contact

## Design system

- **Sage** `#8E9A78` — primary
- **Soft Mauve** `#C9B8C4` — accent
- **Bone** `#F5F3EF` — background
- **Warm Sand** `#EAE3D8` — surface
- **Warm Charcoal** `#3A3632` — text

**Color direction (notes):** A warm-neutral field of Bone (#F5F3EF) and Warm Sand surface (#EAE3D8) lets one Sage (#8E9A78) accent carry all emphasis, with a soft Mauve (#C9B8C4) secondary note and Warm Charcoal (#3A3632) text — restrained and soothing per the primary reference.

**Typography:** Display — Fraunces (italic available); Body — Instrument Sans. Self-hosted in the approved hero as `@font-face` — carry the same font files into the new site (never load from Google Fonts at runtime; download once and self-host, per house convention).

**Layout notes:** Committed to the juniper archetype: thin sub-60-char utility bar, centered serif wordmark with flanking nav plus a smaller nav CTA, and an asymmetric hero with a large photo layered under a smaller overlapping inset on the left against a right-side text block led by a letter-spaced caps eyebrow. A single sage square button carries all emphasis; a floating SVG botanical line drifts into the negative space as the reference's signature connective texture.

**Spacing base unit:** 8px

**Type scale ratio:** 1.25

## Design teardown (the reference this hero was built from)

LAYOUT & GRID: The primary reference (Light Textured Coach 'juniper') runs a centered ~1200px container with a thin full-width utility bar pinned at the very top ('SCHEDULE A FREE CONSULTATION →'), then a centered wordmark header with 4 nav links flanking it. The hero itself is an asymmetric two-zone split: a large layered photo group occupies the left ~55% (a main portrait plus a smaller overlapping inset photo bleeding off its corner), while the text block sits right ~45%, vertically centered, with a small eyebrow label ('HOLISTIC HEALTH COACHING') above a two-line serif display headline and a single soft button. Sections breathe with ~120px vertical gaps; the hero photos overlap the section boundary and a hand-drawn botanical line-art element floats into the negative space below-right. TYPE SYSTEM: Display serif ~44px, line-height ~1.15, near-zero tracking, sitting against a tiny ~11px all-caps letter-spaced (~0.18em) eyebrow. Body/subhead ~15px, line-height ~1.6. Wordmark ~28px lowercase serif. The ratio between eyebrow→body→h1 reads ~1.25. Display contrasts against body purely through weight and serif-vs-sans, never through loudness. SPACING: base unit 8px; component padding (button) ~14px/32px; generous 40–56px gaps between eyebrow/headline/subhead/CTA. Whitespace-dominant, low density. COLOR: near-white warm background (#F5F3EF), sage green accent for the CTA button (#8E9A78), soft mauve/lilac secondary (#C9B8C4 seen on the About button), warm charcoal text (#3A3632). Color is deliberately withheld — nearly everything is neutral so the single sage button carries all the emphasis. COMPONENTS: buttons are rectangular with very slight softening (~2px, effectively square), muted-fill primary, no ghost buttons in hero, no drop shadows — depth comes only from photo layering. Borders omitted almost everywhere. IMAGERY: photos cropped into soft rectangles, one large + one small overlapping inset for depth, arched photo shapes appear deeper in the page. Hand-drawn botanical vector line-art bleeds between sections as the signature texture move. WHY PREMIUM: (1) overlapping/inset photo layering instead of a flat single image, (2) restraint — one sage accent against a warm-neutral field, (3) the deliberate sophisticated serif with a tiny letter-spaced caps eyebrow. Borrowed from Soft Feminine Therapy: the sub-60-char utility bar tone and the floating organic vector shapes as connective texture.

## Approved hero

**Headline:** Restorative bodywork, unhurried and human
**Subhead:** Personalized, hands-on care in a calm, unrushed space — so your body can finally let go, and you can leave feeling like yourself again.
**CTA:** Book a session
**Rationale:** Two-line serif display echoes juniper's ~44px sophisticated headline; the subhead stays short and scannable per the supporting references. One sage square primary CTA is the clear focal point, distinct from the smaller nav CTA above.

The exact approved hero markup is in `brief.json` under `hero_html` — use it as the literal starting point for the hero component (reuse its fonts, palette, and composition).

## Inspiration — what to emulate

- **Light Textured Coach** (https://aspen-juniper.showit.site/) — This design does an excellent job at layering elements and using unique shapes for the images and layout elements, making it feel very custom and premium. Plenty of whitespace within sections. Overlapping photos and text break it up so not feeling so boring. Lovely soft color palette, perfect for women coaches. Great addition of video background of some sections, column spacing is generous. The serif font feels very sophisticated and deliberate.  The hero is unique with layers and textures. Gerat usage of decorate elements overkapping and between sections.
- **Soft Feminine Therapy** (https://www.blancabradleytherapy.com/) — Soft, feminine color palette. Hand-drawn nature elements. Symbolic hummingbird logo. Great usage of subtle vector elements. website uses earthy neutrals and pops of warm colors, which gives it a soothing yet vibrant feel. minimalist layout, nice padding and spacing throughout each section.  Great CTA and social icon placement. Text is a good length, nt too long and still very scannable.
- **Mens Bold & Clean** (https://www.gregfaxon.com/) — Bold typography. Nice masculine layout and a great design for men. Great CTA placement and bright CTA colors. Nice usage of decorative underline on headlines. Text is short and easy to read. Spacious layout. Slightly darker palette feels maculine and grounded. Sans serif font throughout, and bold uppercase nav item text. Feels purposeful and masculine. Good for male coaches.

## Assets & logistics

**Logo:** (none provided)

**Drive folder:** https://drive.google.com/drive/folders/1jh6uNAdgN_7g65SUQ5OaUyvO3d6MG2Qe

**Photos:** professional

**Booking system:** asdasd

**Email marketing:** asasd

## Kavi build defaults

- Next.js (App Router), Tailwind CSS, deployed on Vercel.
- Server Components first — `"use client"` only on the smallest interactive island.
- Self-host all fonts (`next/font/local`) — never `next/font/google` or a Google Fonts CSS import.
- Convert images to `.webp`; always add `alt` text.
- Include the `KaviBadge` component (see the Kavi component registry).
- If Open Design was used to develop a deeper design system for this client, its export lives in `/design-system/` — reference `colors_and_type.css` + `brand.json` + `logos/` from there. Each client gets their OWN design system; never reuse Kavi's own brand.
