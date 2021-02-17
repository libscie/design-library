# Design library <img src="https://raw.githubusercontent.com/libscie/design/main/libscie-logomark-1024-square.png" align="right" height="64" />
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-1-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

This repository helps standardize way designs are implemented across liberate science projects. This makes it easier to propagate any changes to the design system, by simply updating this library.

## Usage

```sh
npm install @libscie/design-library
```

```js
const libscie = require('@libscie/design-library')
// If you want to import only specific parts of the design library
const {
    colors
} = require('@libscie/design-library')
```

## Colors

```js
const background = libscie.colors.purple900
const alternatively = colors.purple900
```

![Color library cheatsheet](./color-cheatsheet.png)

The name is the base color; the number indicates the XXX. The only exception is `white`, which replaces `mono100`.
## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="http://sobrakseaton.com"><img src="https://avatars.githubusercontent.com/u/28573875?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Patrick Sobrak-Seaton</b></sub></a><br /><a href="#design-psobrakseaton" title="Design">🎨</a></td>
  </tr>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!