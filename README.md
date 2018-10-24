# VS Code Pitch Black Monokai Color Theme

All backgrounds and unnecessary borders are black and are taken from the [Pitch Black](https://github.com/ViktorQvarfordt/vscode-pitch-black-theme/blob/master/themes/pitch-black-color-theme.json) theme. Syntax highlighting colors are taken from the [Monokai](https://github.com/Microsoft/vscode/blob/master/extensions/theme-monokai/themes/monokai-color-theme.json) theme.


## Settings

Some features cannot be enabled automatically by this extension. In the user settings, set the following.

- Black title bar: `"window.titleBarStyle": "custom"`
- Remove highlighting of tab lines etc: `"workbench.colorCustomizations": { "editorWhitespace.foreground": "#000" }`
- Remove line next to scroll bar: `"editor.overviewRulerBorder": false`


## Manual Install

```
cd ~/.vscode/extensions
git clone https://github.com/henrikdahlberg/pitch-black-monokai.git pitch-black-monokai
```
