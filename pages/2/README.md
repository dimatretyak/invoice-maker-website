# Invoice365 Landing Page - Variant 2

A modern, Loom-inspired landing page designed for Google Ads A/B testing.

## 🎨 Features

- **Loom-inspired Design**: Clean, modern layout with bold typography and smooth animations
- **Dark Mode Support**: Automatically detects and applies system theme preferences
- **Fully Responsive**: Optimized for mobile, tablet, and desktop devices
- **A/B Testing Ready**: Easy color scheme changes via CSS variables
- **Interactive Gallery**: Clickable screenshots with lightbox modal
- **Social Proof**: 4.9 star rating with 6 user testimonials
- **SEO Optimized**: Complete meta tags and Open Graph support

## 📁 Files

- `index.html` - Main landing page with Tailwind CDN
- `style.css` - Custom styles with CSS variables for A/B testing
- `assets/` - App icon (logo.jpg) and screenshots (1.png - 9.png)

## 🧪 A/B Testing

To test different color schemes, simply modify the CSS variables in `style.css`:

```css
:root {
  --primary-color: #11b561;  /* Change this for different variants */
  --primary-hover: #0ea54e;
  --primary-light: #2dd88f;
}
```

### Suggested Color Variants for Testing:

1. **Green (Default)**: `#11b561` - Professional, trustworthy
2. **Blue**: `#3b82f6` - Corporate, reliable
3. **Purple**: `#8b5cf6` - Creative, modern
4. **Orange**: `#f97316` - Energetic, friendly
5. **Red**: `#ef4444` - Bold, urgent

## 🎯 Sections

1. **Hero Section**
   - App icon with hover effect
   - Bold headline and subheadline
   - 4.9 star rating display
   - Primary CTA button
   - Trust badges

2. **Preview Section**
   - 8 app screenshots in responsive grid
   - Hover effects with lift animation
   - Clickable lightbox for enlarged views

3. **Features Section**
   - 6 key features with icons
   - Card-based layout
   - Hover effects

4. **Reviews Section**
   - 6 user testimonials
   - Gradient avatars
   - 5-star ratings

5. **CTA Section**
   - Full-width call-to-action
   - Primary color background
   - Download button

6. **Footer**
   - Copyright and links
   - Privacy policy link

## 🌓 Dark Mode

Dark mode is automatically detected and applied based on the user's system preferences. The implementation:

- Prevents FOUC (Flash of Unstyled Content) with inline script
- Listens for system theme changes in real-time
- Applies dark variants to all components

## 📱 Responsive Breakpoints

- **Mobile** (default): Single column, stacked layout
- **Tablet** (md: 768px): 2-column grids, larger text
- **Desktop** (lg: 1024px): 3-4 column grids, full-width hero

## 🚀 Usage

1. Open `index.html` in a browser
2. The page will automatically detect your system theme
3. Click on screenshots to view them in lightbox
4. All links point to the App Store listing

## 🔗 Links

- App Store: https://apps.apple.com/US/app/id6743351285
- Main Website: https://invoice365.app
- Privacy Policy: ../../privacy-policy.html

## 📊 Google Analytics

The page includes Google Analytics tracking (ID: G-V8KHMM0GPM) to measure:
- Page views
- Click-through rates on CTA buttons
- User engagement metrics

## 🎨 Icon Testing

To test different app icons, simply replace `assets/logo.jpg` with your variant icon. The icon should be:
- Square format (1:1 ratio)
- Minimum 512x512px
- JPG or PNG format

## ✨ Key Differences from Variant 1

This variant features:
- Loom-inspired hero section with larger, bolder typography
- Gradient backgrounds for visual depth
- More prominent social proof placement
- Simplified, cleaner feature cards
- Enhanced hover animations throughout
- Lighter, more modern color palette

---

Built with ❤️ using Tailwind CSS

