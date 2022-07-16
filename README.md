# Styles

SCSS/CSS Styles optimize for web applications. This project allow to optimize the customs scss styles and generate the standard css styles supported by all browser.

## Quick start

- Clone the repo: `git clone https://github.com/carlossolmedo/styles.git`
- Install all dependencies with [npm](https://www.npmjs.com/): `npm install`

## What's included

```bash
├── package-lock.json
├── package.json
└── scss
    ├── _layout.scss # style by default
    ├── _reboot.scss
    ├── _utilities.scss
    ├── _variables.scss
    ├── main.scss  # load declared styles
    └── mixins
```
If you want to add your customs styles you only need to change `layout.scss` for your own and call it in `main.scss`

## Getting Started

```bash
# watch mode
npm run watch
# production
npm run prod
```
Notice that production command will generate a new `dist` directory with the final css file.
