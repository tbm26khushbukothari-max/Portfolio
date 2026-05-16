# Project card images

Six images for the smaller project cards in the More Work grid.

| File | Project | Ratio | Size |
|---|---|---|---|
| `galleri5.jpg` | Galleri5 × Myntra EORS | 16:10 | 800 × 500 px |
| `zyngai.jpg` | Zyngai.com | 16:10 | 800 × 500 px |
| `rusticks.jpg` | RuSticks | 16:10 | 800 × 500 px |
| `anita-dongre.jpg` | Anita Dongre | 16:10 | 800 × 500 px |
| `bearcare.jpg` | Bearcare | 16:10 | 800 × 500 px |
| `park-avenue.jpg` | Park Avenue | 16:10 | 800 × 500 px |

Max file size: 150 KB each.

## How to wire each one up

Inside the relevant `.gmedia` div:

```html
<!-- Before -->
<div class="gmedia theme-navy">
  <div class="ph-grain"></div>
  <div class="ph-inner">...</div>
</div>

<!-- After -->
<div class="gmedia">
  <img
    src="assets/images/projects/galleri5.jpg"
    alt="Galleri5 x Myntra EORS"
    style="position:absolute;inset:0;width:100%;height:100%;object-fit:cover;">
</div>
```

Remove the theme class from `.gmedia` once the image is in.
