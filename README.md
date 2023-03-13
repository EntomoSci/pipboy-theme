# Pipboy Theme

Theme inspired by the PipBoy of Fallout videogame series


## Font configuration

Following references of [this](https://fallout.fandom.com/wiki/Fonts_in_the_Fallout_series) fallout wiki, you can get a nice font configuration to complement PipBoy colors by:

1. Download and install [monofonto](https://typodermicfonts.com/monofonto/) font (for editor code).
2. Download and install [fixedsys](https://github.com/kika/fixedsys/) font (for integrated terminal).
3. Copy and paste the JSON below in your configuration file:

```
// PipBoy theme font configuration.
"editor.fontFamily": "Monofonto, Consolas, 'Courier New', monospace",
"editor.fontSize": 14,
"editor.letterSpacing": 0.5,
"terminal.integrated.fontSize": 15,
"terminal.integrated.lineHeight": 1.1,
"terminal.integrated.letterSpacing": 1.1,
"terminal.integrated.fontFamily": "Fixedsys Excelsior, monospace"
```
*This is only a default configuration. Feel free to adjust it to meet your preferences.*

## Troubleshoot

If the fonts aren't recognized after doing the steps described above, follow carefully the steps showed in the docs of each font and try again.
