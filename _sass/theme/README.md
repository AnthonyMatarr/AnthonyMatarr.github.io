# Color Theme System

This directory contains color theme options for the website. You can easily switch between them by changing the `site_theme` setting in `_config.yml`.

## Available Color Themes

### Original Themes
- **default** - Original teal/turquoise theme
- **air** - Light and airy theme
- **sunrise** - Warm orange/yellow theme
- **mint** - Fresh mint green theme
- **dirt** - Earthy brown theme
- **contrast** - High contrast black/white theme

### New Custom Themes (Recommended for ML/Academic Work)

#### **slate** (Recommended)
Modern, sophisticated gray-blue - GitHub/VS Code inspired
- Clean and tech-forward
- Perfect for technical/research portfolios
- Professional and modern

#### **sage**
Muted green - calming and intellectual
- Natural, approachable
- Modern academic feel
- Easy on the eyes for extended reading

#### **charcoal**
Sophisticated dark gray with warm amber accents
- Contemporary and professional
- Warm but not distracting
- Great contrast and readability

## How to Switch Themes

1. Open `_config.yml` in the root directory
2. Find the `site_theme` line (near the top)
3. Change the value to one of the theme names above
4. Save the file
5. Restart your Jekyll server

Example:
```yaml
site_theme: "slate"
```

## Dark Mode

All themes include both light and dark versions. Users can toggle between them using their system preferences or browser settings.

## Pairing with Fonts

All themes work with any font option, but they were designed to pair beautifully with:
- **option4-contemporary-academic** (Lexend + Inter + JetBrains Mono)
