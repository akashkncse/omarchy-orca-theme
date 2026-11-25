# Orca Theme for Omarchy

A dark Omarchy theme inspired by black-and-white orcas, blue water, and misty evergreen shores. Edit `colors.toml` to customize the palette.

## Preview locally

Run these commands from the repository root. The symlink lets Omarchy read your edits directly from this checkout.

```bash
mkdir -p "$HOME/.config/omarchy/themes"
ln -sT "$PWD" "$HOME/.config/omarchy/themes/orca-theme"
omarchy theme set orca-theme
```

After changing the palette, run `omarchy theme set orca-theme` again. Use `omarchy theme bg next` to cycle through the three wallpapers in `backgrounds/`.

- `00-orca-breach-4k.jpg` depicts an orca breaching in a misty Pacific Northwest fjord. It was created with the built-in image generation tool and upscaled from 1672 × 941 to 3840 × 2160.
- `1.jpg` and `2.jpg` are the original reference photos.

## Wallpaper generation prompt

> Generate an epic photorealistic wildlife desktop wallpaper in 16:9 at 3840 × 2160 if supported. Use the two orca photos as mood and color references: vivid blue churning water from the first, misty evergreen shoreline and cool gray sky from the second. A single anatomically accurate black-and-ivory orca breaches above a deep Pacific Northwest fjord, slightly right of center, with crisp arcs of silvery spray. Low water-level viewpoint, layered evergreen headlands under cloud, subtle shafts of cool light, deep ink-blue shadows, cold ocean blues and pale seafoam. Keep the top edge and left side relatively quiet for desktop UI. Frame the whole animal and main spray comfortably for 16:9 cropping. Natural wildlife photography, cinematic scale, fine water texture. No text, logos, borders, or people.
