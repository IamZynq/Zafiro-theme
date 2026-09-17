# [Zafiro Theme](https://marketplace.visualstudio.com/items?itemName=zhuangtongfa.Material-theme)

## [GitHub Repository](https://github.com/IamZynq/Zafiro-theme)

**Language:** 🇺🇸 English · [🇪🇸 Español](./languages/README.es.md)

A dark color theme for Visual Studio Code with a crimson background and a high-contrast [palette](https://marketplace.visualstudio.com/search?target=VSCode&category=Themes&sortBy=Installs) for VS Code.

[![VS Code Marketplace](https://img.shields.io/badge/VS%20Code%20Marketplace-007ACC?style=for-the-badge\&logo=visual-studio-code\&logoColor=white)](https://marketplace.visualstudio.com/search?target=VSCode&category=Themes&sortBy=Installs)

## Screenshots

### ZafiroDark

![Screenshot](./Images/ZafiroDark.png)

### ZafiroPurple

![Screenshot](./Images/ZafiroPurple.png)

### ZafiroProto

![Screenshot](./Images/ZafiroProto.png)

## Markdown Preview Style

![Screenshot](./Images/Markdown.png)

I highly recommend installing the **Color Highlight** extension.

### Suggested Editor Settings

```json
"editor.fontSize": 20,
"editor.lineHeight": 30,
"editor.fontFamily": "JetBrains Mono",
```

**JetBrains Mono Download:**
https://www.jetbrains.com/lp/mono

### Code Example Colors

![Screenshot](./Images/bash.png)

![Screenshot](./Images/css.png)

![Screenshot](./Images/html.png)

## Donation

If you like this extension, you can support its development with a donation.

## Python & Pylance Users

For Python users, I recommend using the [Pylance](https://marketplace.visualstudio.com/items?itemName=ms-python.vscode-pylance) extension for fast, feature-rich language support.

The **Scope Inspector** tool allows you to explore which semantic tokens are present in a source file and which theme rules they match.

## Example of Customizing Semantic Colors in `settings.json`

```jsonc
{
  "editor.semanticTokenColorCustomizations": {
    "[One Dark Pro]": {
      // Apply to this theme only
      "enabled": true,
      "rules": {
        "magicFunction:python": "#ee0000",
        "function.declaration:python": "#990000",
        "*.decorator:python": "#0000dd",
        "*.typeHint:python": "#5500aa",
        "*.typeHintComment:python": "#aaaaaa",
        "parameter:python": "#aaaaaa"
      }
    }
  }
}
```

Please check the official documentation for more helpful information:

* [Theme Color Reference](https://code.visualstudio.com/docs/getstarted/theme-color-reference)
* [Themes](https://code.visualstudio.com/docs/getstarted/themes)
* [More Information](https://code.visualstudio.com/updates/v1_15#_user-definable-syntax-highlighting-colors)

## CHANGELOG

[CHANGELOG.md](https://github.com/IamZynq/Zafiro-theme/blob/main/CHANGELOG.md)

## DOCS & CONTRIBUTE

To help with documentation or contribute to the project, first fork and clone this repository.

Then navigate to the `ZAFIRO-THEME` folder:

```bash
cd ZAFIRO-THEME
```
