---
name: Kinetic Travel & Intelligence
colors:
  surface: '#f9f9ff'
  surface-dim: '#cfdaf2'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f3ff'
  surface-container: '#e7eeff'
  surface-container-high: '#dee8ff'
  surface-container-highest: '#d8e3fb'
  on-surface: '#111c2d'
  on-surface-variant: '#5c403d'
  inverse-surface: '#263143'
  inverse-on-surface: '#ecf1ff'
  outline: '#916f6c'
  outline-variant: '#e5bdb9'
  surface-tint: '#bf071b'
  primary: '#b20017'
  on-primary: '#ffffff'
  primary-container: '#d8232a'
  on-primary-container: '#fff1ef'
  inverse-primary: '#ffb3ad'
  secondary: '#4b41e1'
  on-secondary: '#ffffff'
  secondary-container: '#645efb'
  on-secondary-container: '#fffbff'
  tertiary: '#006443'
  on-tertiary: '#ffffff'
  tertiary-container: '#007f57'
  on-tertiary-container: '#ccffe2'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad6'
  primary-fixed-dim: '#ffb3ad'
  on-primary-fixed: '#410003'
  on-primary-fixed-variant: '#930011'
  secondary-fixed: '#e2dfff'
  secondary-fixed-dim: '#c3c0ff'
  on-secondary-fixed: '#0f0069'
  on-secondary-fixed-variant: '#3323cc'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#f9f9ff'
  on-background: '#111c2d'
  surface-variant: '#d8e3fb'
typography:
  display-hero:
    fontFamily: Plus Jakarta Sans
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
  display-hero-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  title-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  label-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
  label-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
  label-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 11px
    fontWeight: '700'
    lineHeight: 14px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  gutter-md: 1.5rem
  gutter-lg: 2rem
  margin: 1rem
  margin-md: 2rem
  margin-lg: 3rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

The design system is engineered for next-generation transit booking, fusing the operational urgency of long-distance intercity travel with the calm precision of conversational artificial intelligence. It serves dynamic commuters, intercity travelers, and digital-first explorers who demand instant clarity, uncompromised ticket inventory accuracy, and frictionless route orchestration.

### Design Movement & Ethos
The aesthetic merges **Modern Travel Functionalism** with **Atmospheric Intelligence**:
- **Clarity over Clutter:** High data-density interfaces (schedules, amenities, seat layouts, boarding points) are simplified through disciplined visual hierarchies and generous white spaces.
- **Trust-Centric Precision:** Financial and scheduling commitments require tactile, dependable affordances. Primary actions use authoritative crimson tones paired with solid slate neutrals.
- **AI Spark Integration:** Predictive queries, smart filters, and conversational agents are surfaced using ambient indigo-violet highlights and soft gradient glass backdrops to distinguish generative guidance from hard real-time inventory.

## Colors

The palette balances the energy of transit infrastructure with cognitive comfort during complex booking flows.

- **Primary (`#D8232A`):** Indian Bus Crimson. Reserved for high-intent conversion points, critical alerts, live tracking markers, and key brand callouts. It delivers instant recognition, urgency, and brand vitality.
- **Secondary (`#4F46E5` / `#6366F1`):** AI Electric Indigo. Used exclusively for smart booking workflows, natural language search prompts, route comparison insights, and conversational assistant indicators.
- **Tertiary (`#10B981`):** Verified Emerald. Denotes safety ratings, punctuality scores, confirmed seat states, and successful payment validations.
- **Neutral System:**
  - Base canvas: `#F8F9FA` to prevent screen fatigue across dense listing pages.
  - Surface elevations: Pure White (`#FFFFFF`) with borders tinted in `#E2E8F0`.
  - Typography: Deep Charcoal Slate (`#0F172A`) for headlines and (`#334155`) for readable body metadata.
- **Semantic Accents:**
  - Warning/Scarcity (`#F59E0B`): Fast-filling bus warnings, limited berth counts, and boarding gate updates.

## Typography

The typography leverages **Plus Jakarta Sans** uniformly across display, body, and label roles to maintain structural warmth, clean letterforms, and high legibility across tabular numerical data.

- **Numerals & Tabular Data:** Timestamps (departure/arrival), fares, platform numbers, and seat matrices rely on proportional figures with explicit font weights (`600` or `700`) to guarantee fast scan rates in sunlight or on the go.
- **Hierarchy Rules:** 
  - Station pairs and journey times use `headline-sm` or `title-md`.
  - Operator identities, route policies, and passenger details use `body-md`.
  - Status indicators (e.g., "FAST FILLING", "AC SLEEPER 2+1", "AI BEST VALUE") use `label-sm` with slight positive tracking (+0.02em) and uppercase casing.

## Layout & Spacing

A strictly rational 8pt spacing rhythm enforces consistency across both desktop multi-pane search grids and mobile-first single-column flows.

- **Breakpoints:**
  - **Mobile (`< 768px`):** Single column fluid canvas, `margin: 1rem`, compact vertical cards, fixed bottom reservation bar.
  - **Tablet (`768px - 1024px`):** 8-column layout, split view for route selection alongside preview cards.
  - **Desktop (`> 1024px`):** 12-column fixed grid (maximum width: 1280px), left-hand contextual filters (3 cols), primary bus feed (6 cols), and persistent interactive itinerary/seat selection drawer (3 cols).
- **Component Padding Scale:**
  - `space-xs` (4px): Badge padding, micro tag gaps, inline status icons.
  - `space-sm` (8px): Seat grid cells, pill tags, button vertical paddings.
  - `space-md` (16px): Card internal padding, conversational bubble spacing.
  - `space-lg` (24px): Card group separators, modal container interiors.
  - `space-xl` (40px): Section divisions, itinerary stage wrappers.

## Elevation & Depth

Visual hierarchy uses a layered, ambient depth system rather than aggressive drop shadows, preserving clarity across dense information tables.

- **Surface Levels:**
  - **Level 0 (Canvas):** Warm light grey (`#F8F9FA`). Background foundation for list pages.
  - **Level 1 (Card/Resting):** Pure White (`#FFFFFF`) with a 1px border (`#E2E8F0`) and an ambient tinted shadow: `0 1px 3px 0 rgba(15, 23, 42, 0.05)`.
  - **Level 2 (Active/Hover/Floating Filters):** `0 8px 24px -4px rgba(15, 23, 42, 0.08), 0 2px 6px -1px rgba(15, 23, 42, 0.04)`. Card border transitions from `#E2E8F0` to `#CBD5E1`.
  - **Level 3 (Modals/Seat Map Drawers):** `0 20px 40px -12px rgba(15, 23, 42, 0.16)`. Accompanied by a 40% opacity slate backdrop blur (`backdrop-filter: blur(8px)`).
- **AI Atmosphere Layer:**
  - Smart discovery blocks and agent interfaces apply a subtle 1px border with a gradient angle (`#818CF8` to `#E0E7FF`) and an ambient indigo glow shadow (`0 0 20px -4px rgba(99, 102, 241, 0.12)`).

## Shapes

The design system adopts a **Rounded (`2`)** geometry to balance welcoming friendliness with structured utility.

- **Primary Cards & Modals:** Standard corner radius of `0.75rem` (12px) to `1rem` (16px), giving inventory containers approachable, modern outlines.
- **Action Buttons & Form Inputs:** Uniformly set to `0.5rem` (8px) for crisp structural alignment.
- **Badges, Status Tags & Filter Chips:** Full-pill execution (`9999px`) to immediately separate categorical metadata from interactive rectangular controls.
- **Seat Deck Elements:** Sleeper berths and semi-sleeper seats feature `0.375rem` (6px) rounded contours to mimic actual cabin interiors while maintaining precision grid alignment.

## Components

### Buttons
- **Primary Action (Book Seat, Continue to Payment):** Solid crimson (`#D8232A`), white text, bold font (`label-lg`), height: 48px, radius: 8px. Hover shifts to `#C11D23`. Active scale down to 0.98 for tactile feedback.
- **AI Agent Prompts (Suggest Alternatives, Analyze Reviews):** Linear gradient fill (`#4F46E5` to `#6366F1`), white text, subtle glowing hover effect, leading spark icon.
- **Secondary / Ghost:** White background, 1px `#CBD5E1` border, slate text (`#1E293B`). Hover shifts to `#F1F5F9`.

### Chips & Filter Pills
- **State: Default:** `#FFFFFF` background, 1px `#E2E8F0` border, `#475569` text.
- **State: Selected:** Crimson-tinted background (`#FEF2F2`), border `#D8232A`, `#D8232A` text with checkmark glyph.
- **AI Insight Chip:** Tinted indigo background (`#EEF2FF`), border `#C7D2FE`, indigo text (`#4338CA`), leading sparkle icon.

### Form Inputs & Search Bar
- **Journey Search Box:** Unified segmented search unit (Origin, Destination, Date). White container with soft elevation, `#E2E8F0` internal divider lines, bold source/target labels, and an interactive destination-swap round button.
- **Input Fields:** 44px height, `#FFFFFF` background, `#CBD5E1` border. Focused state reveals a 2px crimson ring (`#D8232A`) with 0 offset.

### Travel Cards (Bus Listing Item)
- White container, rounded-xl (16px), 1px border `#E2E8F0`.
- Top section: Operator brand, bus type badge (e.g., `Bharat Benz Multi-Axle A/C Sleeper`), safety rating pill (emerald green with star).
- Middle section: Dynamic timeline visualizing departure point, time, journey duration line with stopping points, and destination time.
- Bottom bar: Live seat availability count, fast-filling badge (`#F59E0B`), starting price (`title-md` in bold slate), and primary "Select Seats" action button.

### Seat Selection Matrix
- Two distinct interactive decks: Lower Deck and Upper Deck toggle.
- **Seat States:**
  - *Available:* `#FFFFFF` with `#94A3B8` outline.
  - *Selected:* Filled `#D8232A` with `#FFFFFF` seat icon.
  - *Occupied/Reserved:* `#F1F5F9` background, muted `#CBD5E1` slash mark, non-clickable.
  - *Reserved for Women:* Pastel pink tint (`#FDF2F8`) with `#EC4899` stroke.
  - *AI Recommended Seat:* Pulsing soft violet halo indicating lowest vibration/quietest cabin area.

### Conversational AI Floating Widget
- Persistent floating pill / sheet with backdrop-blur glassmorphic background (`rgba(255, 255, 255, 0.9)`), indigo-tinted micro-border, streaming text capabilities, and suggested transit follow-up tags (e.g., "Buses arriving before 8 AM", "Live tracking available").