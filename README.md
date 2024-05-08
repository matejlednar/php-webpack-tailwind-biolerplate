# PHP, Tailwind CSS, PostCSS, Webpack Boilerplate


PHP, Tailwind CSS, PostCSS, Webpack boilerplate.

## File structure
src/css/main.css - place your CSS here,<br>
src/css/tailwind.css - place tailwind functions, directives, etc. here,<br>
src/css/styles.css - auto-generated CSS by watch script (don't edit),<br>
src/js/script.js - place your JavaScript here,<br>
src/index.php - place your HTML and PHP code here,<br>
src/inc/*.php - place your *.php files here,<br>

## Included

- PHP support
- Tailwind CSS shared configuration support (custom preset)
- Smooth scrolling
- CSS support
- JavaScript Support
- Fonts support
- Images support
- JS optimization
- CSS optimization
- Build tool  

## Prerequisites

- Node.js
- npm

## Installation

```npm install```

## Run project

``` localhost/src/index.php ```

## Development

### Watch CSS changes in CSS files

Auto-generated styles.css file for development (src/css/styles.css).
Don't edit src/css/styles.css. Use main.css for styling.

``` npm run css-watch ```

## Build project

``` npm run build ```

### Run build/production version

Run index.php file.

Location: dist/index.php

``` localhost/dist/index.php ```

### Create the CSS output file (optional)

Auto-generated styles.css file for production (dist/css/styles.css). This action is not needed. The style.css file is processed during the build operation.

``` npm run css-build ```

## Configuration

### npm 

Edit package.json file.

You can change the entry point here.

``` "main": "src/js/script.js",```

#### tailwind.custom.config.js

Default custom preset configuration (remove demo color).

```
/* Shared configuration */
module.exports = {
  theme: {
    extend: {
    },
  },
};
```
