# Font Theme System

This directory contains different font theme options for the website. You can easily switch between them by changing the `font_theme` setting in `_config.yml`.

## Available Font Themes

### `default`
**System Fonts** - Original theme using system fonts
- Headings: System sans-serif
- Body: System sans-serif
- Code: Monaco, Consolas

### `option1-clean-modern`
**Clean & Modern (Coding-Adjacent)** - Best for tech-focused academic portfolio
- Headings: Inter
- Body: IBM Plex Sans
- Code: JetBrains Mono

### `option2-academic-professional`
**Academic Professional** - Traditional but modern feel
- Headings: Playfair Display (serif)
- Body: Source Sans 3
- Code: Source Code Pro

### `option3-tech-monospace`
**Tech-Forward Monospace Everything** - Distinctive coding aesthetic
- Headings: Space Mono
- Body: IBM Plex Mono
- Code: IBM Plex Mono

### `option4-contemporary-academic` (Recommended)
**Contemporary Academic** - Balances professionalism with modern tech feel
- Headings: Lexend
- Body: Inter
- Code: JetBrains Mono

### `option5-minimalist-professional`
**Minimalist Professional** - Sleek, contemporary look
- Headings: Montserrat
- Body: Lato
- Code: Roboto Mono

## How to Switch Font Themes

1. Open `_config.yml` in the root directory
2. Find the `font_theme` line (near the top)
3. Change the value to one of the options above
4. Save the file
5. Restart your Jekyll server if running locally

Example:
```yaml
font_theme: "option4-contemporary-academic"
```

## Technical Details

- Font themes are loaded via Google Fonts in `_includes/fonts.html`
- SCSS variables are defined in each theme file
- The selected theme is imported in `assets/css/main.scss` before other styles
- All fonts include fallbacks to system fonts for performance
