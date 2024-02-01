# WebFont Golos Text

Package for integrating `Golos Text` fonts in a web environment.

![npm](https://img.shields.io/npm/v/@wikiline/webfont-golos-text?style=for-the-badge)
![npm](https://img.shields.io/npm/dm/@wikiline/webfont-golos-text?style=for-the-badge)
![npm](https://img.shields.io/npm/dt/@wikiline/webfont-golos-text?style=for-the-badge)
___

## Installation

This package can be deployed automatically using NPM:

```
npm i @wikiline/webfont-golos-text
```

## Usage (CSS)

Font files are located in the `fonts/` directory. To import all fonts, you can use:

```css
body {
  font-family: 'Golos Text', sans-serif;
}
```

### Importing

```css
@import "~@wikiline/webfont-golos-text/src/css/all.css";
@import "~@wikiline/webfont-golos-text/src/css/all-normal.css";
```

To import specific fonts, you can use:

```css
@import "~@wikiline/webfont-golos-text/src/css/weight-400.css";
@import "~@wikiline/webfont-golos-text/src/css/weight-400-normal.css";
@import "~@wikiline/webfont-golos-text/src/css/weight-500.css";
@import "~@wikiline/webfont-golos-text/src/css/weight-500-normal.css";
@import "~@wikiline/webfont-golos-text/src/css/weight-600.css";
@import "~@wikiline/webfont-golos-text/src/css/weight-600-normal.css";
@import "~@wikiline/webfont-golos-text/src/css/weight-700.css";
@import "~@wikiline/webfont-golos-text/src/css/weight-700-normal.css";
@import "~@wikiline/webfont-golos-text/src/css/weight-900.css";
@import "~@wikiline/webfont-golos-text/src/css/weight-900-normal.css";
```

Note: Also, each file is presented in a minimized form.

### Variables

Each font uses the following CSS variables to set the font display property with the default `swap` value if CSS
variables are not defined:

```css
:root {
  --font-display: swap;
  --font-display-golos-text: swap;
}
```

## Usage (LESS)

Font files are located in the `fonts/` directory. To import all fonts, you can use:

```less
body {
  font-family: 'Golos Text', sans-serif;
}
```

### Importing

```less
@import "~@wikiline/webfont-golos-text/src/less/all";
@import "~@wikiline/webfont-golos-text/src/less/all-normal";
```

To import specific fonts, you can use:

```less
@import "~@wikiline/webfont-golos-text/src/less/_weight-400";
@import "~@wikiline/webfont-golos-text/src/less/_weight-400-normal";
@import "~@wikiline/webfont-golos-text/src/less/_weight-500";
@import "~@wikiline/webfont-golos-text/src/less/_weight-500-normal";
@import "~@wikiline/webfont-golos-text/src/less/_weight-600";
@import "~@wikiline/webfont-golos-text/src/less/_weight-600-normal";
@import "~@wikiline/webfont-golos-text/src/less/_weight-700";
@import "~@wikiline/webfont-golos-text/src/less/_weight-700-normal";
@import "~@wikiline/webfont-golos-text/src/less/_weight-900";
@import "~@wikiline/webfont-golos-text/src/less/_weight-900-normal";
```

### Variables

Each font uses the following LESS variables to set the font display property with the default `swap` value if SCSS
variables are not defined:

```less
@font-display: swap;
@font-display-golos-text: swap;
```

You can declare these variables globally or import them from a file: `_variables.less`.

```less
@import "~@wikiline/webfont-golos-text/src/less/config/_variables";
```

## Usage (SCSS)

Font files are located in the `fonts/` directory. To import all fonts, you can use:

```scss
body {
  font-family: 'Golos Text', sans-serif;
}
```

### Importing

```scss
@import "~@wikiline/webfont-golos-text/src/scss/all";
@import "~@wikiline/webfont-golos-text/src/scss/all-normal";
```

To import specific fonts, you can use:

```scss
@import "~@wikiline/webfont-golos-text/src/scss/weight-400";
@import "~@wikiline/webfont-golos-text/src/scss/weight-400-normal";
@import "~@wikiline/webfont-golos-text/src/scss/weight-500";
@import "~@wikiline/webfont-golos-text/src/scss/weight-500-normal";
@import "~@wikiline/webfont-golos-text/src/scss/weight-600";
@import "~@wikiline/webfont-golos-text/src/scss/weight-600-normal";
@import "~@wikiline/webfont-golos-text/src/scss/weight-700";
@import "~@wikiline/webfont-golos-text/src/scss/weight-700-normal";
@import "~@wikiline/webfont-golos-text/src/scss/weight-900";
@import "~@wikiline/webfont-golos-text/src/scss/weight-900-normal";
```

### Variables

Each font uses the following SCSS variables to set the font display property with the default `swap` value if SCSS
variables are not defined:

```scss
$font-display: swap;
$font-display-golos-text: swap;
```

## Licensing

It is important to always read the license for every font that you use. Most of the fonts in the collection use the SIL
Open Font License, v1.1. Some fonts use the Apache 2 license. The Ubuntu fonts use the Ubuntu Font License v1.0.
