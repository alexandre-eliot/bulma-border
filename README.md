# Bulma Border

[![license](https://img.shields.io/badge/license-MIT-yellow.svg)](https://alexandre-eliot.github.io/bulma-border/) [![npm package](https://img.shields.io/npm/v/bulma-border.svg)](https://www.npmjs.org/package/bulma-border) [![downloads](https://img.shields.io/npm/dt/bulma-border.svg)](https://www.npmjs.com/package/bulma-border) [![size](https://img.shields.io/bundlephobia/minzip/bulma-border)](https://www.npmjs.com/package/bulma-border)

## Table of Contents

* [Quick Start](#quick-start)
* [How to use](#how-to-use)
* [Contributing](#contributing)
* [Contributors](#contributors)
* [Reporting Issues](#reporting-issues)
* [Licensing](#licensing)
* [Useful Links](#useful-links)

## Quick Start

### npm install

```shell script
# NPM
$ npm i bulma-radio --save
```

### yarn install

```shell script
# Yarn
yarn add bulma-border
```

### SCSS

Use with scss

```scss
/* Bulma Border */
@import "node_modules/bulma-border/bulma-border";
```

### JavaScript

```javascript
/* Bulma Border */
import 'bulma-border';
```

### CSS

Add the following line at the end of the head element on your HTML file

```html
<!-- Bulma Border -->
<link rel="stylesheet" href="https://unpkg.com/bulma-border"/>
```

## How to use

### Classes construction

```text
.has-border[-direction]?[-color]?[-style]?[-size]?
```

**Note** Neither of `direction`, `color` and `size` have to be supplied,
i.e. `.has-border-right` and `.has-border-black-6` are both valid

#### Directions

* `x` *that includes* `left` and `right`
* `y` *that includes* `top`, `bottom`

default: *all directions*

#### Colors

Bulma's original colors palette such as :
`white`, `black`, `light`, `dark`, `primary`, `link`, `info`, `success`, `warning` and `danger`

default: `primary`

#### Styles

Common css styling values :
`solid`, `dotted`, `dashed`, `double`, `groove`, `ridge`, `inset` and `outset`

default: `solid`

#### Sizes

Bulma's original sizes with three added sizes

```scss
$size-8: 0.5rem !default;
$size-9: 0.25rem !default;
$size-10: 0.125rem !default;
```

#### Defaults

```scss
/* border width */
$def-border-width: 125rem;
/* border color */
$def-border-color: $primary;
/* border style */
$def-border-style: solid;
```

### Examples

```text
.has-border-x-8
```

will translate into

```scss
border-left-width: 0.5rem;
border-left-color: hsl(171, 100%, 41%);
border-left-style: solid;
border-right-width: 0.5rem;
border-right-color: hsl(171, 100%, 41%);
border-right-style: solid;
```

```text
.has-border-left-success
```

will translate into

```scss
border-left-width: 0.125rem;
border-left-color: hsl(141, 53%,  53%);
border-left-style: solid;
```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am ':sparkles: feat: Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

**Note** Use of [Gitmoji](https://gitmoji.dev/) and [Semantic Commit Messages](https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716) are highly encouraged

## Contributors

* Maintainer - [@alexandre-eliot](https://github.com/alexandre-eliot)

## Reporting Issues

1. Make sure you are using the latest version of the package
2. Provide steps to reproduce
3. Provide an expected behavior
4. Describe what is actually happening
5. Platform, Browser & version as some issues may be browser specific

## Licensing

* Copyright &copy; 2021 [Alexandre Eliot](https://github.com/alexandre-eliot)
* Licensed under MIT

## Useful Links

* [Bulma](https://bulma.io)
* [Bulma Spacing](https://github.com/kaangokdemir/bulma-spacing)

### Changelog

See the [CHANGELOG.md](https://github.com/kaangokdemir/bulma-border/blob/master/CHANGELOG.md) file
