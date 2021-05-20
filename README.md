## Description

 * A theme, inspired by Ironman
 * Small Tribute to Anthony Edward Stark
 * I love you 3000 :)

# Installation

1. Open **Extensions** sidebar panel in VS Code. `View → Extensions`
2. Search for `IronMan` - find the one by **SaiRohith** - there are a few other half-baked ones so make sure you have the right one!
3. Click **Install** to install it.
4. Code > Preferences > Color Theme > **IronMan**
5. Optional: Use the recommended settings below for best experience

## Recommended Settings

```js
{
  // This is all that matters
  "workbench.colorTheme": "IronMan",
  // The Cursive font is operator Mono, it's $200 and you need to buy it to get the cursive. Dank Mono or Victor Mono are good alternatives 
  "editor.fontFamily": "Operator Mono, Menlo, Monaco, 'Courier New', monospace,'cascadia code'",
  "editor.fontSize": 17,
  "editor.lineHeight": 25,
  "editor.letterSpacing": 0.5,
  "files.trimTrailingWhitespace": true,
  "editor.fontWeight": "400",
  "prettier.eslintIntegration": true,
  "editor.cursorStyle": "line",
  "editor.cursorWidth": 5,
  "editor.cursorBlinking": "solid",
  "editor.renderWhitespace": "all",
}
```
### Tweaks & theming

If you want to play around with new colors, use the setting
`workbench.colorCustomizations` to customize the currently selected theme. For
example, you can add this snippet in your "settings.json" file:

```json
"workbench.colorCustomizations": {
  "tab.activeBackground": "#282c34",
  "activityBar.background": "#282c34",
  "sideBar.background": "#282c34"
}
```

or use the setting `editor.tokenColorCustomizations`

```json
"editor.tokenColorCustomizations": {
  "[IronMan]": {
    "textMateRules": [
      {
        "scope": ["source.python"],
        "settings": {
          "foreground": "#e06c75"
        }
      }
    ]
  }
}
```
#### Italic 
You could set this in your setting.json to make code be italic
```json
"editor.tokenColorCustomizations": {
    "textMateRules": [
      {
        "name": "italic font",
        "scope": [
          "comment",
          "keyword",
          "storage",
          "keyword.control",
          "keyword.control.from",
          "keyword.control.flow",
          "keyword.operator.new",
          "keyword.control.import",
          "keyword.control.export",
          "keyword.control.default",
          "keyword.control.trycatch",
          "keyword.control.conditional",
          "storage.type",
          "storage.type.class",
          "storage.modifier.tsx",
          "storage.type.function",
          "storage.modifier.async",
          "variable.language",
          "variable.language.this",
          "variable.language.super",
          "meta.class",
          "meta.var.expr",
          "constant.language.null",
          "support.type.primitive",
          "entity.name.method.js",
          "entity.other.attribute-name",
          "punctuation.definition.comment",
          "text.html.basic entity.other.attribute-name",
          "tag.decorator.js entity.name.tag.js",
          "tag.decorator.js punctuation.definition.tag.js",
          "source.js constant.other.object.key.js string.unquoted.label.js",
        ],
        "settings": {
          "fontStyle": "italic",
        }
      },
    ]
  }
```

## Colours
Hot Rod Red : #aa0505
Dark Tan Red : #6a0c0b
Titanium Gold : #fbca03
Meteor Gold : #b97d10

### Author

Theme Created by -- Rohith

# [IronMan](https://marketplace.visualstudio.com/items?itemName=SaiRohith.Jarvis)
# [Butter](https://marketplace.visualstudio.com/items?itemName=SaiRohith.DarkButter)

  You can catch on :  [GITHUB](https://github.com/rohith1125)





