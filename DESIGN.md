# PIP&NOO: Website Design Framework

**Platform Target:** Stitch & Antigravity

---

## 1. Brand Identity & Strategy

- **Mission:** To combat the culture of single-use fashion by transforming textile waste into timeless, deeply loved, and completely unique handmade pieces.
- **Core Values:** 100% Handmade, Radically Upcycled, One-of-a-Kind.
- **The Offering:** A definitive alternative to fast fashion. Highly unique, single-run clothing and accessories.
- **Competitive Edge:** Complete exclusivity. Because materials are sourced from pre-loved items and crafted on a small scale, no two pieces are ever identical.
- **Target Audience:** Eco-conscious individuals (14+) minimizing their environmental footprint without sacrificing style. Fluid, leaning toward a feminine aesthetic, but open to all.

---

## 2. Visual Aesthetic & Global Styles

**Concept:** Earthy Upcycled-Chic. A bridge between vintage nostalgia (charity shop roots) and intentional, modern slow-fashion design.

### Color Palette

A warm, grounding, and earth-centric palette.

| Color Category | Specific Tones | Application / UI Role |
| --- | --- | --- |
| **Background** | Warm Off-White | Global background color. Flat and clean (no textures) to allow products to stand out. |
| **Greens** | Forest, Muted Mint | Secondary accents, subtle borders, or footer backgrounds. |
| **Browns** | Chocolate, Caramel, Toffee | Primary text, secondary headers, or primary button backgrounds. |
| **Oranges** | Warm Retro Orange | Interactive accent color (hover states, active links, notification dots). |

### Typography

- **Primary/Logo Font:** `Aku and Kamu`
  - *Usage:* Logo, main headers (H1, H2), expressive hero text.
- **Secondary/Body Font:** `Montserrat`
  - *Usage:* Body copy, navigation links, buttons, product descriptions, UI elements. Keeps the site grounded and highly legible.

---

## 3. Site Architecture & Navigation

### Sitemap

The site will consist of four primary pages:

1. **Home:** Introduction to the brand, featured collections, and mission statement.
2. **Collections:** The live shop featuring currently available one-of-a-kind items.
3. **Our Story:** The origin story, charity shop roots, and the upcycling/sustainability process.
4. **Archive:** A portfolio gallery of previously sold pieces to showcase the brand's history and craftsmanship.

### Navigation Rules

- **Style:** Top Navigation Bar.
- **Behavior:** Sticky (remains visible as the user scrolls down) for ease of browsing. Keep it minimalist and uncluttered.

---

## 4. UI Elements & Interactions

### Buttons

- **Style:** Modern but soft. Buttons should utilize slightly rounded corners (e.g., a `border-radius` of 4px to 8px) to reflect the handmade, approachable nature of the brand without looking like a bubble.
- **Hover State (Text/Links):** Text buttons and navigational links must smoothly transition to **Warm Retro Orange** upon hover.

### Badges & Tags

- **Constraint:** Do not use high-contrast, rounded bubble tags/badges in accent colors (such as orange bubbles like "The Antidote to Fast Fashion" or "Our Founder") as section labels or page-level decoration. Keeping these tags off the page aligns with a clean, boutique, and premium slow-fashion presentation.

### Product Imagery Interactions

- **Hover State:** Hovering over any product card/image should trigger a **slight, smooth zoom-in effect** (CSS `transform: scale(1.03)` with a smooth `transition` timing) to emphasize the tactile details of the clothing.

### E-Commerce Mechanics & Filtering

- **The Archive System:** When a product reaches inventory `0`, it is automatically hidden from the "Collections" page and dynamically moved to the "Archive" page. It loses its "Add to Cart" function and becomes a portfolio display piece.
- **Shop Filters:** The "Collections" page must include a clean filtering system allowing users to sort by:
  - **Color**
  - **Product Type:** Clothes, Accessories, Bags

---

## 5. Media & Assets

- **Photography Style:** *To Be Determined.* Developers should build flexible image containers that can support both landscape and portrait aspect ratios gracefully, anticipating high-quality, un-textured flat off-white backgrounds.
- **Detail Shots:** Product pages must support galleries to allow for macro/close-up imagery of the handmade stitching.
