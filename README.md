# Enactus Canada Design System

The primary design system for **Enactus Canada** — the national network that supports
university and college students using entrepreneurial action to solve social and
environmental problems. Everything here is derived from Enactus Canada's official brand
guide and the brand asset package supplied with this project; nothing has been invented,
redrawn or approximated.

## Sources

| Source | What came from it |
|---|---|
| **`Brand-Guide.pdf`** — Enactus Canada Brand Guidelines, 20 pp (supplied directly) | **The authoritative source.** Purpose / vision / mission, the five core values and their taglines, logo rules (main logo, monochrome, incorrect usage, origami don'ts, scaling, clear space, team lockups), the primary colour specs, the WCAG contrast page, Roboto specimen + hierarchy table, icon style, the two official PowerPoint templates, and the four photography categories |
| `github.com/enactuscanada/enactus-brand-guidelines` (branch `main`) | Repository README; names `Brand-Guide.pdf` as the authoritative document and `social@enactus.ca` as the contact for logo requests |
| Uploaded asset package (65 files) | Roboto + Roboto Condensed + Knockout font binaries, logo lockups, 25 gold-circle icons, the painted icon circle, six grainy gold gradient backgrounds, origami illustration, SDG ring / curved line / colour bar |
| 15 Enactus photographs (supplied directly) | Real imagery across all four brand-guide categories, in `assets/photography/` |
| Direct guidance from Enactus Canada | Knockout is used **for titles only**; the SDG wheel colours are the **official secondary palette**; Enactus Cactus (the online platform for registered students and faculty) has its own full logo, and the cactus on its own is **only the favicon** — none of these is stated in the PDF |

The brand guide was read in full and is the ground truth for everything below; where it is
silent (Knockout's role, the secondary palette) the gap is filled by direct guidance from
Enactus Canada and flagged as such. The GitHub repository itself carries only a README —
explore it for anything added upstream later. Logo requests and non-standard lockups:
**social@enactus.ca**.

## Company & product context

Enactus Canada is a **non-profit network**, not a software company. Its externally
visible surfaces are presentations, documents, social graphics and recruitment material —
so this system's high-fidelity surface is the **slide layout set**, and the UI components
exist to support web and application work built in the brand.

No product UI, application code or screen designs were supplied, so **no UI kits were
built**: recreating screens that do not exist would mean inventing a product. If Enactus
Canada has a member portal, team dashboard or marketing site you want recreated, attach
the codebase or a Figma file and the kits can be added.

**Purpose** — to ignite the potential of Canada's future leaders to drive positive social,
environmental, and economic impact by empowering their entrepreneurial mindset.

**Vision** — to offer an unparalleled experience among Canadian post-secondary programs,
where passionate students collaborate to create a better world by bringing their innovative
ideas to life.

**Mission** — Enactus is a network of leaders committed to using business as a catalyst for
positive social and environmental impact. We educate, inspire, and support young people to
use innovation and entrepreneurship to solve the world's biggest problems.

**Core values** — the official wording is on enactus.ca/about. When a value appears on a slide, use the name and a plain one-liner:

| Value | Say it plainly |
|---|---|
| Innovation | We look for new ways to solve old problems. |
| Passion | We care about the people our projects serve. |
| Collaboration | We build things together, with people unlike us. |
| Integrity | We do what we say, and we show our numbers. |
| Entrepreneurship | We spot a need and start something. |

The Purpose, Vision and Mission statements above are official and stay word for word in formal documents. Everywhere else, use the short version: **students using business to solve problems in their communities.**

---

## CONTENT FUNDAMENTALS

Learned from how enactus.ca news posts are actually written (Student Leader of the Year, Early-Stage Summer Sprint, National Champion announcements).

**Lead with a person, a school and a result.** Every story opens with who did what: "LimbRise, a mobility aid for knee injuries from the University of Prince Edward Island, is the winner of…" Name the team, the school and the project in the first sentence.

**Say what the project does in plain words.** "A mobility device that replaces crutches." "Turns waste paper into new products." If a 12-year-old couldn't repeat it back, rewrite it.

**Show it with numbers.** The posts count things: "from four returning members to 30", "65 ventures from 27 schools", "a $2,000 bursary". One real number beats three adjectives. Always say where the number came from.

**Let students talk.** Each post carries a first-person quote from a student, and those quotes are the most human lines on the site. Use real quotes with full attribution: *Name, Role, Enactus [School]*.

**Thank people by name.** Posts close by thanking mentors, judges, faculty advisors and the partner who funded the award. Keep that habit.

**Person.** "We" for Enactus Canada or a team speaking about itself. "You" when talking to a student, advisor or partner. Not "Enactus Canada is pleased to announce".

**Casing.** Title case for slide titles (as in the Presentation Toolkit); sentence case for body. ALL CAPS only on the cover title. Canadian spelling: *colour*, *centre*, *program*.

**Plain words, not jargon.** The website still uses some jargon. Don't copy it into new material:

| Instead of | Write |
|---|---|
| ignite potential / empower | help, train, fund, back |
| catalyst for good | a way to fix a problem |
| changemakers / future leaders | students, team members |
| ecosystem | network, community, everyone involved |
| impact-driven venture | business that helps people |
| drive positive social, environmental and economic impact | help people, the planet and local economies |
| stakeholders | partners, judges, advisors, the people the project helps |
| experiential learning | learning by doing |

**Tone.** Proud, warm and specific, like a team captain introducing the team. The site celebrates ("We can't wait to see how these ventures evolve") without hype. Excitement comes from facts, not exclamation marks. No emoji in branded material.

**On-voice examples (from enactus.ca):**
- "He grew his team from just four returning members to 30 active members."
- "Over the six-week sprint, 65 ventures from 27 Canadian postsecondary schools took part in weekly workshops."
- "Last year, over 2,200 students ran 160-plus projects that helped more than 30,000 people."

**Off-voice:** "Empowering tomorrow's changemakers today!" · "We are thrilled to announce our impactful new initiative" · "Leveraging synergies across our ecosystem"

---

## VISUAL FOUNDATIONS

**Colour — primary palette.** Four official colours: Enactus Gold `#FFC222` (Pantone 7408C),
Shadow Gold `#C88A12`, Almost Black `#070D0D` (Pantone 7543C), Off-White `#F0EFEC`
(Pantone 9100C). The gold ramp (`--gold-100`…`--gold-900`) and neutral ramp exist for UI
states only and are never presented as brand colours.

**Colour — secondary palette.** The 17 UN Sustainable Development Goal colours of the SDG
wheel are Enactus Canada's **official secondary palette** (`--sdg-01`…`--sdg-17`, plus role
aliases `--secondary-red / -orange / -teal / -green / -navy`). They are the only sanctioned
colours outside the primary four. Use them for SDG graphics, goal-coded categories and
accent colour where gold and black alone are too limited. They never recolour the logo,
never appear in a gradient, and never carry body text on their own — pair them with Almost
Black or Off-White type, and check contrast per pairing. Off-White is the default page and slide ground — **not pure
white**; white appears only as a card surface sitting on Off-White. The palette is warm
and high-contrast: gold does the emotional work, Almost Black does the reading work.

**Text on gold is always Almost Black.** White on Enactus Gold fails contrast and is
explicitly out. Shadow Gold on Off-White is large-text-only (18pt+ / 14pt bold+).

**SDG colours** (`--sdg-01`…`--sdg-17`) are a separate, sealed palette. They appear only
in SDG-related graphics — the ring, the curved line, the colour bar — and never as UI
accents, chart series or decorative colour.

**Type.** Roboto is the primary typeface for every hierarchy level; the brand guide's
presentation scale is H1 Bold 50pt / H2 Medium 40pt / H3 Medium 32pt / body Medium or
Light 25pt / caption Light or Thin 20pt, scaled proportionally for smaller formats.
Roboto Condensed handles dense labels and tight slide furniture. **Knockout** (28 wide,
71 standard, 91 compressed) is the **titles-only** face: slide and page titles, section
numerals, and big figures — all-caps and tightly tracked. It never sets subheadings, body
copy, labels, captions or UI text, and it is never mixed with Roboto inside one headline.
(The brand guide names only Roboto; Knockout's titles-only role comes from Enactus Canada
directly.) Body copy leans *light*, headings lean *bold*: the
weight contrast is the system's main typographic gesture. Long-form measure caps at 68ch.

**Spacing & layout.** 4px base step. Card padding 24px, control gap 12px, section gap
64px. Slides are authored on a 64px margin at 1280×720 (96px at 1920×1080) — nothing
touches the trim except a deliberate full-bleed gradient or a split-panel edge. Layouts
are left-aligned and asymmetric: content sits against the left margin with the logo
parked top-left and generous empty ground on the right. Nothing is centre-aligned except
icon captions.

**Backgrounds.** Communication backgrounds come in two tiers, both supplied as soft
blurred-light images (several carry real grain):
- **Primary — gold & yellow (9).** The default for all Enactus Canada communication.
  Six light (`primary-gold-light-*`, Almost Black type) and three dark
  (`primary-gold-dark-*`, Off-White type).
- **Secondary — other hues (20).** Blue, green, teal, lime, orange, red, pink, magenta, in
  light and dark versions. Use when a piece needs its own identity: a campaign, an
  SDG-coded topic, a themed event. One secondary hue per piece, never mixed.
Alongside these, flat Off-White and flat Almost Black remain valid grounds. At most **two
background treatments per deck or document**; image backgrounds open, close and divide,
body slides stay flat. Keep type off the brightest hotspot of the image. These are image
assets — never re-roll them as CSS `linear-gradient()`. Filenames read
`{tier}-{hue}-{light|dark}-{form}`; 1920px web versions live in `assets/backgrounds/`,
480px previews in `thumbs/`, full-resolution masters in `originals/`. The six earlier
gold gradients are kept in `legacy/` and are superseded.

**Imagery.** Photography is warm, bright, candid and in-colour — never desaturated,
duotoned, grained or black-and-white. The guide's four categories are **Events** (the
energy of regional and national competitions, training sessions and community events),
**Community Impact** (the people, businesses and communities Enactus projects serve),
**Portraits** (clean, professional headshots of members, leaders and stakeholders) and
**Students in Action** (students working, collaborating and presenting). Fifteen real
Enactus photographs covering all four sit in `assets/photography/`, named by category.
Photos are placed full-bleed or in a hard rectangular frame with **no rounded corners and
no border**. Over a photo, text sits on the `--overlay-protect-dark` bottom-up scrim, not
on a translucent capsule. Never tint a photo gold, and never place the logo over a busy
part of the frame.

**Graphic motifs.** The origami fold is the brand's one structural idea — flat planes,
straight cuts, a single darker Shadow Gold facet standing in for a shadow. It shows up as
the logo mark, and in UI the 3px Enactus Gold top edge on feature cards
(`--border-width-rule`, as on Enactus Cactus). It is **not** a decorative line to drop
under headlines on slides. No drop shadows on brand
shapes, no 3D, no bevels.

**Corner radii.** Small: 2px badges, 4px buttons and inputs, 6px cards, 10px dialogs.
The folded-paper geometry means sharp is safer than soft. The only fully rounded shapes
are `Tag` chips, the `Switch` track and the painted icon circle.

**Cards.** White surface on the Off-White page, 1px `--border-subtle` hairline, 6px
radius, `--shadow-sm`, 24px padding, optional 3px gold top rule. On hover an interactive
card lifts 1px and goes to `--shadow-md`. Never a coloured left border as decoration —
the only coloured left edge in the system is the tone indicator on `Toast`.

**Shadows.** Neutral-tinted and restrained: paper resting on paper.
`--shadow-xs` through `--shadow-lg` all use `rgba(7,13,13,…)`. No gold shadows, no glows,
no coloured spread. The focus ring is the one tinted shadow: `0 0 0 3px rgba(200,138,18,.35)`.

**Borders.** 1px hairlines for structure, 2px for the outline button (so it reads as
deliberate, not as a disabled fill), 3px for gold section rules.

**Transparency & blur.** Used only for the modal scrim (`rgba(7,13,13,.55)`) and the
photo protection gradients. `--blur-glass` exists for overlay bars on imagery; it is not
a decorative surface treatment. No frosted cards, no translucent panels over flat colour.

**Animation.** Quick and matter-of-fact. 80ms press, 140ms colour change, 220ms fade and
lift, 360ms for larger transitions; `cubic-bezier(.2,0,.2,1)` as the standard curve.
**No bounce, no spring, no parallax, no scroll-triggered reveals.** Motion confirms an
action; it never performs.

**Hover states.** Filled controls go **darker**, never lighter — gold 500 → gold 600.
Ghost and outline controls pick up a neutral tint (`--neutral-100`); the secondary
button inverts entirely to solid Almost Black with Off-White text. Cards lift 1px.
Links go from Shadow Gold to `--gold-800`.

**Press states.** A uniform `scale(0.985)` over 80ms. No colour change on press, no
inset shadow.

**Focus states.** Shadow Gold 1px border plus the soft gold ring — never a blue browser
default, never a removed outline.

**Fixed elements.** On slides, the full logo appears on the cover and quote slides only (72px+
at 1280×720, the 3/4in minimum). All other slides carry the gold origami mark alone in the top-right
corner — never directly under or beside the full logo. White slides add a gold / black / gold bar
on the left edge. No footer text.

---

## ICONOGRAPHY

**The official set is 25 PNG icons, copied into `assets/icons/`.** Each is line art in
icon ink `#232F3A` — single weight, rounded caps, slightly hand-drawn — laid over a
**hand-painted, deliberately irregular Enactus Gold disc**. The line art intentionally
overflows the disc. The bare painted circle is available as `assets/icons/_circle.png`
for composing new icons in the same style.

Set: compass, earth, entrepreneurship, flags, food, gears, handshake, impact, leaves,
lightbulb, map, megaphone, money, people, projects, recycle, rocket, sdg, smart-device,
speakers, talk-bubbles, team, university, water, world-cup.

- **Format:** raster PNG, transparent background, square, ~1280px source. No icon font,
  no SVG sprite, no CDN icon library is used by the brand.
- **Never** substitute a flat, filled, outlined-only or multi-colour icon set (Lucide,
  Heroicons, Material) for these — the painted circle is the recognisable part.
- **Never** hand-draw a replacement in SVG. If the concept you need is missing, request a
  new icon from social@enactus.ca rather than improvising.
- **Emoji and unicode glyphs are not icons here.** They do not appear in branded material.
  The few unicode characters used inside components (×, ▾, ✓, ↓) are *control affordances*
  at UI scale, not brand iconography, and never appear on a slide.
- **Sizing:** 48px minimum, 72px default, 112–160px for slide value rows. Below 48px the
  painted texture disappears — use a plain glyph instead.
- Use `BrandIcon` to render them so the path and alt text stay consistent.

---

## Index

### Root
- `styles.css` — the single entry point consumers link; `@import` list only
- `readme.md` — this file
- `SKILL.md` — Agent Skills front matter, for use in Claude Code
- `github.md` — source-repository association and sync record
- `thumbnail.html` — homepage tile

### `tokens/`
`fonts.css` · `colors.css` · `typography.css` · `spacing.css` · `radius.css` ·
`elevation.css` · `motion.css` · `assets.css`

### `assets/`
- `fonts/` — Roboto (9 weights + italics), Roboto Condensed (3 + italics), Knockout 28 / 71 / 91
- `logos/` — `enactus-primary.svg` (gold mark + black wordmark), `enactus-primary-black.svg`
  (all-black), `enactus-full-color-white.png` (gold mark + white wordmark, for dark grounds),
  `enactus-lockup-black.png` (raster fallback for `primary`, 640×360, includes ™),
  `enactus-cactus-horizontal.png` — the full logo of **Enactus Cactus**, our online platform
  for registered students and faculty; `enactus-cactus-favicon.png` — the cactus on its own, **used only
  as the Cactus favicon**; `enactus-mark-gold.png` (origami mark alone — for avatars, favicons and app icons
  only; never on the same surface as a full lockup, and never as decoration)
- `icons/` — the 25-icon official set plus `_circle.png`
- `backgrounds/` — 9 primary (gold/yellow) + 20 secondary communication backgrounds, 16:9,
  named `{tier}-{hue}-{light|dark}-{form}.jpg`; `thumbs/` (480px), `originals/` (full-res
  masters), `legacy/` (superseded earlier gold set)
- `illustrations/` — `sdg-ring.png`, `sdg-curved-line.png`, `sdg-color-bar.png` (SDG devices, SDG
  contexts only)
- `photography/` — real Enactus photographs (`flickr-*` files come from the Enactus Canada Flickr, flickr.com/photos/enactus_canada — pull more from there as needed), filenames prefixed by brand-guide category
  (`events-`, `portraits-`, `students-in-action-`). **Web versions**: 1600px on the long edge,
  JPEG q82, ~200–380KB each — use these for slides, cards and screen work.
  `photography/originals/` holds the untouched full-resolution files for print and for any
  crop you need to re-derive.

### Components
| Group | Components |
|---|---|
| `components/brand/` | **Logo**, **BrandIcon** |
| `components/core/` | **Button**, **IconButton**, **Card**, **Badge**, **Tag** |
| `components/forms/` | **Input**, **Select**, **Checkbox**, **Radio**, **Switch** |
| `components/navigation/` | **Tabs** |
| `components/feedback/` | **Dialog**, **Toast**, **Tooltip** |

Every component has a sibling `.d.ts` (props contract) and `.prompt.md` (what & when,
usage example, variants). Each directory carries one `@dsCard` HTML showing all states.

**Intentional additions.** No source defined a component inventory — the brand guide
covers identity, not UI — so the standard primitive set above was authored to the brand's
own rules. Two are brand-specific rather than generic: **Logo** (renders the real asset
files so no one redraws a mark) and **BrandIcon** (wraps the official 25-icon set). Not
built, because nothing in the sources implies them: data table, pagination, breadcrumb,
avatar, date picker, accordion, stepper.

### `slides/` and `templates/`
- `templates/enactus-deck/EnactusDeck.dc.html` — the 13-slide deck, rebuilt from the **Enactus Canada
  Presentation Toolkit** (cover, agenda, introduction ×2, leader message, measuring progress, big
  statistic, SDG spotlight, quote, section header, programs overview, timeline,
  thank you). Copy the folder, point `ds-base.js` at the design system, and edit.
- `slides/` — one Design System card per slide, each framing that slide of the template. See
  `slides/README.md` for the toolkit's slide rules.

### `guidelines/`
Foundation specimen cards grouped as **Colors** (brand, gold ramp, neutrals, semantic
aliases, status, contrast pairings), **Type** (Knockout display, Roboto core, weights,
condensed, screen scale, presentation scale), **Spacing** (scale, spacing in use, radii,
elevation, motion), **Brand** (logo lockups, clear space, icon set, icon anatomy,
primary backgrounds, secondary backgrounds, SDG devices, Enactus Cactus) and **Photography** (the four categories, photo
treatment). The secondary palette card sits under **Colors**.

## Substitutions & gaps

- **No font substitutions.** Every typeface referenced is present as a real binary:
  Roboto, Roboto Condensed and all three Knockout cuts were supplied.
- **No icon substitutions.** The brand's own PNG icon set is used as-is; no CDN library
  is linked anywhere.
- **No logo was created.** All lockups are the supplied official files.
- **No text-only wordmark file was supplied.** Every logo asset in the package is a
  horizontal lockup (mark + wordmark) or the standalone origami mark — the two uploads named
  `Black_Wordmark.png` and `Enactus_Wordmark_white.png` are in fact full lockups, so they are
  stored and documented here as lockups, not wordmarks. When space is tight, use the origami
  mark alone rather than cropping a lockup; request a true wordmark file from social@enactus.ca.
- **Shadow Gold's print values are unreliable in the source.** Page 13 of the brand guide
  repeats Enactus Gold's CMYK / RGB / Pantone figures in the Shadow Gold column — an error
  in the document. Only the hex `#C88A12` is trustworthy; confirm the CMYK build and Pantone
  with social@enactus.ca before any print job.
- **The guide does not cover two things this system documents.** Knockout's titles-only role
  and the SDG wheel as the secondary palette both come from Enactus Canada directly rather
  than from the PDF. Worth adding to the next revision of the guide itself.
- **Spacing, radii, elevation and motion are authored, not specified.** The brand guide sets
  no grid, radius, shadow or animation rules; those token families were derived from the
  origami/flat-plane logic of the identity and are the most likely place to want changes.
- **No UI kits**, for the reason given above — no product source was supplied.
- **Community Impact** is covered by `community-impact-nscc-capcycle.jpg` (Enactus NSCC Ivany, CapCycle). More project-in-the-community photos would still help.
- **No French-language specimens.** Delegate badges in the supplied photos show En/Fr
  designations, so Enactus Canada operates bilingually — but no French copy, type or
  terminology guidance was supplied. Flag this if bilingual materials are in scope.
