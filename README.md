# Sakurazuki

A dark Omarchy theme with midnight plum backgrounds, sakura rose accents, blossom pink highlights, and moonlight lavender. The palette and wallpapers come from [Michal-Nithesh/Sakurazuki](https://github.com/Michal-Nithesh/Sakurazuki), packaged here as a standalone `colors.toml` theme.

![Sakura wallpaper](backgrounds/sakura.png)

## Install

On an Omarchy installation with `colors.toml` theme support:

```bash
omarchy theme install https://github.com/adamcbrewer/omarchy-sakurazuki-theme.git
```

This installs and applies the theme. To switch back to it later:

```bash
omarchy theme set sakurazuki
```

Cycle the two included wallpapers with:

```bash
omarchy theme bg next
```

Omarchy generates the terminal, editor, shell, and border colours from `colors.toml`. GTK applications keep Omarchy's standard dark appearance. The theme keeps your existing desktop layout, plugins, keybindings, and window behaviour.

There are no installer scripts or package dependencies, following the [minimal dependency principle](https://github.com/lirantal/npm-security-best-practices#14-reduce-your-package-dependency-tree).

## Palette

| Role | Colour |
| --- | --- |
| Background | `#14111A` |
| Secondary background | `#211925` |
| Surface / selection | `#2A1B2A` |
| Sakura rose | `#A87692` |
| Blossom pink | `#D9A6C4` |
| Moonlight lavender | `#C2AEDF` |
| Primary text | `#F0DCEB` |
| Secondary text | `#B8A3BB` |
| Muted text | `#88758F` |
| Border | `#443043` |

These are the desktop tokens documented in [Michal's customization guide](https://github.com/Michal-Nithesh/Sakurazuki/blob/90ca56ec0afb921ea1559a80979c8657f6bae514/docs/customization.md). Blossom pink and moonlight lavender map to bright magenta and bright blue. Other terminal accents come from the terminal palette bundled in that same repository. The two darkest background shades are derived from the plum base; the border gradient matches Michal's Hyprland look and feel.

## Wallpapers

- [Sakura](backgrounds/sakura.png)
- [Moonlit Valley Retreat](backgrounds/moonlit-valley-retreat.png)

Both are copied unchanged from [Michal-Nithesh/Sakurazuki](https://github.com/Michal-Nithesh/Sakurazuki). See [CREDITS.md](CREDITS.md) for the source revision and retained upstream licence.

## Credits and licence

Palette and wallpapers: [Michal-Nithesh/Sakurazuki](https://github.com/Michal-Nithesh/Sakurazuki).

The new theme definition and documentation are [MIT licensed](LICENSE). The source's MIT notice is retained separately in [LICENSES](LICENSES/Michal-Nithesh-Sakurazuki-MIT.txt).

Theme format: [Omarchy theming documentation](https://github.com/omacom/omarchy/blob/quattro/docs/theming.md).
