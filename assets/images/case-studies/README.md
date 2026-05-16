# Case study hero images

Three images for the featured case studies in the Work section.

| File | Case study | Ratio | Size |
|---|---|---|---|
| `dabur-starwars.jpg` | Dabur Herb'l × Star Wars | 4:3 | 1200 × 900 px |
| `live-history.jpg` | Live History India | 4:3 | 1200 × 900 px |
| `roos-india.jpg` | ROOS India | 4:3 | 1200 × 900 px |

Max file size: 200 KB each. Compress at squoosh.app.

## How to wire each one up

Inside the relevant `.case-media` div in `index.html`, add the image and remove the theme gradient class:

```html
<!-- Before (placeholder) -->
<div class="case-media theme-rust">
  <div class="ph-grain"></div>
  <div class="ph-inner">...</div>
</div>

<!-- After (real image) -->
<div class="case-media">
  <img
    src="assets/images/case-studies/dabur-starwars.jpg"
    alt="Dabur Herb'l x Star Wars campaign"
    style="position:absolute;inset:0;width:100%;height:100%;object-fit:cover;">
</div>
```

## Image ideas

**dabur-starwars.jpg** — Campaign hero visual, Star Wars + Dabur branding, a social post screenshot, or a behind-the-scenes creative shot

**live-history.jpg** — Platform screenshot, artisan product photo, or a community/event moment from Live History India

**roos-india.jpg** — Lookbook flatlay, garment detail, or a model/wearer photo from the ROOS collection
