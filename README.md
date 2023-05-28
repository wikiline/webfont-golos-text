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

CSS files are located in the `root` directory:

* `all-normal.css`
* `all-normal.min.css`
* `400-normal.css`
* `400-normal.min.css`
* `500-normal.css`
* `500-normal.min.css`
* `600-normal.css`
* `600-normal.min.css`
* `700-normal.css`
* `700-normal.min.css`
* `900-normal.css`
* `900-normal.min.css`

Font files are located in the `fonts/` directory.

### Importing

To import all fonts, you can use:

```css
@import "~@wikiline/webfont-golos-text/all-normal.css";
@import "~@wikiline/webfont-golos-text/all-normal.min.css";
```

To import specific fonts, you can use:

```css
@import "~@wikiline/webfont-golos-text/400-normal.css";
@import "~@wikiline/webfont-golos-text/400-normal.min.css";
@import "~@wikiline/webfont-golos-text/500-normal.css";
@import "~@wikiline/webfont-golos-text/500-normal.min.css";
@import "~@wikiline/webfont-golos-text/600-normal.css";
@import "~@wikiline/webfont-golos-text/600-normal.min.css";
@import "~@wikiline/webfont-golos-text/700-normal.css";
@import "~@wikiline/webfont-golos-text/700-normal.min.css";
@import "~@wikiline/webfont-golos-text/900-normal.css";
@import "~@wikiline/webfont-golos-text/900-normal.min.css";
```

```css
body {
    font-family: 'Golos Text', sans-serif;
}
```

### Variables

Each font uses the following CSS variables to set the font display property with the default `swap` value if CSS
variables are not defined:

* `--font-display` global value applicable to all fonts
* `--font-display-golos-text` the value applicable to a specific font

```css
:root {
    --font-display: swap;
    --font-display-golos-text: swap;
}
```

## Licensing

It is important to always read the license for every font that you use. Most of the fonts in the collection use the SIL
Open Font License, v1.1. Some fonts use the Apache 2 license. The Ubuntu fonts use the Ubuntu Font License v1.0.
