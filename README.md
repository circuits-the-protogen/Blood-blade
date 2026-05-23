# Blood Blade — Omarchy Theme

A dark theme pulled from crimson ink, void black, deep-water teal, and bone white.
Inspired by the aesthetic of ink wash art and sumi-e brushwork.

## Colors

| Role               | Hex       |
|--------------------|-----------|
| Background         | `#0A0A0C` |
| Foreground         | `#EAE4D4` |
| Accent             | `#C41E1E` |
| Cursor             | `#EAE4D4` |
| Selection bg       | `#C41E1E` |
| Selection fg       | `#0A0A0C` |
| Red (blood)        | `#C41E1E` |
| Bright Red         | `#E8273A` |
| Teal               | `#2D7A6E` |
| Violet             | `#9090CC` |
| Amber              | `#C08040` |

## Install (Omarchy 3.3+)

```bash
# Option A — copy manually
cp -r omarchy-blood-blade-theme ~/.config/omarchy/themes/blood-blade
omarchy-theme-set blood-blade

# Option B — from this repo (if hosted on GitHub)
# Use Install > Style > Theme in the Omarchy menu (Super + Alt + Space)
# and paste the repo URL
```

## Wallpaper

Add your own backgrounds to the `backgrounds/` folder inside the theme directory.
Any `.jpg` or `.png` file placed there will be available via `Super + Ctrl + Space`.

The artwork that inspired this theme (a dark anime illustration with crimson ink
swirls and koi fish) works well as a wallpaper — place it in `backgrounds/` as
`01.jpg` or similar.

## Compatibility

Requires Omarchy 3.3+. The single `colors.toml` auto-generates configs for:
Ghostty · Alacritty · Kitty · btop · Hyprland · Hyprlock · Waybar · Mako ·
Walker · VS Code · Chromium/Brave · Obsidian
