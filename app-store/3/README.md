# Invoice365 App Store Landing Page - Version 3

This is an App Store-style landing page designed for Google Ads A/B testing to optimize CTR (Click-Through Rate).

## Features

- ✅ App Store-inspired design
- ✅ Responsive layout (mobile, tablet, desktop)
- ✅ Dark mode support with system preference detection
- ✅ Horizontal scrollable screenshot gallery (mobile/tablet)
- ✅ Grid layout screenshot gallery (desktop)
- ✅ Lightbox modal for full-size screenshot viewing
- ✅ Keyboard navigation (ESC to close, arrows to navigate)
- ✅ Smooth animations and transitions
- ✅ SEO optimized with meta tags
- ✅ Google Analytics integration

## A/B Testing

### Changing Primary Color

Edit the CSS variables in the `<style>` section (around line 42):

```css
:root {
  --primary-color: #FF5722;        /* Change this for different variations */
  --primary-color-hover: #E64A19;  /* Hover state */
  --primary-color-light: #FF7043;  /* Light variant */
}
```

**Suggested colors to test:**
- Orange (current): `#FF5722`
- Blue: `#007AFF`
- Green: `#34C759`
- Purple: `#AF52DE`
- Red: `#FF3B30`

### Changing App Icon

Replace the image source in the hero section (around line 288):

```html
<img src="./assets/1.png" alt="Invoice365 App Icon" class="app-icon" id="app-icon">
```

Simply replace `1.png` with your alternative icon image.

### Changing Screenshots

Update the screenshot images in the `./assets/` folder (files 2.png through 9.png).

## File Structure

```
/app-store/3/
├── index.html          # Main landing page
├── README.md           # This file
└── assets/
    ├── 1.png          # App icon
    ├── 2.png          # Screenshot 1
    ├── 3.png          # Screenshot 2
    ├── 4.png          # Screenshot 3
    ├── 5.png          # Screenshot 4
    ├── 6.png          # Screenshot 5
    ├── 7.png          # Screenshot 6
    ├── 8.png          # Screenshot 7
    └── 9.png          # Screenshot 8
```

## Usage

1. Open `index.html` in a web browser
2. Or deploy to your web server
3. Use for Google Ads campaigns
4. Track CTR and conversions
5. Create variations by duplicating and modifying colors/icons

## Dark Mode

The page automatically detects the user's system preference for dark mode. Users can also manually toggle between light and dark modes using the button in the top-right corner.

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- Lightweight design
- Optimized images recommended
- Fast loading times
- Smooth animations

## Analytics

Google Analytics is integrated with tracking ID: `G-V8KHMM0GPM`

Track the following events:
- Page views
- Download button clicks
- Screenshot interactions
- Theme toggle usage

