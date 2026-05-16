# Case study hero images

Four images for the featured case studies. Save your file with the **exact filename below** — that is what the HTML expects.

| Save as this filename | Matches this card on screen | Ratio | Size |
|---|---|---|---|
| `dabur-herbl-x-star-wars.jpg` | Dabur Herb'l × Star Wars | 4:3 | 1200 × 900 px |
| `live-history-india.jpg` | Live History India | 4:3 | 1200 × 900 px |
| `roos-india.jpg` | ROOS India | 4:3 | 1200 × 900 px |
| `loreal-paris-cannes.jpg` | L'Oréal Paris Cannes 2025 | 4:3 | 1200 × 900 px |

Max file size: 200 KB each. Compress at squoosh.app before dropping in.

## How to wire each one up in index.html

Inside the relevant `.case-media` div, replace the placeholder block with the image and remove the theme class:

```html
<!-- Dabur Herb'l × Star Wars -->
<div class="case-media">
  <img src="assets/images/case-studies/dabur-herbl-x-star-wars.jpg"
       alt="Dabur Herb'l × Star Wars campaign"
       style="position:absolute;inset:0;width:100%;height:100%;object-fit:cover;">
</div>

<!-- Live History India -->
<div class="case-media">
  <img src="assets/images/case-studies/live-history-india.jpg"
       alt="Live History India platform"
       style="position:absolute;inset:0;width:100%;height:100%;object-fit:cover;">
</div>

<!-- ROOS India -->
<div class="case-media">
  <img src="assets/images/case-studies/roos-india.jpg"
       alt="ROOS India lookbook"
       style="position:absolute;inset:0;width:100%;height:100%;object-fit:cover;">
</div>
```

## How to wire each one up in the case study sub-pages

In each `case-studies/[folder]/index.html`, replace the `.cs-hero-img` placeholder div:

```html
<!-- Before -->
<div class="cs-hero-img">
  <span class="img-placeholder">...</span>
</div>

<!-- After -->
<div class="cs-hero-img">
  <img src="../../assets/images/case-studies/dabur-herbl-x-star-wars.jpg"
       alt="Dabur Herb'l × Star Wars campaign">
</div>
```

## Image ideas

**dabur-herbl-x-star-wars.jpg** — Campaign hero visual with Star Wars + Dabur branding, a social post screenshot, or a behind-the-scenes creative shot

**live-history-india.jpg** — Platform screenshot, artisan product photo, or a community moment from Live History India

**roos-india.jpg** — Lookbook flatlay, garment detail, or a model/wearer photo from the ROOS collection

**loreal-paris-cannes.jpg** — Red carpet moment, Nykaa campaign creative, or a product flat-lay with Cannes visual language
