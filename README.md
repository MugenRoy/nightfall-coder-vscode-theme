<br>

<div align="center">
  <img src="https://raw.githubusercontent.com/MugenRoy/nightfall-coder-vscode-theme/main/icon.png" alt="logo" width="150" height="150">

<br>

# [Nightfall Coder](https://marketplace.visualstudio.com/items?itemName=mugen.nightfall-coder) <br> <br>
</div>

<div align="center">

[![Preview in vscode.dev](https://img.shields.io/badge/preview%20in-vscode.dev-blue)](https://vscode.dev/theme/mugen.nightfall-coder/Nightfall%20Coder)

</div>
This theme is designed to :

-   _Provide_ excellent contrast and reduce eye strain during long coding sessions, especially in low-light conditions.
-   _Ensure_ a balanced color scheme, offering a visually appealing coding experience.
-   _Work_ with common languages like JavaScript_, Python, C++ and more.
-   _Fully support_ VS Code's Bracket Pair Colorization feature, making it easy to visually distinguish nested code blocks.

## Showcase ( Simple Snippet )

![Screenshot](https://raw.githubusercontent.com/MugenRoy/nightfall-coder-vscode-theme/main/images/javascript.png)

Font used in the snippet is [JetBrains Mono.](https://www.jetbrains.com/lp/mono/)

## Installation

1. Open VS Code.
2. Go to Extensions (`Ctrl+Shift+X` or `Cmd+Shift+X` on macOS).
3. Search for "Nightfall Coder".
4. Click Install.
5. Press `Ctrl+K`, `Ctrl+T` (or `Cmd+K`, `Cmd+T` on macOS) to open the theme selector.
6. Select "Nightfall Coder".

Alternatively, you can install it directly from the [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=mugen.nightfall-coder).


## Disabling Italics
Paste this into your [settings.json](https://code.visualstudio.com/docs/getstarted/settings#_settings-file-locations) to disable italics.

```javascript
"editor.tokenColorCustomizations": {
    "[Nightfall Coder]": { 
        "textMateRules": [{
            "scope": [
                "keyword.control",
                "keyword.other",
                "storage.type", 
                "storage.modifier", 
                "storage.control",
            ],
            "settings": {
                "fontStyle": ""
            }
        }]
    }
}
```

## Basic Color Palette

 Color                                                                                      | Used for:                                                 |
 --------------------------------------------------------------------------------------------- | --------------------------------------------------------- |
![#E4B1F0](https://www.colorbook.io/imagecreator.php?hex=E4B1F0&width=15&height=15) `#E4B1F0` | Strings                                                   |  
![#6D6D6D](https://www.colorbook.io/imagecreator.php?hex=6D6D6D&width=15&height=15) `#6D6D6D` | Comments                                                  |
![#AAA0FA](https://www.colorbook.io/imagecreator.php?hex=AAA0FA&width=15&height=15) `#AAA0FA` | Functions                                                 |
![#DEC76E](https://www.colorbook.io/imagecreator.php?hex=DEC76E&width=15&height=15) `#DEC76E` | Numbers                                             |
![#83D6C5](https://www.colorbook.io/imagecreator.php?hex=83D6C5&width=15&height=15) `#83D6C5` | Keywords                                                  |
![#68a9dd](https://www.colorbook.io/imagecreator.php?hex=68a9dd&width=15&height=15) `#68a9dd` | Operators                                                 |
![#db4b4b](https://www.colorbook.io/imagecreator.php?hex=db4b4b&width=15&height=15) `#db4b4b` | Error                                                     |
![#a9b1d6](https://www.colorbook.io/imagecreator.php?hex=a9b1d6&width=15&height=15) `#a9b1d6` | Variables & Parameters                                   |

<br>

<div align="center"> 

## License

[Apache 2.0 © 2025 Shaswata Roy](./LICENSE)

**Try it out!**

</div>