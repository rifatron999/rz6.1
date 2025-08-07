# Assets Folder

This folder contains all static assets for the RoNZar website.

## File Structure

- `image.jpg` - Placeholder for hero or feature images
- `font.woff2` - Custom font files (if needed)

## Usage

Add your images, fonts, and other static assets here. The HTML file references these files using relative paths like:

```html
<img src="assets/image.jpg" alt="Description">
<link rel="preload" href="assets/font.woff2" as="font" type="font/woff2" crossorigin>
```

## Recommended Image Formats

- **Hero Images**: JPG/PNG, optimized for web (max 500KB)
- **Icons**: SVG or PNG with transparent background
- **Product Images**: JPG, consistent aspect ratios
- **Background Images**: JPG/PNG, optimized for performance

## Font Files

If using custom fonts, include:
- `font.woff2` - Modern browsers (recommended)
- `font.woff` - Older browsers (fallback)
- `font.ttf` - Legacy support (if needed) 