# Sequoia Dark for Omarchy

A warm, inviting, and modern dark theme for [Omarchy](https://omarchy.org).
Includes uniform styling across nvim, btop and vs-code.

## Preview

![Sequoia Dark](./preview.png)

## Installation

In your terminal of choice paste the following link:

```text
omarchy theme install https://github.com/agworkgit/omarchy-sequoia-dark-theme
```

Or via the Omarchy menu `SUPER + SPACE`, Install > Style > Theme

```text
https://github.com/agworkgit/omarchy-sequoia-dark-theme
```

### VS Code Theme

```
Name: Sequoia Dark
Id: agworkgit.sequoia-dark
Description: A dark VS Code theme with warm amber, neon green, blue and purple accents that matches the Sequoia Dark Omarchy theme.
Version: 1.0.0
Publisher: agworkgit
```

#### Installation

Launch VS Code Quick Open (Ctrl+P), paste the following command, and press enter.

```text
ext install AlexGrigore.sequoia-dark
```

## Main Background

Who knows where the road might lead you...
Feel free to check the other backgrounds I included, all themed around the Big Sur coastline and roads.

![Main Background](./backgrounds/sequoia-bends.png)

## Colour Palette

| Type       | Colour  |
| ---------- | ------- |
| Background | #1d1d20 |
| Accent     | #ffbb88 |
| Green      | #92fd9b |
| Yellow     | #fff885 |
| Blue       | #82aeff |
| Magenta    | #a27fff |
| Cyan       | #00f489 |
| Foreground | #ffeed2 |

## Limitations

No neovim.lua or vscode.json: those pin a named upstream colorscheme plugin rather than reading colors.toml, and no published scheme matches this palette. Both applications fall back to Omarchy's defaults. 

If you would like to get uniform colours across LazyVim and VS Code some of the files need to be placed in the theme directory manually, the process is simple, clone the repo separately and move the `btop.theme` and `neovim.lua` to your local theme directory at `~/.config/omarchy/themes/sequoia-dark`
