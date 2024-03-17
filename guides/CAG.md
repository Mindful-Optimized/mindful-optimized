# ⚒ Colorful Anvils
Allows you to format text with support for RGB colors, gradients, and many more! Simply rename items using tags.

## List of available tag

Colors

There are multiple tags representing colors.
They use their vanilla name.
```<yellow>, <dark_blue>, <dark_purple>, <gold>, <red>, <aqua>, <gray>, <light_purple>, <white>, <dark_gray>, <green>, <dark_green>, <blue>, <dark_aqua>, <dark_green>, <black>.```

There is also a universal `<color:[value]>` and `<c:[value]>` tags, in which you can replace `[value]` with a vanilla color name or an RGB color starting with # (for example `<color:#AABBCC>`)

**Decorations**
These tags allow decorating text.
`<strikethrough>/<st>` - Makes the text strikethrough.
`<underline>/<underlined>` - Underlines the text.
`<italic>/<i>` - Makes the text italic.
`<obfuscated>/<obf>` - Obfuscates the text (matrix effect).
`<bold>/<b>` - Makes the text bold.

**Fonts**
This tag allows you to change the font to any built-in one or one provided by a resource pack.
You can use it by simply adding `<font:[value]>`, where `[value]` is just a font name.
Minecraft has 3 built-in fonts: `default`, `uniform`, and `alt`.

**Gradients**
*This tag allows you to add gradients to the text.*
Types of gradients:
`<gradient:[color 1]:[color 2]:...>/<gr:[color 1]:[color 2]:...>` - Can take multiple colors to move between them smoothly.
`<hard_gradient:[color 1]:[color 2]:...>`/`<hgr:[color 1]:[color 2]:...>` - Can take multiple colors to move between them without mixing them.
`<rainbow:[frequency]:[saturation]:[offset]>`/`<rb:[...]>` - Simple rainbow gradient. All arguments are optional (<ranbow> is still valid) and they take numbers between 0 and 1 (0.3 for example).

**Reset**
`<reset>` and `<r>` are special, self-contained tags that close all previous formatting.
They are useful in cases where you want to close multiple formatting tags quickly.