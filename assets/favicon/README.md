# Favicon and OG image

## Files to add

| File | Size | Purpose |
|---|---|---|
| `favicon.ico` | 32 × 32 px | Browser tab icon |
| `favicon-192.png` | 192 × 192 px | Android home screen |
| `apple-touch-icon.png` | 180 × 180 px | iOS home screen |
| `og-image.jpg` | 1200 × 630 px | Social media preview card |

## Free tools

- **favicon.io** — generate a favicon from text (use "KK" in Fraunces italic, rust colour `#c4522d`)
- **og-image generators** — vercel.com/og or opengraph.xyz

## How to wire up in index.html

Add inside `<head>` (after the font link):

```html
<link rel="icon" type="image/x-icon" href="assets/favicon/favicon.ico">
<link rel="apple-touch-icon" href="assets/favicon/apple-touch-icon.png">
<link rel="icon" type="image/png" sizes="192x192" href="assets/favicon/favicon-192.png">

<!-- OG / social sharing -->
<meta property="og:title" content="Khushbu Kothari — Brand Strategist & Product Marketing">
<meta property="og:description" content="Six years across founder's offices, agencies, and a D2C label. AI-fluent, data-driven, shipping at scale.">
<meta property="og:image" content="https://yourdomain.com/assets/favicon/og-image.jpg">
<meta property="og:url" content="https://yourdomain.com">
<meta name="twitter:card" content="summary_large_image">
```
