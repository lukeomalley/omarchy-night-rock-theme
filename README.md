# Night Rock for Omarchy

A deep blue-black Omarchy theme with warm, muted Gruvbox-inspired colors.
Night Rock uses `#08080d` as its base, `#d4be98` for text, and restrained
red, orange, yellow, green, aqua, blue, and purple accents.

## Install

```bash
omarchy theme install https://github.com/lukeomalley/omarchy-night-rock-theme.git
```

Omarchy installs and activates the theme automatically. Switch back to it later
with:

```bash
omarchy theme set night-rock
```

## Frosted desktop appearance

The theme supplies translucent charcoal shell surfaces, soft white labels,
warm selection accents, subtle outlines, and roomier panel spacing.

For the matching desktop appearance, use the accompanying
[Hyprland settings](https://github.com/lukeomalley/dotfiles/blob/feat/cross-platform-dotfiles/stow/omarchy/hypr/.config/hypr/looknfeel.lua):
10px corners, compact gaps, soft window shadows, and shell-layer blur.
In `~/.config/omarchy/shell.json`, set `bar.transparent` to `false` so the
bar uses the theme's translucent background instead of being fully transparent.
These desktop settings are separate from the theme install; custom menu and
clipboard plugins are also provided by the dotfiles.

After pulling theme updates, reapply with `omarchy theme set night-rock`.

## Source

This installable repository is published from the canonical Night Rock project:
[lukeomalley/dark-rock-theme](https://github.com/lukeomalley/dark-rock-theme/tree/main/omarchy/night-rock).

## Palette

| Role | Color |
| --- | --- |
| Background | `#08080d` |
| Foreground | `#d4be98` |
| Red | `#ea6962` |
| Orange | `#e78a4e` |
| Yellow | `#d8a657` |
| Green | `#a9b665` |
| Aqua | `#89b482` |
| Blue | `#7daea3` |
| Purple | `#d3869b` |

## License

MIT
