# vscode-settings

- `settings.json` file for VSCode.

macOS:

```json
{
    "workbench.colorTheme": "Community Material Theme Ocean High Contrast",
    "workbench.iconTheme": "material-icon-theme",
    "editor.formatOnSave": true,
    "editor.fontFamily": "Fira Code",
    "editor.fontLigatures": true,
    "editor.minimap.enabled": false,
    "editor.renderWhitespace": "none",
    "breadcrumbs.enabled": false,
    "prettier.singleQuote": false,
    "prettier.tabWidth": 4,
    "prettier.printWidth": 160,
    "javascript.updateImportsOnFileMove.enabled": "always",
    "emmet.excludeLanguages": ["markdown"],
    "editor.codeActionsOnSave": {
        "source.fixAll": true,
        "source.fixAll.eslint": true
    },
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "[javascript]": {
        "editor.defaultFormatter": "esbenp.prettier-vscode"
    },
    "git.enableSmartCommit": true,
    "bracketPairColorizer.activeScopeCSS": ["borderStyle : solid", "borderWidth : 1px", "borderColor : {color}; opacity: 0.5"],
    "files.autoSave": "onFocusChange",
    "editor.find.autoFindInSelection": "always",
    "explorer.confirmDelete": false,
    "tabnine.experimentalAutoImports": true,
    "explorer.confirmDragAndDrop": false,
    "auto-close-tag.activationOnLanguage": [
        "xml",
        "php",
        "blade",
        "ejs",
        "jinja",
        "javascript",
        "javascriptreact",
        "typescript",
        "typescriptreact",
        "plaintext",
        "markdown",
        "vue",
        "liquid",
        "erb",
        "lang-cfml",
        "cfml",
        "HTML (EEx)",
        "HTML (Eex)",
        "plist"
    ],
    "typescript.updateImportsOnFileMove.enabled": "always",
    "terminal.integrated.shell.osx": "bash"
}
```

Windows/WSL:

```json
{
    "workbench.colorTheme": "Material Theme Ocean High Contrast",
    "workbench.iconTheme": "material-icon-theme",
    "editor.formatOnSave": true,
    "editor.fontLigatures": true,
    "editor.fontSize": 13,
    "editor.minimap.enabled": false,
    "editor.renderWhitespace": "none",
    "breadcrumbs.enabled": false,
    "prettier.singleQuote": false,
    "prettier.tabWidth": 4,
    "javascript.updateImportsOnFileMove.enabled": "always",
    "emmet.excludeLanguages": ["markdown"],
    "editor.codeActionsOnSave": {
        "source.fixAll": true,
        "source.fixAll.eslint": true
    },
    "git.enableSmartCommit": true,
    "bracketPairColorizer.activeScopeCSS": [
        "borderStyle : solid",
        "borderWidth : 1px",
        "borderColor : {color}; opacity: 0.5"
    ],
    "files.autoSave": "onFocusChange",
    "editor.find.autoFindInSelection": "always",
    "window.zoomLevel": 0,
    "explorer.confirmDelete": false,
    "tabnine.experimentalAutoImports": true,
    "explorer.confirmDragAndDrop": false,
    "auto-close-tag.activationOnLanguage": [
        "xml",
        "php",
        "blade",
        "ejs",
        "jinja",
        "javascript",
        "javascriptreact",
        "typescript",
        "typescriptreact",
        "plaintext",
        "markdown",
        "vue",
        "liquid",
        "erb",
        "lang-cfml",
        "cfml",
        "HTML (EEx)",
        "HTML (Eex)",
        "plist"
    ]
}
```

Linux/Ubuntu/Debian:

```
```
