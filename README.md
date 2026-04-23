# PragmataPro

## Settings

Das gewünschte Font kann ganz einfach über den Namen eingebunden werden:

> [!info] Font Ligaturen
> Fonts mit dem Zusatz `Liga` unterstützen Ligaturen wie "Frakturen" usw.
> Diese können über "Font Features" aktiviert werden.

```json settings.json
{
  "font-family": "'PragmataPro Liga', 'PragmataPro', 'PragmataPro Mono Liga', 'PragmataPro Mono'"
}
```

### Visual Studio Code

```json
{
  "editor.fontSize": 14,

  // Set the font

  "editor.fontFamily": "'PragmataPro Mono Liga', 'JetBrains Mono NL', '72 Monospace Bold', Consolas, 'Courier New', monospace",

  // Turn on font ligatures

  "editor.fontLigatures": "'ss03'",

  // Set letter spacing

  "editor.letterSpacing": 0.7,

  "terminal.integrated.fontFamily": "'PragmataPro Mono Liga', 'JetBrains Mono NL', '72 Monospace Bold', Consolas, 'Courier New', monospace",

  "terminal.integrated.fontSize": 13
}
```

### Ghostty

- [Ghostty Font Features](https://ghostty.org/docs/config/reference#font-feature)

```txt
font-family="PragmataPro Mono Liga"
font-feature=+liga,ss03
```

## Font Features

Das Font unterstützt viele sogenannte "Font Features" welche helfen bestimmte Schriftarten oder Ligaturen freizuschalten. Eine vollständige Übersicht gibt es im ["Handbook"](./Handbook.opng)

- Fraktur = `ss03`
- Fraktur (Fett" = `ss04`
- Git Tree = `ss13`
- Type Pills = `ss15`
- Komische Schrift = `ss16`
- Badges = `ss18`
- Pills = `ss20`
- 
