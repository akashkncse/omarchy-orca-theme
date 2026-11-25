# Orca Theme for Omarchy

This starter uses Omarchy's stock Catppuccin palette. Edit `colors.toml` to make it your own. Start with `accent`, `background`, and `foreground`, then tune the terminal colors and their `bright_*` variants.

## Preview locally

Run these commands from the repository root. The symlink lets Omarchy read your edits directly from this checkout.

```bash
mkdir -p "$HOME/.config/omarchy/themes"
ln -sT "$PWD" "$HOME/.config/omarchy/themes/orca-theme"
omarchy theme set orca-theme
```

After editing the palette, run `omarchy theme set orca-theme` again. To add a wallpaper, create a `backgrounds/` directory and place an image inside it.
