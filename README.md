# Vaka

A minimal blog theme powered by [Hugo](https://gohugo.io).
Based on Calin Tataru's theme [Minimal](https://github.com/calintat/minimal)

## Installation

```
$ git clone https://github.com/oneleaftea/vaka.git
```

## Features

You can tweak the look of the theme to suit your needs in a number of ways:

- The accent colour can be changed by using the `accent` field in `config.toml`.

- You can also change the background colour by using `backgroundColor`.

- Add colored 5px borders at the top and bottom of pages by setting `showBorder` to `true`.

For best results, I recommend you use a dark accent colour with a light background, for example:

```toml
[params]
    accent = "red"
    showBorder = true
    backgroundColor = "white"
```

### Fonts

The theme uses [Google Fonts](https://fonts.google.com) to load its font. To change the font:

```toml
[params]
    font = "Raleway" # should match the name on Google Fonts!
```
