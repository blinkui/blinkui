# Changelog


## 0.8.X

### 0.8.0

- beginning to keep track of changes
- moved the notes from `README.md` to this `changelog.md`

---

## Notes:

### Up for discussion:

- grids
- vertical-align
- writing-mode
- column-count (R)
- hyphens
- background-blend-mode
- cursor (pointer)
- taking it further: filters, transitions

### Thoughts:

- Steps (8, 16) also in `z-index` and `top`, `right`… modules? (Consistency)
- Moving away from number steps to semantic steps like: XXS › XS › S › M › L › XL › XXL?

## Add/Improve:

- `padding_child.css` (then, margin und padding need !important)
- separate section for “add-ons/helpers” (like `margin_child.css`)
- negative margins (for grids) — or is it better to go for the grid module?

## Make responsive:

- width, max-width and height should have responsive classes (at least vh + %/vw)
- `order`
- `flex-grow`
- `z-index`
- `position`

## Demo:

- `margin_child.css`
- `order.css`

## Exceptions:

- `bgc` (background-color) vs. `bc` (border-color)
- font-weight: normal (`fw-n`) vs. flex-wrap: nowrap (`fw-nw` also: `ws-nw`)

## Duplicates:

- `fs`: flex-shrink, font-size, font-style
- `fw`: font-weight, flex-wrap
- `o`: order, opacity
- `bs`: border-style, box-shadow, box-sizing
