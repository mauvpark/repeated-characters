# repeated-characters README

This extension colorize characters each 3 characters.

## Preview

<p align="center">
  <img src="assets/preview.png" width="450" title="">
</p>

## Settings

`ctrl + shift + p` = > Open Settings(JSON)

```jsonc
{ 
    ...

    "editor.tokenColorCustomizations": {
        "textMateRules": [
            {
                "scope": "keyword.rc-quoted",
                "settings": {
                    "foreground": "#ffd900"
                }
            }
        ]
    }
}
```