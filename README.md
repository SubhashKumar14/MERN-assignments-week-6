# Week 6 – Frontend Layout Assignments

This workspace contains small, static HTML + CSS pages focused on practicing modern layout techniques (Grid/Flexbox), responsive design, and reusable UI patterns.

## Tech used

- **HTML5** (semantic sections like `header`, `nav`, `main`, `section`, `footer`)
- **CSS3**
  - CSS Grid
  - Flexbox
  - Media queries (responsive breakpoints)
  - Transitions + hover states
  - Background images + overlays
  - CSS custom properties (variables)
- **No JavaScript** (these are purely layout/styling exercises)

## How to run / view

Open any folder’s `index.html` in a browser (or use VS Code **Live Server**).

> Note: in this workspace the HTML files reference `./styles.css`, while the stylesheet files are named `style.css`. If a page loads without styling, either rename `style.css` → `styles.css` in that folder, or update the `<link rel="stylesheet">` path in the HTML.

## Frontend concepts practiced

- **Layout systems**
  - **CSS Grid** for complex 2D placement (spanning rows/columns)
  - **Flexbox** for 1D alignment (nav bars, hero split layout, card rows)
- **Responsive design**
  - Media queries to stack columns into a single column on smaller screens
  - Fluid images (`width: 100%`, `height: auto`) and scalable typography
- **Reusable styling patterns**
  - A shared **`.container` pattern** (max-width + centered content)
  - Reusable **button styles** with hover transitions
  - Card UI patterns with spacing, borders, shadows, and rounded corners
- **Visual/UI fundamentals**
  - Background images, overlays (RGBA), text shadows
  - Consistent spacing, font sizing, and line-height

## Projects (features)

### `grid-project/`

- **Testimonial / review card grid** using **CSS Grid**
- Cards span across multiple columns/rows with `grid-column` and `grid-row`
- **Theme colors via CSS variables** (`:root { --color: ... }`)
- Responsive switch to **single-column** layout on small screens

### `layout-1/`

- **Marketing-style landing page** with:
  - Hero section (headline + paragraph + primary CTA)
  - 3 feature cards in a row (Flexbox)
  - Footer section
- Reusable **primary/secondary buttons** with hover states
- Responsive: feature cards stack vertically on smaller screens

### `layout-2/`

- Header + hero section with **split layout** (text + circular image)
- 3-column content cards with separators
- Responsive: hero becomes vertical and cards stack on smaller screens

### `layout-3/`

- Hero banner with **background image** + **semi-transparent overlay**
- Centered call-to-action button with hover “lift” effect
- Content section with **two-column** (text + image) layout that stacks on smaller screens

### `layout-4/`

- Simple **navbar** with horizontal links (Flexbox)
- Centered intro section with a **circular image**
- Three content sections laid out side-by-side (Flexbox)
