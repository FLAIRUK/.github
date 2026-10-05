# FLAIR brand

The FLAIR wordmark, redrawn as vector artwork from the original avatar: monoline strokes, round caps, 4.5 units wide.

| File | Use |
| --- | --- |
| `flair-light.svg` | Wordmark for light backgrounds (ink `#1F2328`) |
| `flair-dark.svg` | Wordmark for dark backgrounds (ink `#F0F6FC`) |
| `flair-avatar-light.svg`, `.png` | Square avatar, 512 × 512, white background |
| `flair-avatar-dark.svg`, `.png` | Square avatar, 512 × 512, `#0D1117` background |

To switch between them with the viewer's GitHub theme:

```html
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/FLAIRUK/.github/main/brand/flair-dark.svg">
  <img src="https://raw.githubusercontent.com/FLAIRUK/.github/main/brand/flair-light.svg" alt="FLAIR" width="320">
</picture>
```
