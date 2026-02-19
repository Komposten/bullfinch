# Bullfinch

Bullfinch is a theme based on [NightLion's Eclipse](https://github.com/eclipse-color-theme/eclipse-color-theme/blob/master/com.github.eclipsecolortheme/themes/nightlion-aptana-theme.xml) theme.

## Included themes

- Zed theme family: `zed-bullfinch.json`
  - `Bullfinch Dark`
  - `Bullfinch Muted Dark`
- Windows Terminal scheme: `windows-terminal-bullfinch.json`
- IntelliJ schemes:
  - `bullfinch.icls`
  - `bullfinch-muted.icls`

## Reference files

Reference assets used during theme creation are kept in `resources/`:

- Eclipse NightLion source theme
- IntelliJ Islands Dark reference scheme
- Zed schema and reference theme

## Usage

### Zed

1. Open the theme file and copy/import it into your Zed themes setup.
2. Select either `Bullfinch Dark` or `Bullfinch Muted Dark`.

### Windows Terminal

1. Open your Windows Terminal settings.
2. Merge the `schemes` entry from `windows-terminal-bullfinch.json`.
3. Set your profile `colorScheme` to `Bullfinch`.

### IntelliJ / JetBrains IDEs

1. Go to Editor > Color Scheme.
2. Import Scheme and select either:
  - `bullfinch.icls`
  - `bullfinch-muted.icls`

## Notes

- The muted variants are designed for lower color intensity while preserving theme identity.
- Diagnostic warning/error colors are intentionally separated for better readability.
