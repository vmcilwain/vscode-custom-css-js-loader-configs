# VSCode custom css and js loader files

## Description

These are config files to be used with [Custom CSS and JS Loader](https://github.com/be5invis/vscode-custom-css).

These files are a slightly modified copy of Josh Cirre's gist (as of 2025-05-16) which can be found below.

These were built with [Catppuccin for VSCode](https://github.com/catppuccin/vscode) theme and [Catppuccin Icons for VSCode](https://github.com/catppuccin/vscode-icons) icons in mind. If you decide to use with another theme, be sure to update the CSS colors to match.

## Installation

1. Clone or download this repo
2. Open up the command palette `(crlt | cmd) + p`
3. Select `Preferences: Open User Settings (JSON)`
4. Add the following:

```json
"vscode_custom_css.imports": [
  "file:///full/path/to/vscode-custom-css-js-loader-configs/css.css",
  "file:///full/path/to/vscode-custom-css-js-loader-configs/js.js",
]
```

## Additional Info

Josh Cirre's gist (as of 2025-05-16):

[https://gist.github.com/joshcirre/bf958a8636e2bdeaf484be5d0f49ba50](https://gist.github.com/joshcirre/bf958a8636e2bdeaf484be5d0f49ba50)

The corresponding Youtube video

[https://www.youtube.com/watch?v=axPTJq-Yfd0](https://www.youtube.com/watch?v=axPTJq-Yfd0)