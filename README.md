# Sakurazuki

A dark Omarchy theme with plum backgrounds, muted rose accents, and moonlit blue highlights. The palette comes from [Sakurazuki by ahmed-z0](https://github.com/ahmed-z0/omarchy-sakurazuki-theme), packaged here as a fresh `colors.toml` theme.

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
| Foreground | `#D8D0DC` |
| Accent | `#A87692` |
| Muted text | `#6B5E72` |
| Selection | `#2A2432` |
| Rose | `#8D5F74` |
| Slate | `#6F7B8F` |
| Lavender | `#9A84A2` |
| Mauve | `#947598` |
| Moonlit blue | `#7E95C1` |

The original palette supplies the base and bright colours. Darker surface shades are derived from the plum background. Selection uses a plum surface so selected text stays readable with Omarchy's generated foreground.

## Wallpapers

- [Sakura](backgrounds/sakura.png)
- [Moonlit Valley Retreat](backgrounds/moonlit-valley-retreat.png)

Both are copied unchanged from [Michal-Nithesh/Sakurazuki](https://github.com/Michal-Nithesh/Sakurazuki). See [CREDITS.md](CREDITS.md) for the source revision and retained upstream licence.

## Credits and licence

Palette inspiration: [ahmed-z0/omarchy-sakurazuki-theme](https://github.com/ahmed-z0/omarchy-sakurazuki-theme). Wallpapers: [Michal-Nithesh/Sakurazuki](https://github.com/Michal-Nithesh/Sakurazuki).

The new theme definition and documentation are [MIT licensed](LICENSE). The wallpaper source's MIT notice is retained separately in [LICENSES](LICENSES/Michal-Nithesh-Sakurazuki-MIT.txt).

Theme format: [Omarchy theming documentation](https://github.com/omacom/omarchy/blob/quattro/docs/theming.md).
