# rices

A collection of desktop rices for Omarchy (Hyprland-based desktop framework).

## Omarchy Themes

### Hermes
![Hermes theme preview](hermes/preview.png)

A dark obsidian + golden amber theme for Omarchy.

- **Background**: `#0a0a0f`
- **Accent**: `#e0a526`
- **Foreground**: `#d4c8a0`

#### Install
Copy the `hermes/` directory into `~/.local/share/omarchy/themes/` or `~/.config/omarchy/themes/`, then:

```bash
omarchy theme set hermes
```

#### Files
- `colors.toml` — Theme color definitions
- `wallpaper.png` — Default wallpaper
- `backgrounds/` — Additional wallpapers
- `preview.png` — Theme preview (1800x1012)
- `preview-unlock.png` — Lock screen preview (1920x1080)
- `unlock.png` — Unlock banner (800x188)
- `hyprland.conf`, `hyprlock.conf`, `waybar.css` — Hyprland/Waybar styling
- `alacritty.toml`, `kitty.conf`, `ghostty.conf` — Terminal colors
- `neovim.lua`, `vscode.json` — Editor themes
- `btop.theme`, `mako.ini`, `swayosd.css`, `walker.css` — App theming
