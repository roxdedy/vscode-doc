### Recommended Settings

#### Editor settings

```
    "editor.codeLens": false,
    "editor.renderWhitespace": "none",
    "editor.autoIndent": true,
    "editor.fontSize": 14,
    "editor.fontFamily": "Inconsolata, Fira code",
    "editor.formatOnPaste": false,
    "editor.formatOnType": true,
    "editor.letterSpacing": 1,
    "editor.tabSize": 2,
    "editor.wordWrap": "off"
```

#### File settings

```
    "files.autoSave": "afterDelay",
    "files.autoSaveDelay": 2000,
    "files.exclude": {
        "**/.git": true,
        "**/.DS_Store": true,
        "**/*.js": {
            "when": "$(basename).ts"
        },
        "**/*.js.map": {
            "when": "$(basename)"
        }
    },
    "files.hotExit": "onExit",
    "files.defaultLanguage": "typescript",
    "files.trimTrailingWhitespace": true,
```

#### Prettier settings

```
    "prettier.singleQuote": true,
    "prettier.printWidth": 100,
```
