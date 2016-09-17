# React TypeScript Skeleton #

## Installation ##

```shell
npm install
```

## Tasks ##

1. `npm run clean`: clean build `./dist`
2. `npm run build` or `npm run build:dev`: build debug development version in `./dist`
3. `npm run build:prod`: build debug minified production version in `./dist`
4. `npm run serve` or `npm run serve:dev`: build debug development version in `./dist` and serve it
5. `npm run serve:prod`: build debug minified production version in `./dist` and serve it
6. `npm run serve:hot` or `npm start`: serve debug development version with css/js hot reload

## IDE ##

Recommended IDE is Visual Studio Code: <https://code.visualstudio.com/>

Required plugin set:

- EditorConfig for VS Code
- TSLint
- stylelint
- markdownlint

## Features ##

- React
- TypeScript
- TypeScript Runtime
- WebPack
- BrowserSync
- LESS/SCSS/SASS
- Bootstrap 3.x
- Bootstrap 4.x
- Semantic UI 2.x
- css/js/react hot reload
- debug builds with source maps
- separated vendor/app js and css code
- automatic asset bundling
- automatic source map fixer
- tslint

TODO:

- markdownlint
- stylelint
- auto tests!!!
- inline styles in react with autoprefixing
- react router
- mobx or redux
- inline small assets into css
- es-next decorators
- es-next class properties
- foundation framework
- scss example
- stylys example
- postcss example

## CSS Frameworks ##

- Bootstrap 3.x (LESS) (DEFAULT)
- Bootstrap 4.x (SCSS)
- Semantic UI 2.x (LESS)

To install Bootstrap 4 and overwrite Bootstrap 3 you need to run:

```shell
npm install bootstrap#4.0.0-alpha.4 tether --save
```

To install Semantic UI you need to run:

```shell
npm install semantic-ui-less --save
```

### Bootstrap 3.x Customization ###

Library configuration is located here:

- `src/bootstrap/bootstrap.js`
- `src/bootstrap/bootstrap.less`

You could alter `bootstrap.js` and `bootstrap.less` to disable not needed components.

You could include overrides into `bootstrap.less` to tune theme.

To activate library you need to import `bootstrap.js` and `bootstrap.less` in main file.

### Bootstrap 4.x Customization ###

Library configuration is located here:

- `src/bootstrap/bootstrap.js`
- `src/bootstrap/bootstrap.scss`

You could alter `bootstrap.js` and `bootstrap.scss` to disable not needed components.

You could include overrides into `bootstrap.scss` to tune theme.

To activate library you need to import `bootstrap.js` and `bootstrap.scss` in main file.

### Semantic UI 2.x Customization ###

Library configuration is located here:

- `src/semantic/semantic.js`
- `src/semantic/semantic.less`

You could alter `semantic.js` and `semantic.less` to disable not needed components.

Theme configuration is located here: `src/semantic/theme.config`

Site theme is located here: `src/semantic/site`

Please follow official guidelines to override styles.

As example you could refer to `node_modules/semantic-ui/src/_site` structure and official
documentation <http://learnsemantic.com/developing/customizing.html>.

To activate library you need to import `semantic.js` and `semantic.less` in main file.
