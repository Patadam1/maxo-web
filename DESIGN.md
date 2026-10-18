---
name: Maxó
description: Comida casera cocinada en leña. The page is the wood fire, burning live, with the clay pot in it.
colors:
  hollin: "#150e0b"
  hollin-2: "#20150f"
  hollin-3: "#2c1d14"
  barro: "#8e3519"
  barro-hondo: "#6a2610"
  lumbre-glow: "#ff6e1e"
  ascua: "#ffb15c"
  ceniza: "#f2e9df"
  ceniza-2: "#cbb9a8"
  ceniza-3: "#9c8674"
  sobre-barro: "#f6dccb"
  guindilla: "#de3132"
  guindilla-hondo: "#b8221f"
  on-guindilla: "#ffffff"
typography:
  display:
    fontFamily: "Bricolage Grotesque, ui-sans-serif, system-ui, sans-serif"
    fontSize: "clamp(3.1rem, 1.6rem + 5.6vw, 6rem)"
    fontWeight: 800
    lineHeight: 0.95
    letterSpacing: "-0.018em"
    fontVariation: "\"wdth\" 82, \"opsz\" 96"
  headline:
    fontFamily: "Bricolage Grotesque, ui-sans-serif, system-ui, sans-serif"
    fontSize: "clamp(2.6rem, 1.6rem + 4.6vw, 5.6rem)"
    fontWeight: 800
    lineHeight: 0.95
    letterSpacing: "-0.018em"
    fontVariation: "\"wdth\" 82, \"opsz\" 96"
  plato:
    fontFamily: "Bricolage Grotesque, ui-sans-serif, system-ui, sans-serif"
    fontSize: "clamp(2.2rem, 1.3rem + 3.6vw, 4.6rem)"
    fontWeight: 800
    lineHeight: 0.95
    letterSpacing: "-0.018em"
    fontVariation: "\"wdth\" 82, \"opsz\" 96"
  title:
    fontFamily: "Bricolage Grotesque, ui-sans-serif, system-ui, sans-serif"
    fontSize: "clamp(1.75rem, 1.3rem + 1.4vw, 2.4rem)"
    fontWeight: 800
    lineHeight: 1
    letterSpacing: "-0.018em"
    fontVariation: "\"wdth\" 82, \"opsz\" 96"
  numeral:
    fontFamily: "Bricolage Grotesque, ui-sans-serif, system-ui, sans-serif"
    fontSize: "clamp(7rem, 4rem + 14vw, 15rem)"
    fontWeight: 800
    lineHeight: 0.8
    letterSpacing: "-0.05em"
    fontFeature: "\"tnum\""
    fontVariation: "\"wdth\" 78, \"opsz\" 96"
  dato:
    fontFamily: "Bricolage Grotesque, ui-sans-serif, system-ui, sans-serif"
    fontSize: "clamp(1.35rem, 1.1rem + 0.7vw, 1.7rem)"
    fontWeight: 700
    lineHeight: 1.3
    letterSpacing: "-0.01em"
    fontVariation: "\"wdth\" 88"
  lead:
    fontFamily: "Bricolage Grotesque, ui-sans-serif, system-ui, sans-serif"
    fontSize: "clamp(1.1rem, 1rem + 0.4vw, 1.3rem)"
    fontWeight: 400
    lineHeight: 1.55
    fontVariation: "\"wdth\" 100"
  body:
    fontFamily: "Bricolage Grotesque, ui-sans-serif, system-ui, sans-serif"
    fontSize: "clamp(1.0625rem, 0.98rem + 0.3vw, 1.1875rem)"
    fontWeight: 400
    lineHeight: 1.55
    fontVariation: "\"wdth\" 100"
  label:
    fontFamily: "Bricolage Grotesque, ui-sans-serif, system-ui, sans-serif"
    fontSize: "0.95rem"
    fontWeight: 600
    lineHeight: 1.2
    fontVariation: "\"wdth\" 100"
  button:
    fontFamily: "Bricolage Grotesque, ui-sans-serif, system-ui, sans-serif"
    fontSize: "1.05rem"
    fontWeight: 700
    lineHeight: 1.1
    fontFeature: "\"tnum\""
rounded:
  pill: "999px"
  circle: "50%"
  hearth: "50% 50% 18px 18px / 30% 30% 18px 18px"
  hearth-low: "50% 50% 18px 18px / 24% 24% 18px 18px"
  panel: "24px"
  photo: "18px"
  thumb: "14px"
spacing:
  gut: "clamp(16px, 4vw, 48px)"
  wrap: "min(1240px, 100% - 2 * clamp(16px, 4vw, 48px))"
  section: "clamp(96px, 12vw, 170px)"
  section-tight: "clamp(88px, 11vw, 150px)"
  stack: "clamp(48px, 6vw, 80px)"
  row: "clamp(26px, 3.2vw, 44px)"
  cluster: "14px 22px"
  chip-gap: "10px"
components:
  llamar:
    backgroundColor: "{colors.guindilla}"
    textColor: "{colors.on-guindilla}"
    typography: "{typography.button}"
    rounded: "{rounded.pill}"
    padding: "0.95em 1.35em 0.95em 1.1em"
  llamar-hover:
    backgroundColor: "{colors.guindilla-hondo}"
    textColor: "{colors.on-guindilla}"
  llamar-bar:
    backgroundColor: "{colors.guindilla}"
    textColor: "{colors.on-guindilla}"
    rounded: "{rounded.pill}"
    padding: "0.6em 1em 0.6em 0.85em"
  llamar-cierre:
    backgroundColor: "{colors.guindilla}"
    textColor: "{colors.on-guindilla}"
    rounded: "{rounded.pill}"
    padding: "1.05em 1.6em 1.05em 1.3em"
  llamar-movil:
    backgroundColor: "{colors.guindilla}"
    textColor: "{colors.on-guindilla}"
    rounded: "{rounded.pill}"
    padding: "1.05em 1.2em"
    width: "100%"
  nav-link:
    textColor: "{colors.ceniza-2}"
    typography: "{typography.label}"
    rounded: "{rounded.pill}"
    padding: "0.55em 0.9em"
  sello:
    textColor: "{colors.ceniza-2}"
    typography: "{typography.label}"
  hogar:
    backgroundColor: "{colors.hollin-3}"
    rounded: "{rounded.hearth}"
    width: "min(100%, 330px)"
  olla:
    textColor: "{colors.ceniza}"
    typography: "{typography.title}"
    width: "min(100%, 340px)"
  plato:
    textColor: "{colors.ceniza}"
    typography: "{typography.plato}"
    padding: "{spacing.row} 0"
  foto:
    backgroundColor: "{colors.hollin-2}"
    rounded: "{rounded.hearth-low}"
    width: "clamp(220px, 24vw, 300px)"
  dato:
    textColor: "{colors.ceniza}"
    typography: "{typography.dato}"
    padding: "18px 0 0"
  ademas-pill:
    backgroundColor: "{colors.hollin-2}"
    textColor: "{colors.ceniza-2}"
    rounded: "{rounded.pill}"
    padding: "0.5em 1em"
  menu:
    backgroundColor: "{colors.hollin-2}"
    textColor: "{colors.ceniza}"
    rounded: "{rounded.panel}"
    padding: "clamp(24px, 3vw, 40px)"
  galeria-nav:
    backgroundColor: "{colors.hollin-2}"
    textColor: "{colors.ceniza}"
    rounded: "{rounded.circle}"
    size: "52px"
  galeria-nav-hover:
    backgroundColor: "{colors.hollin-3}"
---

# Design System: Maxó

## Overview

**Creative North Star: "La Lumbre"**

The site is the wood fire itself. A soot-black ground holds a live WebGL fire that rises from the bottom edge of the first and last sections, embers drift up through the copy, and the visitor can stoke it ("atizar") with a finger or the mouse. Between those two fires, whole sections are fired in barro terracotta, and the dishes appear as round clay cazuelas cut out of their photos, turning slowly as the page scrolls and breathing steam. Nothing is boxed. Light belongs to the fire, and the one saturated non-fire color is the logo's chili red, kept for the call to phone.

The density is low and the type is loud: a heavy, narrowed Bricolage Grotesque set very large and tight, with a plain full-width cut of the same family for reading. Every authored movement rises like heat, slowly and with a long ease-out, and never slides in from the side. The page is built for a phone in a hand on the street. A fixed chili-red call bar rises into view on mobile once the hero is passed and steps aside at the closing call.

The surface brief rejects the restaurant template (a stock food hero, a card grid, a map embed). The build carries that through: dishes are cut-out pots, rows and arch-framed photos, never a grid of boxed cards.

**Key Characteristics:**
- Soot ground, terracotta fields, firelight as the only glow.
- One red action: chili-red pill buttons with the number always visible.
- Heavy, narrowed grotesk display (wdth 82, opsz 96) over a full-width body cut (wdth 100).
- Hearth-arch contours, pills, hairline rules; no card boxes.
- Live fire, embers, steam and turning pots; every entrance rises.

## Colors

A three-ink fire palette: soot, clay and ash, lit only by ember light and punctuated by one chili red.

### Primary
- **Guindilla (Logo Chili Red)** (`guindilla`): the call to phone and nothing else. Every "Llamar" pill, plus text selection. It is the logo's mark color, so the action reads as the brand speaking.
- **Guindilla Honda (Deep Chili)** (`guindilla-hondo`): hover state of the call pill only.
- **On Chili White** (`on-guindilla`): label color on the chili pill and on selection. Ash white on chili measures about 3.8:1 and fails at button size; pure white clears 4.5:1, which is why it exists. Use it nowhere else.

### Secondary
- **Barro (Fired Terracotta)** (`barro`): a whole-section field (the encargo section). It owns the section edge to edge rather than tinting a box. It is also the scrollbar thumb.
- **Barro Hondo (Deep Clay)** (`barro-hondo`): the second clay field (the opiniones section), darker so two clay sections never read as the same band.
- **Sobre Barro (Clay-Lit Ash)** (`sobre-barro`): body text and supporting copy set on either clay field. Headings on clay stay in ceniza.

### Tertiary
- **Lumbre Glow (Ember Light)** (`lumbre-glow`): never a fill or text color. It appears only as light: as low-alpha radial glows at the base of the hero and the closing section (about 0.25 to 0.28 alpha), as the warm gradient on the lower edge of the hearth photo, and as the core of the shader's flame ramp. Warmer variants of the same light (rgb 255/140/60 and 255/160/90 at 0.18 to 0.35 alpha) warm the clay fields and the footer's top hairline.
- **Ascua (Glowing Coal)** (`ascua`): the lit accent. It is used for one lit word in the hero headline ("barro"), the filled part of the Google stars, the keyboard focus ring, and hover underlines on links. It always reads as something glowing, never as a decorative tint.

### Neutral
- **Hollín (Soot)** (`hollin`): the page ground, the browser theme color, the footer band, and the scrollbar track.
- **Hollín 2 (Banked Soot)** (`hollin-2`): raised soot for pills, the menu panel, gallery buttons, empty photo wells, and the hearth photo's 10px soot ring.
- **Hollín 3 (Charred Wood)** (`hollin-3`): the hover state of the gallery buttons and the backing behind the hearth photo.
- **Ceniza (Ash White)** (`ceniza`): headings, primary text and data values. Hairline rules are ceniza at low alpha (0.08 to 0.30), never a separate grey.
- **Ceniza 2 (Warm Ash)** (`ceniza-2`): leads, supporting copy, nav links, labels, captions.
- **Ceniza 3 (Cold Ash)** (`ceniza-3`): the quietest note (the menu footnote). Use it sparingly and only on soot.

### Named Rules
**The Named Inks Rule.** Every color on the page is one of the tokens above or a low-alpha version of one. Hairlines are ceniza at alpha, shadows are soot or deep clay at alpha, and glows are ember light at alpha. Never add a free grey or a new hue.

**The Firelight Rule.** Orange is light, not paint. Lumbre glow appears only as radial light or flame; ascua only marks something lit (one word, the stars, focus, hover). No orange fills, orange buttons or orange section bands.

**The One Red Rule.** Guindilla means "phone us". If something is chili red, tapping it calls 926 82 15 30.

## Typography

**Display Font:** Bricolage Grotesque (variable: opsz 12–96, wdth 75–100, wght 300–800), with ui-sans-serif, system-ui fallback
**Body Font:** Bricolage Grotesque, same family, at full width

**Character:** One warm grotesk worked two ways. Headings are pressed narrow (wdth 82) at the largest optical size (opsz 96) and weight 800, so they set big and tight like lettering burned into wood. Reading text opens back out to full width (wdth 100) at regular weight, so it stays plain and friendly.

### Hierarchy
- **Display** (800, clamp 3.1rem to 6rem, 0.95): the hero H1 only, held to about 11ch.
- **Headline** (800, clamp 2.6rem to 5.6rem, 0.95): section H2s. Individual sections size it down (gallery and opinions, max about 4.2 to 4.4rem) or up (closing call, max 6rem), always within this voice. Balanced wrapping, about 12 to 14ch.
- **Plato** (800, clamp 2.2rem to 4.6rem, 0.95): the dish-row names, nearly headline-sized because each row is its own heading.
- **Title** (800, clamp 1.75rem to 2.4rem, 1.0): the encargo pot names and the menu title, about 12ch.
- **Numeral** (800, clamp 7rem to 15rem, 0.8, -0.05em, wdth 78, tabular figures): the giant 4,6 rating. It is the narrowest setting on the page.
- **Dato** (700, clamp 1.35rem to 1.7rem, 1.3, wdth 88): values in the visit data (address, hours, how, Instagram). It is a middle width between display and body.
- **Lead** (400, clamp 1.1rem to 1.3rem, 1.55): section intros and the hero line, 34 to 42ch.
- **Body** (400, clamp 1.0625rem to 1.1875rem, 1.55, wdth 100): all reading text, 30 to 40ch, with pretty wrapping.
- **Label** (600, 0.95rem): nav links, data terms, pills, captions (0.85 to 0.98rem). Sentence case, never uppercase-tracked.
- **Button** (700, 1.05rem; the number in 800 with tabular figures): the call label.

### Named Rules
**The Narrow Fire, Wide Ash Rule.** Display roles narrow (wdth 78 to 88) and run at opsz 96; reading text is always wdth 100. Never set body copy condensed, and never set a heading at full width.

**The Visible Number Rule.** The phone number is set in tabular figures inside the call button itself. On the desktop and mobile call pills the number is always visible; on the narrow header pill the word "Reservar" is dropped and the number stays.

## Layout

The container is one centered wrap, at most 1240px wide, with fluid gutters (`gut`, 16px to 48px). Sections are full-bleed bands with generous fluid vertical padding (`section`, `section-tight`); the wrap carries the inline gutters, so sections pad only in the block direction. Internal rhythm: headers sit apart from their content by `stack` (48px to 80px, about 110px for the pot row), dish rows breathe on `row`, and action clusters use 14px by 22px gaps.

The compositions are asymmetric two-column splits rather than centered stacks. The hero runs 1.25fr to 0.75fr (copy left, hearth photo right), the encargo header 1.1fr to 0.9fr with the paragraph bottom-aligned to the heading, and opiniones pairs an auto-width numeral with the text. The three pots sit in a 3-column row, with the middle pot dropped by up to 90px so the row reads as pots on a fire rather than a grid. The closing section is the one centered composition: heading, line and call button, then a 4-column data row on hairlines.

Responsive rules:
- **861px and up** is the desktop layout. Hover effects are gated on `(hover:hover)` and pointer-follow effects also require at least 861px.
- **At 860px and below,** everything goes to one column. The header nav is hidden, leaving the logo and the call pill. The hero aligns to the top, the hearth photo centers and shrinks to min(52vw, 210px), and the fire canvas grows to 72% of the hero height. The pots stack with 64px gaps and lose their offset. Dish rows gain a 92px inline thumbnail (3:4, 14px corners), and the floating pointer photo is removed. Gallery photos become 62vw wide and the arrow buttons are hidden. The fixed full-width mobile call bar appears.
- **At 980px and below,** the visit data goes to 2 columns; **at 560px and below,** 1 column.
- Safe-area insets pad the header, the hero top, the atizar hint, the mobile call bar and the footer.

## Elevation & Depth

Depth comes from fire and soot, not from a shadow scale. The page is flat soot and flat clay, lit from below by radial ember glows and the live fire canvas. Soft, dark shadows appear only where an object sits in front of the fire or above the page: the cut-out pots, the hearth photo, the floating dish photo, and the call pill. Rings and hairlines are inset ceniza at low alpha, never borders in a new grey. There are no hard-edged or offset shadows.

### Shadow Vocabulary
- **Call lift** (`box-shadow: 0 10px 24px -12px rgba(0,0,0,.7), 0 2px 0 rgba(255,255,255,.18) inset`): the chili pill, with a soft drop and a glazed top lip. On hover it deepens to `0 16px 30px -14px rgba(0,0,0,.8)`. On clay it uses `0 14px 30px -14px rgba(0,0,0,.65)`. The header pill has none.
- **Hearth mouth** (`box-shadow: 0 0 0 10px #20150f, 0 0 0 11px rgba(242,233,223,.08), 0 40px 80px -20px rgba(0,0,0,.8)`): a 10px banked-soot ring, a 1px ash hairline, and a deep drop beneath the hearth photo.
- **Pot on the fire** (`filter: drop-shadow(0 30px 30px rgba(45,12,3,.55)) drop-shadow(0 6px 8px rgba(45,12,3,.4))`): the cut-out cazuelas, shadowed in deep clay rather than black so they sit on the terracotta.
- **Floating photo** (`box-shadow: 0 30px 60px -20px rgba(0,0,0,.85), 0 0 0 1px rgba(242,233,223,.1)`): the photo that follows the pointer over dish rows.
- **Soot ring** (`box-shadow: 0 0 0 1px rgba(242,233,223,.08 to .14) inset`): pills, the menu panel and gallery buttons.
- **Header scrim** (`background: rgba(21,14,11,.94); box-shadow: 0 1px 0 rgba(242,233,223,.08)`): the fixed bar once the page passes 60% of the viewport.
- **Ember line** (`box-shadow: 0 -1px 0 rgba(255,140,60,.35)`): the footer's top edge, where the closing fire meets the soot band.

### Named Rules
**The Lit From Below Rule.** Glows sit at the bottom of a section (radial gradients anchored at 110% to 115% from the top) because fire is on the floor. Never light a section from the top with orange.

## Shapes

The form language is clay-fired. Its signature contour is the **hearth arch**: an elliptical dome on top with small 18px corners at the foot (`rounded.hearth`, vertical radii 30%), like the mouth of a wood oven or lumbre. It frames the hero photo at a 9:15 portrait ratio. A lower dome (`rounded.hearth-low`, vertical radii 24%) frames every gallery photo at 9:14. Round bellies come from the cazuela cut-outs themselves: transparent PNGs set in a square, with no frame at all.

Everything interactive or small is a **pill** (999px): call buttons, nav links, additional-offer chips. Gallery arrows are full circles (52px). The only rectangles are the rare contained elements: the menu panel (24px), the floating dish photo (18px, rotated 3 degrees) and the mobile row thumbnail (14px).

**Rules** structure lists instead of boxes. 1px ceniza hairlines at 0.14 alpha run above and between the dish rows; 0.22 alpha hairlines top each data column; text links carry a 1px or 2px bottom rule that turns ascua or ceniza on hover.

### Named Rules
**The Arch Not Box Rule.** Photos are framed as hearth arches; dishes are cut-out pots or ruled rows. A plain rectangular card is never the frame for food.

## Components

### Llamar (call button)
The one action, warm and pressable.
- **Shape:** full pill (999px), with the phone icon (a 1.3em stroked SVG) leading.
- **Primary:** chili red with white text, 700 weight at 1.05rem; the number is in 800 with tabular figures. Padding is 0.95em 1.35em 0.95em 1.1em, a little shorter on the icon side.
- **Hover:** rises 2px and deepens to deep chili, with a deeper drop (0.5s, house ease). **Active:** presses down 1px and scales to 0.98. **Focus:** the global 2.5px ascua ring, offset 3px.
- **Variants:** header pill (0.6em by 1em, 0.95rem, no shadow; drops "Reservar" at 860px and below); closing call (1.2rem, 1.05em by 1.6em); mobile bar (fixed 12px from the edges, full width, centered, hidden below the viewport and rising into place over 0.6s once the page passes 80% of the viewport; it hides again near the closing call, when the header pill also fades out).

### Sello (Google seal)
The proof sits beside the call. It shows the rating in 800 at 1.5rem in ceniza, then 86 by 16px stars filled in ascua to the exact rating (clipped at 17.5px per star), then "229 opiniones en Google" underlined with a 1px warm-ash rule that turns ascua on hover. It has no box or badge. The same star set, at 180 to 260px wide, sits under the giant 4,6 numeral.

### Hogar (hearth photo)
The real olla-fuego photo in a hearth-arch frame (9:15, max 330px), with the hearth-mouth ring and a gradient overlay that darkens the top and warms the foot with ember light. The hero fire canvas (z-index above it) licks over its lower edge. The figcaption floats centered 38px above it and is hidden on mobile.

### Olla (encargo pot)
A cut-out cazuela (square, up to 340px) with a deep-clay drop shadow, three blurred steam strokes rising from it, a Title-level name (about 12ch) and a sobre-barro line (30ch), all centered. It only appears on a barro field. The middle pot drops up to 90px.

### Plato (dish row)
A ruled row of 1fr, 250px and 0.75fr columns: the large Plato name, an empty middle column where the floating photo lands, and a warm-ash description. On hover the name rises 6px (0.7s) and a 220px photo (9:13, 18px corners) fades and scales in from 0.85 and -4 degrees to 1 and 3 degrees. It follows the pointer vertically with a 0.14 easing factor. At 860px and below the row becomes name and description beside a 92px thumbnail.

### Foto (gallery photo)
A horizontal snap strip (start-aligned, inline padding aligned to the 1240px wrap, scrollbar hidden, mouse drag to scroll). Each photo is 220 to 300px (62vw on mobile) in a hearth-low arch at 9:14 on a banked-soot well, with a 600 warm-ash caption beneath. On hover the image scales to 1.05 over 1.2s. The 52px circular soot arrows step one photo and dim to 0.35 at either end.

### Dato (visit data)
A definition column topped by a 0.22 alpha hairline with 18px top padding. The term is a 600 warm-ash label, the value is set at Dato level (700, wdth 88), and a small note sits under it at body size in warm ash at full width. Links inside take a 1px rule that turns ascua on hover. "Cómo llegar" is a bold full-width link with a trailing arrow.

### Menu (menú del día panel)
The one contained panel. It is banked soot with 24px corners, a 0.08 alpha ash inset ring and 24 to 40px padding. The header pairs a Title-level name with the price in 800 at 1.6rem with tabular figures, baseline-aligned. Columns auto-fit at a 220px minimum with 700 warm-ash course headings, and a cold-ash footnote closes it. It renders only when the editable data block has dishes; otherwise it stays hidden.

### Additional offer pills
A wrap of banked-soot pills (0.5em by 1em, ash inset ring, 500 weight at 0.95rem, warm ash) with 10px gaps. They carry facts, not filters, and have no states.

### Navigation
A fixed transparent bar over the fire. Once scrolled past 60% of the viewport it gains a 0.94 alpha soot scrim and hairline, and the 118px light logo fades and rises into place. Links are warm-ash 600 pills (0.55em by 0.9em) that lighten to ceniza on a 0.07 ash wash on hover. At 860px and below only the logo and the call pill remain.

### El Fuego (signature: the live fire)
- **Flames:** a full-width WebGL fragment shader (two-layer fbm noise, rendered at half resolution) anchored to the bottom 64% of the hero (72% on mobile) and 52% of the closing section. Its color ramp runs from soot red through clay red and flame orange to pale gold. The tongues climb continuously.
- **Embers:** a 2D canvas over the hero with additive blending, up to 220 particles spawning in the bottom 18%. They rise at 40 to 130px/s, sway, flicker, and fade from gold to red as they die.
- **Atizar:** pointer movement over either fire bends the flames up toward the pointer (Gaussian bump), adds heat (faster, taller flames, decaying by 0.35 per second) and, in the hero, sprays up to 6 stronger embers per move toward the touch. A hint line ("Pasa el dedo / el ratón por el fuego", 600 at 0.85rem with a hand icon) sits at the bottom center and fades over 0.8s after the first stoke.
- **Burn down and relight:** scrolling through the hero lowers its flame level by up to 70% and its ember rate by up to 80%. The closing fire starts at 0.35 and rises toward 0.85 as its section comes into view, so the fire glows again at the last call. Fires pause when off-screen.
- **Reduced motion:** a single still frame of each fire is drawn; no embers, no hint.

### Motion grammar
- **House ease:** `cubic-bezier(.16,1,.3,1)`, a long ease-out on every authored transition.
- **Sube (heat rise):** entering elements start 28px low, blurred by 8px and transparent, then rise and sharpen (opacity and blur 1s, translate 1.2s). They trigger once at 18% visibility.
- **Pots:** they scale up from 0.82 over 1.4s, staggered 0.12s per pot. Steam loops every 4.8s per stroke, offset 1.6s, rising from 30% below to 35% above while stretching vertically.
- **Turning cazuelas:** each pot rotates with scroll in proportion to its distance from the viewport center (up to about 38 degrees per viewport), alternating direction pot to pot.
- **Reduced motion:** entrances render in their final state, steam holds at 0.45 opacity, pots do not rotate, and smooth scrolling is off.

## Do's and Don'ts

### Do:
- **Do** keep every color within the named inks; tint with alpha (hairlines are ceniza at 0.08 to 0.30) rather than adding a grey.
- **Do** use guindilla only for tel: actions, with white label text and the number in tabular figures inside the pill.
- **Do** frame food photos as hearth arches (`rounded.hearth`, `rounded.hearth-low`) and set dishes as cut-out pots or ruled rows.
- **Do** let whole sections be fields of barro or barro hondo, with sobre-barro body text on them.
- **Do** set headings in Bricolage Grotesque 800 at wdth 82 and opsz 96, line height 0.95, tracking -0.018em; set body at wdth 100.
- **Do** make every authored entrance rise (Sube: 28px, 8px blur, house ease), and honor prefers-reduced-motion with final states and a still fire.
- **Do** light sections from below with ember glows at 0.25 alpha or less, and keep the fire canvas at the bottom edge.
- **Do** keep the call one tap away on mobile with the fixed full-width call bar.

### Don't:
- **Don't** use orange as a fill, button or text block; ember color is light (glows, flame, the stars, focus, one lit word).
- **Don't** put a grid of boxed cards on the page for dishes, photos or reviews; the restaurant-template stock hero, card grid and map are what this world refuses.
- **Don't** slide authored entrances in sideways; motion rises. User-driven horizontal scrolling in the gallery strip is fine.
- **Don't** use chili red for anything that does not call the restaurant.
- **Don't** add hard-edged or offset shadows; depth is soft soot or deep-clay drops and firelight.
- **Don't** set reading text condensed or headings at full width.
