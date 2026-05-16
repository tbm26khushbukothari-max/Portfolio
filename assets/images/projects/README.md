# Project card images

Seven images for the More Work grid. Save your file with the **exact filename below** — that is what the HTML expects.

| Save as this filename | Matches this card on screen | Ratio | Size |
|---|---|---|---|
| `loreal-paris-cannes.jpg` | L'Oréal Paris Cannes 2025 | 16:10 | 800 × 500 px |
| `galleri5-x-myntra-eors.jpg` | Galleri5 × Myntra EORS | 16:10 | 800 × 500 px |
| `zyngai.jpg` | Zyngai.com | 16:10 | 800 × 500 px |
| `rusticks.jpg` | RuSticks | 16:10 | 800 × 500 px |
| `anita-dongre.jpg` | Anita Dongre | 16:10 | 800 × 500 px |
| `bearcare.jpg` | Bearcare | 16:10 | 800 × 500 px |
| `park-avenue.jpg` | Park Avenue | 16:10 | 800 × 500 px |

Max file size: 150 KB each. Compress at squoosh.app before dropping in.

## How to wire each one up in index.html

Inside the relevant `.gmedia` div, replace the placeholder block with the image and remove the theme class:

```html
<!-- Galleri5 × Myntra EORS -->
<div class="gmedia">
  <img src="assets/images/projects/galleri5-x-myntra-eors.jpg"
       alt="Galleri5 × Myntra EORS activation"
       style="position:absolute;inset:0;width:100%;height:100%;object-fit:cover;">
</div>

<!-- Zyngai.com -->
<div class="gmedia">
  <img src="assets/images/projects/zyngai.jpg"
       alt="Zyngai AI image platform"
       style="position:absolute;inset:0;width:100%;height:100%;object-fit:cover;">
</div>

<!-- RuSticks -->
<div class="gmedia">
  <img src="assets/images/projects/rusticks.jpg"
       alt="RuSticks tableware brand"
       style="position:absolute;inset:0;width:100%;height:100%;object-fit:cover;">
</div>

<!-- Anita Dongre -->
<div class="gmedia">
  <img src="assets/images/projects/anita-dongre.jpg"
       alt="Anita Dongre sustainability messaging"
       style="position:absolute;inset:0;width:100%;height:100%;object-fit:cover;">
</div>

<!-- Bearcare -->
<div class="gmedia">
  <img src="assets/images/projects/bearcare.jpg"
       alt="Bearcare brand identity"
       style="position:absolute;inset:0;width:100%;height:100%;object-fit:cover;">
</div>

<!-- Park Avenue -->
<div class="gmedia">
  <img src="assets/images/projects/park-avenue.jpg"
       alt="Park Avenue menswear strategy"
       style="position:absolute;inset:0;width:100%;height:100%;object-fit:cover;">
</div>
```
