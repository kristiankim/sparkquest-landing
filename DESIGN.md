---
name: Sparkquest
description: Tiny daily wins, quietly celebrated.
colors:
  spark-indigo: "hsl(250 75% 55%)"
  spark-indigo-deep: "hsl(250 75% 35%)"
  spark-indigo-mist: "hsl(250 75% 95%)"
  done-green: "hsl(156 100% 39%)"
  done-green-mist: "hsl(156 100% 96%)"
  star-gold: "hsl(45 100% 50%)"
  star-gold-ink: "#5a4400"
  lavender-paper: "hsl(250 20% 98%)"
  card-white: "hsl(0 0% 100%)"
  slate-ink: "hsl(220 20% 15%)"
  slate-muted: "hsl(220 10% 45%)"
  hairline: "hsl(220 15% 90%)"
typography:
  display:
    fontFamily: "Apercu, 'DM Sans', Inter, system-ui, -apple-system, sans-serif"
    fontSize: "84px"
    fontWeight: 500
    lineHeight: 1.05
    letterSpacing: "-0.02em"
  headline:
    fontFamily: "Apercu, 'DM Sans', Inter, system-ui, -apple-system, sans-serif"
    fontSize: "56px"
    fontWeight: 500
    lineHeight: 1.1
    letterSpacing: "-0.02em"
  title:
    fontFamily: "Apercu, 'DM Sans', Inter, system-ui, -apple-system, sans-serif"
    fontSize: "24px"
    fontWeight: 500
    lineHeight: 1.2
    letterSpacing: "-0.01em"
  body-lead:
    fontFamily: "Apercu, 'DM Sans', Inter, system-ui, -apple-system, sans-serif"
    fontSize: "19px"
    fontWeight: 400
    lineHeight: 1.55
  body:
    fontFamily: "Apercu, 'DM Sans', Inter, system-ui, -apple-system, sans-serif"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.55
  label:
    fontFamily: "Apercu, 'DM Sans', Inter, system-ui, -apple-system, sans-serif"
    fontSize: "12px"
    fontWeight: 600
    lineHeight: 1
    letterSpacing: "0.12em"
rounded:
  sm: "10px"
  md: "14px"
  lg: "18px"
  xl: "24px"
  device: "44px"
  pill: "9999px"
spacing:
  xs: "8px"
  sm: "14px"
  md: "24px"
  lg: "32px"
  xl: "56px"
  section: "120px"
components:
  button-primary:
    backgroundColor: "{colors.spark-indigo}"
    textColor: "{colors.card-white}"
    rounded: "{rounded.md}"
    padding: "14px 24px"
  button-primary-hover:
    backgroundColor: "{colors.spark-indigo-deep}"
    textColor: "{colors.card-white}"
  button-ghost:
    backgroundColor: "{colors.card-white}"
    textColor: "{colors.slate-ink}"
    rounded: "{rounded.md}"
    padding: "14px 24px"
  button-ghost-hover:
    backgroundColor: "{colors.card-white}"
    textColor: "{colors.spark-indigo-deep}"
  nav-cta:
    backgroundColor: "{colors.slate-ink}"
    textColor: "{colors.card-white}"
    rounded: "{rounded.pill}"
    padding: "10px 18px"
  nav-cta-hover:
    backgroundColor: "{colors.spark-indigo-deep}"
  card:
    backgroundColor: "{colors.card-white}"
    rounded: "{rounded.xl}"
    padding: "32px"
  points-pill:
    backgroundColor: "{colors.spark-indigo-mist}"
    textColor: "{colors.spark-indigo-deep}"
    rounded: "{rounded.pill}"
    padding: "5px 8px"
  step-badge:
    backgroundColor: "{colors.spark-indigo-mist}"
    textColor: "{colors.spark-indigo-deep}"
    rounded: "{rounded.pill}"
    padding: "8px 12px"
  input-field:
    backgroundColor: "{colors.card-white}"
    textColor: "{colors.slate-ink}"
    rounded: "{rounded.md}"
    padding: "14px 18px"
---

# Design System: Sparkquest

## Overview

**Creative North Star: "The Quiet Gold Star"**

Think of the gold star on a fridge chart, grown up. Every reward in Sparkquest should feel earned and satisfying, and nothing in the system should shout. The interface is a calm, bright room: lavender-tinted paper, white cards with hairline edges, one confident indigo, and green that appears only where something has been done. Game mechanics such as points, progress and (soon) streaks are real and visible. They are presented the way a teacher hands back a starred worksheet, not the way a slot machine pays out.

The density is airy and unhurried. Sections breathe at 120px. Headlines are big and set in Apercu Medium rather than Bold, with tight tracking, so they read as confident but soft-spoken. The product is drawn honestly as UI mockups (phone checklist, parent dashboard) rather than as illustration or mascots. Atmosphere comes from blurred colour blooms behind the hero, never from decoration on the content itself.

The look is refined and gentle, aimed at the parent who buys the product while staying safe and legible for the 4-to-12-year-olds who use it. It must never resemble arcade or casino game UI (raining coins, flashing confetti, slot-machine reward loops) or loud edtech (saturated primaries, cartoon mascots, shouting badges).

**Key Characteristics:**
- One accent (Spark Indigo) carries every action and every reward; green only means "done"
- Apercu throughout, medium weight for display, wide-tracked uppercase labels
- Generous rounding everywhere, with no sharp corners
- Soft, diffuse shadows, plus an indigo-tinted glow reserved for primary actions
- Real product UI as the hero imagery; colour blooms as the only ambient decoration
- Celebrations are small: one chip, one sparkle, a gentle float

## Colors

The palette is cool and restrained: lavender-white surfaces, slate ink, one saturated indigo, and two supporting accents used sparingly.

### Primary
- **Spark Indigo**: the voice of the system. Used for primary buttons, the logo tile, the points balance pill, progress bar fills and avatars. Wherever the eye should go, or wherever value is shown, it's indigo.
- **Spark Indigo Deep**: hover state for indigo surfaces, eyebrow labels, the italic emphasis word in the hero, and text inside indigo-mist pills. It's the readable, high-contrast form of the brand.
- **Spark Indigo Mist**: tinted backgrounds for points pills, step badges, checkmark bullets, the active nav item and the progress track. Indigo at a whisper.

### Secondary
- **Done Green**: completed tasks only. The filled checkbox, the completed row's border tint, and "+N pts" earned chips. It means "done and earned" and nothing else.
- **Done Green Mist**: background of a completed task row and of the earned-points chip.

### Tertiary
- **Star Gold**: a warm counterweight, currently used only in the hero's colour bloom and as a third avatar colour. It always carries **Star Gold Ink** text when text sits on it.

### Neutral
- **Lavender Paper**: the page background. A barely-there lavender off-white that stops the page from feeling clinical.
- **Card White**: the surface for cards, inputs, ghost buttons and device mockups.
- **Slate Ink**: headlines, body emphasis, and the nav CTA background.
- **Slate Muted**: supporting body copy, list descriptions and meta lines.
- **Hairline**: 1px card borders, input borders, dividers.

### Named Rules
**The One Voice Rule.** Spark Indigo is the only colour that asks for action. Never use green, gold or another hue for a button.

**The Earned Green Rule.** Green appears only after something is done: a checked task, points received. It never decorates, and it doesn't own streaks or progress.

**The No Pure White Page Rule.** The page is Lavender Paper. Card White is reserved for surfaces that sit on top of it.

## Typography

**Display Font:** Apercu (with DM Sans, Inter, system-ui)
**Body Font:** Apercu (same stack)

**Character:** A single humanist grotesque does everything. Medium weight at display sizes gives headlines warmth without heaviness, and the italic, used for exactly one word in the hero, adds a quiet handwritten emphasis. Apercu is marketing-only and never appears in the product UI.

### Hierarchy
- **Display** (500, 84px → 56px under 960px, 1.05): the hero headline only. One italic word in Spark Indigo Deep is allowed.
- **Headline** (500, 56px → 40px under 960px, 1.1): section headings. The footer CTA uses a 64px → 44px variant.
- **Title** (500, 24px, 1.2): card titles such as the "How it works" steps.
- **Body Lead** (400, 19px → 17px, 1.55): the hero subhead, capped at about 520px wide. A related 18px size is used for section ledes and the CTA subline.
- **Body** (400, 17px, 1.55): list copy in Slate Muted, with a bold lead-in phrase in Slate Ink. Card descriptions drop to 16px/1.5.
- **Label** (600, 12px, 0.12em, uppercase): eyebrows above headlines, in Spark Indigo Deep. Mockup labels shrink to 9–10px at 0.08em.

### Named Rules
**The Medium Not Bold Rule.** Headlines are weight 500. Bold (600–700) is for labels, buttons, numbers and lead-in phrases, never for display type.

**The Bold Lead-In Rule.** Feature bullets open with a short bold phrase in Slate Ink, then continue in Slate Muted.

## Layout

The content column is 1200px wide with 56px side padding (24px under 960px), centred. Sections stack vertically with 120px of top and bottom padding (80px on mobile). Section headings are left-aligned with a 720px max width. Pricing and the closing CTA are the exceptions and centre their headings.

Feature sections ("For kids", "For parents") use a two-column grid of text and mockup at roughly 1 : 1.1, with an 80px gap. The two sections alternate which side the mockup sits on. The hero uses 1.1 : 1, text left and phone right. Card rows use an even three-column grid with 24px gaps, and pricing is a two-column grid capped at 880px.

There is a single breakpoint at 960px, where every grid collapses to one column, the nav links hide, and type steps down.

## Elevation & Depth

The system is soft-lifted. Surfaces separate from the lavender page with a hairline border plus a very diffuse, low-opacity shadow, so cards feel like they're resting a few millimetres above the paper. Device mockups get deeper, cooler shadows tinted towards indigo-black, so they read as objects in the scene. Spark Indigo surfaces cast an indigo-tinted glow, which marks them as the place to act.

### Shadow Vocabulary
- **Resting card** (`0 4px 20px -4px rgba(0,0,0,0.05)`): How-it-works cards and pricing cards.
- **Indigo glow** (`0 8px 24px -8px hsl(250 75% 55% / 0.25)`): primary buttons and the points balance pill.
- **Featured glow** (`0 16px 48px -16px hsl(250 75% 55% / 0.25)`): the recommended pricing card.
- **Device float** (`0 32px 80px -24px rgba(45,30,100,0.28)`): phone mockups. The desktop mockup uses `0 40px 80px -28px rgba(20,18,60,0.28)`.
- **Chip float** (`0 8px 24px -8px rgba(0,0,0,0.18)`): small floating callout chips over mockups.

### Named Rules
**The Tinted Glow Rule.** Only Spark Indigo surfaces cast a coloured shadow. Everything else uses neutral or cool-dark shadow.

## Shapes

There are no sharp corners anywhere. Radius grows with the size of the surface: 10px for small nav items and controls inside mockups, 14px for buttons, inputs and stat tiles, 18px for inner panels and the desktop window, 24px for content cards, and 44px for phone bodies. Pills (fully rounded) are used for every badge, points value, chip and the nav CTA. Checkmark bullets are circles, while checkboxes inside the mockups are 6px-rounded squares. Borders are always 1px Hairline, or 1.5px on ghost buttons and inputs.

## Components

### Buttons
Refined and gentle: rounded but precise, with a soft press.
- **Shape:** gently rounded (14px).
- **Primary:** Spark Indigo fill, white 15px/600 text, 14px × 24px padding, indigo glow shadow.
- **Hover / Focus:** fill deepens to Spark Indigo Deep over 200ms with the soft ease. On press it scales to 0.98.
- **Ghost:** Card White fill, 1.5px Hairline border, Slate Ink text. On hover the border tints to half-strength indigo and the text turns Spark Indigo Deep. Ghost buttons often carry a trailing "→".
- **Nav CTA:** a smaller, pill-shaped button in Slate Ink with white text (14px/600, 10px × 18px). It hovers to Spark Indigo Deep, which keeps the nav calm next to the hero's indigo button.

### Chips
- **Points pill:** a small pill in Spark Indigo Mist with Spark Indigo Deep text and tabular numbers. Inside a completed task row it switches to white with Done Green text.
- **Balance pill:** a solid Spark Indigo pill with white bold numerals, a smaller "pts" suffix and the indigo glow.
- **Earned chip:** Done Green Mist background, Done Green text, hairline green border, gently floating.
- **Step badge:** an indigo-mist pill holding a two-digit step number ("01").

### Cards / Containers
- **Corner Style:** 24px.
- **Background:** Card White on Lavender Paper.
- **Shadow Strategy:** resting card shadow. The featured card adds an indigo-tinted border and the featured glow, plus a floating "Most families" tag that overlaps its top edge.
- **Border:** 1px Hairline.
- **Internal Padding:** 32px (36px on pricing cards).

### Inputs / Fields
- **Style:** Card White fill, 1.5px Hairline border, 14px radius, 15px/500 text, 14px × 18px padding.
- **Focus:** the border turns Spark Indigo, with a 4px halo of indigo at 10% opacity, over 200ms.

### Navigation
The wordmark (indigo star tile plus "Sparkquest" at 20px/600) sits on the left, centred text links (15px/500, Slate Ink, hovering to Spark Indigo Deep) in the middle, and the Slate Ink pill CTA on the right. The nav isn't sticky. Under 960px the links hide, leaving only the wordmark and CTA.

### Check List (signature)
Feature bullets and pricing features use a circular Spark Indigo Mist badge holding a Spark Indigo Deep "✓" (22px for features, 18px for pricing), hanging to the left of the copy. This repeats the product's core action, checking things off, as a typographic device.

### Device Mockups (signature)
Hand-built HTML phone (320 × 660, 44px radius, black notch) and desktop window (traffic-light bar, sidebar, stat tiles, panels) mockups show the real product UI with sample kids (Maya, Arlo, Juno). Completed rows are Done Green Mist with struck-through Slate Muted text. Mockups can be tilted slightly (−8° to 4°) and overlapped, with floating chips layered on top.

## Do's and Don'ts

### Do:
- **Do** keep Spark Indigo as the only call-to-action colour, with Spark Indigo Deep on hover.
- **Do** set headlines in Apercu weight 500 with −0.02em tracking, and keep bold for labels, numbers and lead-ins.
- **Do** use Lavender Paper as the page background and Card White only for surfaces on top of it.
- **Do** round everything: 14px controls, 24px cards, pills for badges and chips.
- **Do** keep celebrations small and singular: one floating chip, one ✨, a gentle 8px float.
- **Do** show real product UI as imagery rather than illustration.
- **Do** honour `prefers-reduced-motion` by turning off all animations and transitions.

### Don't:
- **Don't** put white or light text on Done Green. It measures about 2.2:1 and fails WCAG. Use Done Green Mist with darker green text, or keep green to icons and fills.
- **Don't** use Done Green to decorate or to signal anything except completed and earned.
- **Don't** let the system resemble arcade or casino game UI: no raining coins, flashing confetti or slot-machine reward loops.
- **Don't** drift into loud edtech: no saturated primary rainbows, cartoon mascots or shouting badges.
- **Don't** use sharp corners or pure-white page backgrounds.
- **Don't** set display type in Bold.
