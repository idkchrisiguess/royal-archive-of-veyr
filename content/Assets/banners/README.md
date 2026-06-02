# Homepage Banner Images

Place banner images in this folder to display on the site homepage hero.

## Supported formats

- `.jpg`
- `.jpeg`
- `.png`
- `.webp`

## Behavior

- Images are discovered automatically at build time — no configuration required.
- If multiple images exist, one is chosen at random on each page load.
- If this folder is empty, the homepage displays a graceful parchment fallback.

## Recommendations

- Use landscape images at least 1600×900 pixels.
- Keep file sizes under 500 KB when possible for fast loading.
- Choose atmospheric fantasy art: kingdom vistas, royal halls, illuminated manuscripts.

## Example

```
content/assets/banners/
  hall-at-dusk.webp
  crown-chamber.jpg
  veyr-coastline.png
```

After adding images, rebuild the site:

```bash
npx quartz build
```
