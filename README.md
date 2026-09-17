# [Zafiro-Theme](https://marketplace.visualstudio.com/items?itemName=zhuangtongfa.Material-theme)

## [GitHub Repo](https://github.com/IamZynq/Zafiro-theme) 

A dark color theme for Visual Studio Code with a crimson background and a high-contrast [palette](https://marketplace.visualstudio.com/search?target=VSCode&category=Themes&sortBy=Installs) for VS Code! 



[![VS Code Marketplace](https://img.shields.io/badge/VS%20Code%20Marketplace-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)](https://marketplace.visualstudio.com/search?target=VSCode&category=Themes&sortBy=Installs)

## SCREENSHOT
SafiroDark
![ScreenShot](/Images/ZafiroDark.png)
SafiroPurple
![ScreenShot](/Images/ZafiroProto.png)
SafiroProto
![ScreenShot](/Images/ZafiroPurple.png)






## Markdown preview style

![ScreenShot](/Images/Markdown.png)
 I highly recommend installing Color Highlight extension.


### Suggest Editor Settings
```
 "editor.fontSize": 20,
 "editor.lineHeight": 30,
 "editor.fontFamily": "JetBrains Mono",
```
JetBrains Mono Download: https://www.jetbrains.com/lp/mono

### code example colors

![ScreenShot](/Images/bash.png)
![ScreenShot](/Images/css.png)
![ScreenShot](/Images/html.png)
## Donation

If you like this extension, you could donate 


## Python & Pylance users
Python users I recommend using [Pylance](https://marketplace.visualstudio.com/items?itemName=ms-python.vscode-pylance) extension for fast, feature-rich language support.





The [scope inspector](https://code.visualstudio.com/api/language-extensions/syntax-highlight-guide#scope-inspector) tool allows you to explore what semantic tokens are present in a source file and what theme rules they match to.

## Example of customizing semantic colors in settings.json:

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

Please check the official documentation,
[Theme Color Reference](https://code.visualstudio.com/docs/getstarted/theme-color-reference) and
[Theme Color](https://code.visualstudio.com/docs/getstarted/themes), for more helpful information.

[More info](https://code.visualstudio.com/updates/v1_15#_user-definable-syntax-highlighting-colors)

## CHANGELOG

[CHANGELOG.MD](https://github.com/IamZynq/Zafiro-theme/blob/main/CHANGELOG.md)

## DOCS & CONTRIBUTE



To help with documentation, first fork and clone this repository.

`cd` to the `ZAFIRO-THEME` folder









