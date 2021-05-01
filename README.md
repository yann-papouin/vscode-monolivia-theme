# Monolivia

A theme made to mimic the Monodevelop Oblivion Theme.
It is essentially compatible with C# language keywords defined by Omnisharp. 

* [Github repo](https://github.com/yann-papouin/vscode-monolivia-theme)

## Screenshot
---
![Dark Theme](https://raw.githubusercontent.com/yann-papouin/vscode-monolivia-theme/master/media/monolivia.png)

If you have any change requests feel free to create an issue [here](https://github.com/yann-papouin/vscode-monolivia-theme/issues).

Initial theme based on [Blackboard TextMate Theme](http://colorsublime.com/theme/Blackboard).

## How-To

To quickly identify the selection, bind the `Developer: Inspecter Editor Tokens and Scopes` action. It's a lot easier to create/edit a theme with this
action shortcut.

```
    {
        "key": "ctrl+shift+i",
        "command": "editor.action.inspectTMScopes",
        "when": "editorTextFocus"
    }
```