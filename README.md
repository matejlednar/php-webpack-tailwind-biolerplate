# Tailwind CSS, PostCSS, Webpack Boilerplate


Tailwind CSS, PostCSS, Webpack boilerplate.

## Included

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

### Run project

``` npm run start ```

### Build project

``` npm run build ```

### Run build/production version

Run index.html file.
You can use the Live server to run index.html.

Location: dist/index.html

### Configuration

#### npm 

Edit package.json file.

Change the entry point here.

``` "main": "src/js/script.js",```

#### tailwind.custom.config.js

Default custom preset configuration (remove demo color)

```
/* Shared configuration */
module.exports = {
  theme: {
    extend: {
    },
  },
};
```