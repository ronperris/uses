# uses

## vscode

```json
{
  "workbench.startupEditor": "newUntitledFile",
  "workbench.editor.enablePreview": false,
  "workbench.colorTheme": "Dracula Soft",
  "editor.lightbulb.enabled": false,
  "editor.fontLigatures": false,
  "editor.rulers": [80],
  "editor.snippetSuggestions": "top",
  "editor.wordBasedSuggestions": false,
  "editor.suggest.localityBonus": true,
  "editor.acceptSuggestionOnCommitCharacter": false,
  "editor.acceptSuggestionOnEnter": "off",
  "editor.suggestSelection": "recentlyUsed",
  "editor.suggest.showKeywords": false,
  "workbench.statusBar.visible": true,
  "workbench.colorCustomizations": {
    "statusBar.background": "#000000"
  },
  "editor.fontSize": 16,
  "debug.console.fontSize": 16,
  "explorer.decorations.colors": false,
  "git.decorations.enabled": false,
  "terminal.integrated.fontSize": 16,
  "editor.minimap.enabled": false,
  "files.autoSave": "off",
  "javascript.updateImportsOnFileMove.enabled": "never",
  "editor.tabSize": 2,
  "editor.glyphMargin": false,
  "javascript.suggest.autoImports": false,
  "javascript.validate.enable": false,
  "workbench.panel.defaultLocation": "bottom",
  "explorer.openEditors.visible": 0,
  "debug.javascript.codelens.npmScripts": "never",
  "workbench.sideBar.location": "left",
  "spellright.language": ["en"],
  "spellright.documentTypes": ["markdown", "plaintext", "mdx"],
  "files.defaultLanguage": "{activeEditorLanguage}",
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": false
  },
  "eslint.validate": [
    "javascript",
    "javascriptreact",
    "typescript",
    "typescriptreact"
  ],
  "editor.folding": true,
  "search.exclude": {
    "**/.build": true,
    "**/.gh-pages": true,
    "**/.next": true,
    "**/bower_components": true,
    "**/build": true,
    "**/coverage": true,
    "**/dist": true,
    "**/node_modules": true
  },
  "files.exclude": {
    "USE_GITIGNORE": true
  },
  "editor.formatOnSave": true,
  "editor.hover.enabled": true,
  "editor.renderWhitespace": "boundary",
  "[yaml]": {
    "editor.insertSpaces": true,
    "editor.tabSize": 2,
    "editor.autoIndent": "none"
  },
  "[go]": {
    "editor.formatOnSave": true,
    "editor.insertSpaces": false,
    "editor.detectIndentation": false
  },
  "explorer.confirmDragAndDrop": false,
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.suggestSelection": "recentlyUsed",
    "editor.suggest.showKeywords": false
  },
  "editor.lineNumbers": "relative",
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.suggestSelection": "recentlyUsed",
    "editor.suggest.showKeywords": false
  },
  "explorer.confirmDelete": false,
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "editor.cursorStyle": "line",
  "editor.wordSeparators": "/\\()\"':,.;<>~!@#$%^&*|+=[]{}`?-",
  "editor.wordWrap": "off",
  "workbench.editorAssociations": {
    "*.ipynb": "jupyter.notebook.ipynb"
  },
  "redhat.telemetry.enabled": false,
  "terminal.integrated.shellIntegration.decorationsEnabled": "never",
  "editor.inlineSuggest.enabled": true,
  "[python]": {
    "editor.formatOnType": true
  },
  "chatgpt.apiKey": "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",
  "chatgpt.timeoutLength": 60,
  "github.copilot.enable": {
    "*": false,
    "plaintext": false,
    "markdown": true,
    "scminput": false
  },
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "git.openRepositoryInParentFolders": "never",
  "testing.defaultGutterClickAction": "debug",
  "workbench.activityBar.visible": false,
  "markdown.preview.fontSize": 16,
  "cody.autocomplete.enabled": false,
  "extensions.autoUpdate": "onlyEnabledExtensions",
  "window.zoomLevel": -1
}
```

### extensions

```
ban.spellright
bierner.github-markdown-preview
bierner.markdown-checkbox
bierner.markdown-emoji
bierner.markdown-footnotes
bierner.markdown-mermaid
bierner.markdown-preview-github-styles
bierner.markdown-yaml-preamble
christian-kohler.path-intellisense
cssho.vscode-svgviewer
dbaeumer.vscode-eslint
dracula-theme.theme-dracula
esbenp.prettier-vscode
felixfbecker.php-intellisense
formulahendry.auto-rename-tag
golang.go
keifukuda.stopwatch
kokororin.vscode-phpfmt
mikestead.dotenv
ms-azuretools.vscode-docker
ms-playwright.playwright
ms-python.black-formatter
ms-python.isort
ms-python.python
ms-python.vscode-pylance
ms-toolsai.jupyter
ms-toolsai.jupyter-keymap
ms-toolsai.jupyter-renderers
ms-toolsai.vscode-jupyter-cell-tags
ms-toolsai.vscode-jupyter-slideshow
ms-vscode-remote.remote-containers
ms-vscode.cmake-tools
ms-vscode.cpptools
ms-vscode.cpptools-extension-pack
ms-vscode.cpptools-themes
ms-vsliveshare.vsliveshare
nonylene.dark-molokai-theme
redhat.vscode-commons
redhat.vscode-yaml
sourcegraph.cody-ai
timkmecl.chatgpt
twxs.cmake
vscodevim.vim
waderyan.gitblame
wayou.vscode-todo-highlight
```

## hyper.js

```js
// Future versions of Hyper may add additional config options,
// which will not automatically be merged into this file.
// See https://hyper.is#cfg for all currently supported options.

module.exports = {
  config: {
    // choose either `'stable'` for receiving highly polished,
    // or `'canary'` for less polished but more frequent updates
    updateChannel: "stable",

    // default font size in pixels for all tabs
    fontSize: 16,

    // font family with optional fallbacks
    fontFamily: "DejaVu Sans Mono",

    // default font weight: 'normal' or 'bold'
    fontWeight: "normal",

    // font weight for bold characters: 'normal' or 'bold'
    fontWeightBold: "bold",

    // line height as a relative unit
    lineHeight: 1,

    // letter spacing as a relative unit
    letterSpacing: 0,

    // terminal cursor background color and opacity (hex, rgb, hsl, hsv, hwb or cmyk)
    cursorColor: "rgba(248,28,229,0.8)",

    // terminal text color under BLOCK cursor
    cursorAccentColor: "#000",

    // `'BEAM'` for |, `'UNDERLINE'` for _, `'BLOCK'` for █
    cursorShape: "BLOCK",

    // set to `true` (without backticks and without quotes) for blinking cursor
    cursorBlink: false,

    // color of the text
    foregroundColor: "#fff",

    // terminal background color
    // opacity is only supported on macOS
    backgroundColor: "#000",

    // terminal selection color
    selectionColor: "rgba(248,28,229,0.3)",

    // border color (window, tabs)
    borderColor: "#333",

    // custom CSS to embed in the main window
    css: "",

    // custom CSS to embed in the terminal window
    termCSS: "",

    // if you're using a Linux setup which show native menus, set to false
    // default: `true` on Linux, `true` on Windows, ignored on macOS
    showHamburgerMenu: "",

    // set to `false` (without backticks and without quotes) if you want to hide the minimize, maximize and close buttons
    // additionally, set to `'left'` if you want them on the left, like in Ubuntu
    // default: `true` (without backticks and without quotes) on Windows and Linux, ignored on macOS
    showWindowControls: false,

    // custom padding (CSS format, i.e.: `top right bottom left`)
    padding: "12px 14px",

    // the full list. if you're going to provide the full color palette,
    // including the 6 x 6 color cubes and the grayscale map, just provide
    // an array here instead of a color map object
    // colors: {
    //   black: "#000000",
    //   red: "#C51E14",
    //   green: "#1DC121",
    //   yellow: "#C7C329",
    //   blue: "#0A2FC4",
    //   magenta: "#C839C5",
    //   cyan: "#20C5C6",
    //   white: "#C7C7C7",
    //   lightBlack: "#686868",
    //   lightRed: "#FD6F6B",
    //   lightGreen: "#67F86F",
    //   lightYellow: "#FFFA72",
    //   lightBlue: "#6A76FB",
    //   lightMagenta: "#FD7CFC",
    //   lightCyan: "#68FDFE",
    //   lightWhite: "#FFFFFF",
    // },

    // the shell to run when spawning a new session (i.e. /usr/local/bin/fish)
    // if left empty, your system's login shell will be used by default
    //
    // Windows
    // - Make sure to use a full path if the binary name doesn't work
    // - Remove `--login` in shellArgs
    //
    // Bash on Windows
    // - Example: `C:\\Windows\\System32\\bash.exe`
    //
    // PowerShell on Windows
    // - Example: `C:\\WINDOWS\\System32\\WindowsPowerShell\\v1.0\\powershell.exe`
    shell: "",

    // for setting shell arguments (i.e. for using interactive shellArgs: `['-i']`)
    // by default `['--login']` will be used
    shellArgs: ["--login"],

    // for environment variables
    env: {},

    // set to `false` for no bell
    bell: "false",

    // if `true` (without backticks and without quotes), selected text will automatically be copied to the clipboard
    copyOnSelect: false,

    // if `true` (without backticks and without quotes), hyper will be set as the default protocol client for SSH
    defaultSSHApp: true,

    // if `true` (without backticks and without quotes), on right click selected text will be copied or pasted if no
    // selection is present (`true` by default on Windows and disables the context menu feature)
    quickEdit: false,

    // choose either `'vertical'`, if you want the column mode when Option key is hold during selection (Default)
    // or `'force'`, if you want to force selection regardless of whether the terminal is in mouse events mode
    // (inside tmux or vim with mouse mode enabled for example).
    macOptionSelectionMode: "vertical",

    // URL to custom bell
    // bellSoundURL: 'http://example.com/bell.mp3',

    // Whether to use the WebGL renderer. Set it to false to use canvas-based
    // rendering (slower, but supports transparent backgrounds)
    webGLRenderer: true,

    // for advanced config flags please refer to https://hyper.is/#cfg
  },

  // a list of plugins to fetch and install from npm
  // format: [@org/]project[#version]
  // examples:
  //   `hyperpower`
  //   `@company/project`
  //   `project#1.0.1`
  plugins: ["hyper-hide-title", "hyper-dracula"],

  // in development, you can create a directory under
  // `~/.hyper_plugins/local/` and include it here
  // to load it and avoid it being `npm install`ed
  localPlugins: ["hyper-whitespace"],

  keymaps: {
    // Example
    // 'window:devtools': 'cmd+alt+o',
  },
};
```
