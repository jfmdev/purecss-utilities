# PureCSS Utilities

A CSS library that provides utility CSS classes which complement [PureCSS](https://purecss.io/).

[See Demo](https://jfmdev.github.io/purecss-utilities/demo.html)

> Note: the library doesn't provide utilities for Flexbox containers, for that you can use the [Flexbox utility classes](https://gist.github.com/jfmdev/e3541b3d9e94866fe429b9baf89e6303) Gist.


## Installation

TODO (first publish on NPM and jsdelivr)


## Utilities

### Texts

You can set the text font size using classes `.pure-txt-xxs` / `.pure-txt-xs` / `.pure-txt-sm` / `.pure-txt-md` / `.pure-txt-lg` / `.pure-txt-xl` / `.pure-txt-xxl`.

You can define the text alignment using classes `.pure-txt-center` / `.pure-txt-justify` / `.pure-txt-left` / `.pure-txt-right`.

You can change the colors of texts using classes `.pure-txt-black` / `.pure-txt-blue` / `.pure-txt-cyan` / `.pure-txt-green` / `.pure-txt-magenta` / `.pure-txt-red` / `.pure-txt-white` / `.pure-txt-yellow`.

Additionally, you can modify the opacity of the colors the `pure-txt-alpha-*` class, where `*` can be replaced with numbers 10, 20, 25, 30, 40, 50, 60, 70, 75, 80 or 90.

TODO: Add support for links

### Background colors

You can change the colors of backgrounds using classes `.pure-bg-black` / `.pure-bg-blue` / `.pure-bg-cyan` / `.pure-bg-green` / `.pure-bg-magenta` / `.pure-bg-red` / `.pure-bg-white` / `.pure-bg-yellow`.

Additionally, you can modify the opacity of the colors the `pure-bg-alpha-*` class, where `*` can be replaced with numbers 10, 20, 25, 30, 40, 50, 60, 70, 75, 80 or 90.

### Borders

You can define borders using the class `.pure-bd-*`, where `*` can be any number between 1 and 5, defining the width (in pixels) of the border. By default the border will be solid and black.

To change the style of a border you can use classes `.pure-bd-solid` / `.pure-bd-dotted` / `.pure-bd-dashed`.

To change the color of a border you can use classes  `.pure-bd-black` / `.pure-bd-blue` / `.pure-bd-cyan` / `.pure-bd-green` / `.pure-bd-magenta` / `.pure-bd-red` / `.pure-bd-white` / `.pure-bd-yellow`.

Additionally, you can modify the opacity of the border colors using the `pure-bg-alpha-*` class, where `*` can be replaced with numbers 10, 20, 25, 30, 40, 50, 60, 70, 75, 80 or 90.

To set the radius of the border you can use classes `.pure-bd-radius-*` (where `*` can be any number between 1 and 5) / `.pure-bd-radius-circle` / `.pure-bd-radius-pill`.

### Buttons

TODO

### Opacity

The opacity of elements can be modified using the `.pure-opacity-*` class, where `*` can be replaced with numbers 10, 20, 25, 30, 40, 50, 60, 70, 75, 80 or 90.

### Spacing

The library provides `pure-m-*` and `pure-p-*` classes for controlling an element's margin or padding, where `*` can be replaced with any number between `1` and `8`.  

To set the margin or padding to a single side, you can use classes `pure-mb-*` / `pure-ml-*` / `pure-mr-*` / `pure-mt-*` and `pure-pb-*` / `pure-pl-*` / `pure-pr-*` / `pure-pt-*`; and to set the margin or padding to the horizontal or vertical sides, you can use classes `pure-mx-*` / `pure-my-*` and `pure-px-*` / `pure-py-*`.


## Customization

### Colors

The library uses variables `--pureBlack` / `--pureBlue` / `--pureCyan` / `--pureGreen` / `--pureMagenta` / `--pureRed` / `--pureWhite` / `--pureYellow` to define colors that later are used to define utility classes for texts, background, borders and buttons.

You can override these variables to change the colors used, but on that case you must also override the corresponding RBG variables: `--pureBlackRgb` / `--pureBlueRgb` / `--pureCyanRgb` / `--pureGreenRgb` / `--pureMagentaRgb` / `--pureRedRgb` / `--pureWhiteRgb` / `--pureYellowRgb`.

### Spacing

The base spacing used is `0.25rem`, but you can change this value by overriding the value of the `--pureSpacingUnit` variable.


## Development

The library was implemented using [Sass](https://sass-lang.com/), you can use the following commands to build it:

* `npm run build`
* `npm run dev`


## License

PureCSS Utilities is free software; you can redistribute it and/or modify it under the terms of the Mozilla Public License v2.0. You should have received a copy of the MPL 2.0 along with this software, otherwise you can obtain one at http://mozilla.org/MPL/2.0/.
