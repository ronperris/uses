# uses

## vscode

```json
{
  "workbench.startupEditor": "newUntitledFile",
  "workbench.editor.enablePreview": false,
  "workbench.colorTheme": "Dark (Molokai)",
  "editor.lightbulb.enabled": false,
  "editor.fontLigatures": false,
  "editor.rulers": [
    80
  ],
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
  "editor.fontSize": 18,
  "debug.console.fontSize": 18,
  "workbench.activityBar.visible": false,
  "explorer.decorations.colors": false,
  "git.decorations.enabled": false,
  "terminal.integrated.fontSize": 18,
  "editor.minimap.enabled": false,
  "files.autoSave": "off",
  "editor.insertSpaces": true,
  "javascript.updateImportsOnFileMove.enabled": "never",
  "editor.tabSize": 2,
  "editor.glyphMargin": false,
  "javascript.suggest.autoImports": false,
  "javascript.validate.enable": false,
  "workbench.panel.defaultLocation": "bottom",
  "explorer.openEditors.visible": 0,
  "debug.javascript.codelens.npmScripts": "never",
  "workbench.sideBar.location": "left",
  "spellright.language": [
    "en"
  ],
  "spellright.documentTypes": [
    "markdown",
    "plaintext",
    "mdx"
  ],
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
  "eslint.options": {
    "env": {
      "browser": true,
      "jest/globals": true,
      "es6": true
    },
    "parserOptions": {
      "ecmaVersion": 2019,
      "sourceType": "module",
      "ecmaFeatures": {
        "jsx": true
      }
    },
    "rules": {
      "no-debugger": "off"
    }
  },
  "editor.folding": true,
  "search.exclude": {
    "**/node_modules": true,
    "**/bower_components": true,
    "**/coverage": true,
    "**/dist": true,
    "**/build": true,
    "**/.build": true,
    "**/.gh-pages": true
  },
  "files.exclude": {
    "USE_GITIGNORE": true
  },
  "editor.formatOnSave": true,
  "editor.hover.enabled": true,
  "editor.renderWhitespace": "boundary",
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
  "window.zoomLevel": -1
  // livestream
  /*
  "window.zoomLevel": 0,
  "editor.fontSize": 22,
  "terminal.integrated.fontSize": 20,
  "workbench.statusBar.visible": false,
  "editor.cursorBlinking": "solid",
  "explorer.decorations.colors": false,
  "explorer.decorations.badges": false,
  "editor.tokenColorCustomizations": {
    "textMateRules": []
  },
  "typescript.updateImportsOnFileMove.enabled": "never"
  /**/
  // egghead
  /*
  "editor.fontSize": 20,
  "terminal.integrated.fontSize": 15,
  "scm.diffDecorations": "none",
  "editor.lineNumbers": "off",
  "workbench.editor.showTabs": false,
  "workbench.statusBar.visible": false,
  "editor.cursorBlinking": "solid",
  "window.zoomLevel": 1,
  "breadcrumbs.enabled": false,
  "editor.parameterHints.enabled": false,
  "editor.suggestOnTriggerCharacters": false,
  "explorer.decorations.colors": false,
  "explorer.decorations.badges": false
  /**/
  // build react apps
  /*
  "editor.fontSize": 20,
  "terminal.integrated.fontSize": 15,
  "scm.diffDecorations": "none",
  "workbench.statusBar.visible": false,
  "editor.cursorBlinking": "solid",
  "window.zoomLevel": -1,
  "editor.parameterHints.enabled": false,
  "editor.suggestOnTriggerCharacters": false,
  "explorer.decorations.colors": false,
  "explorer.decorations.badges": false
  /**/
  // workshop
  /*
  "editor.fontSize": 22,
  "terminal.integrated.fontSize": 20,
  "scm.diffDecorations": "none",
  "workbench.statusBar.visible": false,
  "editor.cursorBlinking": "solid",
  "window.zoomLevel": 1,
  "workbench.colorTheme": "Night Owl Light",
  "explorer.decorations.colors": false,
  "explorer.decorations.badges": false,
  /**/
  // Talk
  /*
  "editor.fontSize": 22,
  "terminal.integrated.fontSize": 20,
  "scm.diffDecorations": "none",
  "editor.lineNumbers": "off",
  "workbench.statusBar.visible": false,
  "editor.cursorBlinking": "solid",
  "window.zoomLevel": 1,
  "workbench.colorTheme": "Night Owl Light",
  "breadcrumbs.filePath": "off",
  "breadcrumbs.symbolPath": "off",
  "editor.parameterHints.enabled": false,
  "editor.quickSuggestions": false,
  "editor.suggestOnTriggerCharacters": false,
  "explorer.decorations.colors": false,
  "explorer.decorations.badges": false,
  /**/
}
```

### extensions

```
2gua.rainbow-brackets
ban.spellright
bierner.github-markdown-preview
bierner.markdown-checkbox
bierner.markdown-emoji
bierner.markdown-preview-github-styles
bierner.markdown-yaml-preamble
cssho.vscode-svgviewer
dbaeumer.vscode-eslint
eg2.tslint
esbenp.prettier-vscode
felixfbecker.php-intellisense
formulahendry.auto-rename-tag
golang.go
keifukuda.stopwatch
kokororin.vscode-phpfmt
mikestead.dotenv
ms-azuretools.vscode-docker
ms-vscode-remote.remote-containers
ms-vsliveshare.vsliveshare
nonylene.dark-molokai-theme
redhat.vscode-yaml
vscodevim.vim
waderyan.gitblame
wayou.vscode-todo-highlight
```

## hyper.js

```js
module.exports = {
  config: {
    updateChannel: "stable",
    fontSize: 18,
    fontFamily: "DejaVu Sans Mono",
    fontWeight: "normal",
    fontWeightBold: "bold",
    lineHeight: 1,
    letterSpacing: 0,
    cursorColor: "rgba(248,28,229,0.8)",
    cursorAccentColor: "#000",
    cursorShape: "BLOCK",
    cursorBlink: false,
    foregroundColor: "#fff",
    backgroundColor: "#000",
    selectionColor: "rgba(248,28,229,0.3)",
    borderColor: "#333",
    css: "",
    termCSS: "",
    showHamburgerMenu: "",
    showWindowControls: false,
    padding: "12px 14px",
    colors: {
      black: "#000000",
      red: "#C51E14",
      green: "#1DC121",
      yellow: "#C7C329",
      blue: "#0A2FC4",
      magenta: "#C839C5",
      cyan: "#20C5C6",
      white: "#C7C7C7",
      lightBlack: "#686868",
      lightRed: "#FD6F6B",
      lightGreen: "#67F86F",
      lightYellow: "#FFFA72",
      lightBlue: "#6A76FB",
      lightMagenta: "#FD7CFC",
      lightCyan: "#68FDFE",
      lightWhite: "#FFFFFF",
    },
    shell: "",
    shellArgs: ["--login"],
    env: {},
    bell: "false",
    copyOnSelect: false,
    defaultSSHApp: true,
    quickEdit: false,
    macOptionSelectionMode: "vertical",
    webGLRenderer: true,
  },
  plugins: ["hyperterm-monokai", "hyper-hide-title"],
  localPlugins: [],
  keymaps: {},
};
```
