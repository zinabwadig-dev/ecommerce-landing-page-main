# E-commerce Landing Page — Exercise

The HTML is finished. Part of the CSS is already written, and you have to complete the rest.

Open `index.html` in your browser and keep `style.css` open in your editor.
Every place you need to work is marked with a comment like this:

```css
/* TODO (students): ... */
```

## Rules

- Only edit `style.css`. Do not change `index.html` (except for the bonus at the end).
- Do not delete the CSS that is already written.
- Check your result in the browser after every change.

---

## Tasks

### 1. Fonts

The Regular, Medium and Bold fonts are already loaded with `@font-face`.

- [ ] Add the **Light** font (`./src/montreal/NeueMontreal-Light.woff2`) with `font-weight: 300`.

> Tip: copy one of the existing `@font-face` blocks and change it.

### 2. Header

- [ ] Add a **hover effect** on the navigation links (for example: change the color, the opacity, or add an underline).

> Tip: use `.main-nav a:hover` and `.secondary-nav a:hover`. The `transition` is already there.

### 3. Hero

- [ ] Add a **hover style** to the "Shop Now" button (for example: a white background, black text and a black border).

### 4. Categories

- [ ] Place the text (`<span>`) **on top of the image**, in the bottom-left corner.
- [ ] Make the text white, uppercase and bigger.
- [ ] **Bonus:** zoom the image a little when the mouse is over the card.

> Tip: the `.category` already has `position: relative`. Give the `span` `position: absolute` with `bottom` and `left`.
> For the zoom effect, use `transform: scale(1.05)` and `transition`.

### 5. New arrivals (products)

- [ ] Style the **"View all"** link: black color, small size, uppercase, underlined.
- [ ] Style the **product name** (`h3`): small font size, `font-weight: 500`.
- [ ] Style the **price** (`.price`): small font size, grey color.

### 6. Newsletter ⭐ (no CSS at all)

This section has **no CSS**. Style it completely by yourself.

Ideas:

- [ ] Light grey background and a lot of padding.
- [ ] Center the text.
- [ ] Put the input and the button **on the same line** (`display: flex` on the `form`).
- [ ] Give the input a border, padding and a good width.
- [ ] Make the button look like the "Shop Now" button.

### 7. Footer

- [ ] Style the titles (`h4`): small, uppercase, with space under them.
- [ ] Style the links: grey color, small size, space between each `<li>`.
- [ ] Make `.copyright` take the **full width** of the grid.

> Tip: `grid-column: 1 / -1;`

---

## Bonus

### Responsive design

Make the page look good on a phone using `@media` queries.

```css
@media (max-width: 768px) {
  /* your code here */
}
```

- [ ] Hero: 1 column instead of 2, with a smaller title.
- [ ] Categories: 1 column.
- [ ] Products: 2 columns.
- [ ] Footer: 1 column.

### Real images

- [ ] All the images use `hero.webp`. Find your own images, add them to the `src` folder, and change the `src` in `index.html`.

---

## Checklist before you finish

- [ ] Every `TODO` in `style.css` is done.
- [ ] The page has no horizontal scroll.
- [ ] All the hover effects work.
- [ ] The page looks good on a small screen (bonus).
# ecommerce-landing-page
