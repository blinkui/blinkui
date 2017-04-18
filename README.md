# blinkui
Web and interface design in the blink of an eye.

Have a look at the docs at [blinkui.github.io](https://blinkui.github.io/).

---

## Features

- Basic `index.html` template with asset links and responsive viewport meta tag
- Starter folder structure
- npm run scripts for processing with postcss
- postcss plugins
  - import
  - cssnext (including autoprefixer)
  - cssnano

## Getting Started

You will need

- [git](https://git-scm.com/)
- [node.js](http://nodejs.org/download/)
- [npm](https://docs.npmjs.com/getting-started/installing-node) - just a `sudo npm install -g npm` away

To start fresh, clone blinkUI into a new project and remove its git directory.

``` bash
git clone https://github.com/blinkUI/blinkUI.git new-project
cd new-project
rm -rf .git
```

Install the dependencies.

``` bash
npm install
```

Compile source files to the `css` folder.

``` bash
npm start
```

Use `index.html` as a starting point, and edit `src/blink.css` and its included modules under `src/modules/` to customize blinkUI.
