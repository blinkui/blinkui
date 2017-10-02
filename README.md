# blinkui
Web and interface design in the blink of an eye.

Have a look at the docs at [blinkui.github.io](https://blinkui.github.io/).

Start prototyping right away by simply adding a link to the latest blinkUI version to your `<head>`:

``` html
<link rel="stylesheet" href="https://gitcdn.link/repo/blinkui/blinkui/master/css/blink.css">
```

(also available as a minified file:)

``` html
<link rel="stylesheet" href="https://gitcdn.link/repo/blinkui/blinkui/master/css/blink.min.css">
```

---

## What's included in this repository?

- *blinkUI* source files and folder structure
- basic `index.html` template with asset links and responsive viewport meta tag
- npm run scripts for processing with *postcss*
- postcss plugins
  - import (combines the single modules into one css file)
  - cssnext (including autoprefixer; makes sure older browsers understand our state-of-the-art css)
  - cssnano (minifies the css file / reduces the filesize)

## Getting Started

You will need [git](https://git-scm.com/) and [node.js](http://nodejs.org/download/) (which ships with [npm](https://docs.npmjs.com/getting-started/what-is-npm)).

If you should encounter problems with `node` or `npm`, you might have to [update](https://docs.npmjs.com/getting-started/installing-node) either one.

---

To start fresh, clone *blinkUI* into a new project and remove its git directory:

```bash
git clone https://github.com/blinkUI/blinkUI.git new-project
cd new-project
rm -rf .git
```

Install the dependencies:

```bash
npm install
```

Use `index.html` as a starting point, and edit `src/blink.css` and its included modules under `src/modules/` to customize blinkUI, then recompile the source files to the `css` folder:

```bash
npm start
```
