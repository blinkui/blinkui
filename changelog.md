# Changelog

## 1.0.2

- added `lh:0` to line-height module
- added responsive classes to `width` and `flex-basis` modules
- changed the cdn link to RawGit


## 1.0.1

- set default `line-height`to `1.5`in the base stylesheet
- added `@viewport`definition to base stylesheet

## 1.0.0

- mainly moved from value steps (like `p:1r`) to descriptive steps (xs, s, m, l, xl — like `p:m`)
- simplified the base styles, optimized value steps
- changed border-width to border (including `border-style: solid`)
- removed x- and y-axis classes from all modules
- `va:super` > `va:sup` (similar to html element)
- `p:s` (position static) > `p:st` (`p:s` stands now for "padding: small")
- improved `box-shadow` module

## 0.8.3

- added placeholder text color fix to base styles
- added min-height to `body` element in the base styles


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
- background-blend-mode
- cursor (pointer)
- filters
- transform (rotate, scale)


---

## To do:

## Add/Improve:

- `padding_child.css` (then, margin und padding need !important)
- separate section for “add-ons/helpers” (like `margin_child.css`)
- negative margins (for grids) — or is it better to go for the grid module?
- min-height
- aspect-ratios
- transform: grow, shrink, up, down (for animations?)
- `clear` floats

## Make responsive(?):

- `width`, `max-width` and `height` should have responsive classes (at least vh + %/vw)
- `flex-basis`
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

## Duplicates:

- `fs`: flex-shrink (0–2), font-size (xs–xxl), font-style (n/i)
- `fw`: font-weight (xs–xl), flex-wrap (w/nw/wr)
- `o`: order (1–4), opacity (xs–xl), overflow (a/h/v)
- `bs`: border-style (d), box-shadow (xs–xl), box-sizing (bb/cb)

---

## Breakpoint template

```css
@media screen and (min-width: 40rem) {}

@media screen and (min-width: 80rem) {}

@media screen and (min-width: 120rem) {}
```
