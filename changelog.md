# Changelog

## 0.8.X

## 0.8.3

- added placeholder text color fix to base styles
- added min-height to html element in the base styles


## 0.8.2

- visibility on hover is now working with the `transition` module
- slight changes to the base styles

## 0.8.1

- added `vertical-align` module
- added check mark `list-style-type`
- optimized white-space in raw css files
- added `background-size` module


### 0.8.0

- beginning to keep track of changes
- moved the notes from `README.md` to this `changelog.md`
- optimized all color modules (made heavy use of variables and color functions)
- bigger steps in the `z-index` module
- added black to the body in the base stylesheet


---

## Next up

- min-height module
- background-position


---

## Notes:

### Up for discussion:

- grids
- writing-mode
- column-count (R)
- hyphens
- background-blend-mode
- cursor (pointer)
- filters
- transform (rotate, scale)


### Thoughts:

- Steps (.25, .5, 1, 2, 4, 8, 16) also in `z-index` and `top`, `right`… modules? (Consistency)
- Moving away from number steps to more semantic/descriptive steps like: `xxs › xs › s › m › l › xl › xxl`?
- fractions for values like `fb:33%` > `fb:1/3`

---

## To do:

## Add/Improve:

- `padding_child.css` (then, margin und padding need !important)
- separate section for “add-ons/helpers” (like `margin_child.css`)
- negative margins (for grids) — or is it better to go for the grid module?
- min-height
- background-size
- aspect-ratio

## Make responsive:

- `width`, `max-width` and `height` should have responsive classes (at least vh + %/vw)
- `order`
- `flex-grow`
- `z-index`
- `position`

## Demo:

- `margin_child.css`

---

*Watch out for these exceptions or abbreviations.*

## Naming exceptions:

- `bgc` (background-color) vs. `bc` (border-color)
- font-weight: normal (`fw-n`) vs. flex-wrap: nowrap (`fw-nw`, also for white-space: `ws-nw`)

## Duplicates:

- `fs`: flex-shrink, font-size, font-style
- `fw`: font-weight, flex-wrap
- `o`: order, opacity, overflow
- `bs`: border-style, box-shadow, box-sizing

---

## Breakpoint template

```css
@media screen and (min-width: 40rem) {}

@media screen and (min-width: 60rem) {}

@media screen and (min-width: 80rem) {}
```
