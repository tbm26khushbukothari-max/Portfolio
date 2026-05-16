# About section photo

A casual or working photo for the About section — not a headshot, something more candid.

**File name:** `about-photo.jpg`
**Ratio:** 4:5 (portrait orientation)
**Recommended size:** 800 × 1000 px
**Max file size:** 200 KB

## How to wire it up

In `index.html`, find the `.about-photo` div in the About section and replace it with:

```html
<img
  src="assets/images/about/about-photo.jpg"
  alt="Khushbu at work"
  style="width:100%;aspect-ratio:4/5;object-fit:cover;
         border-radius:var(--r-lg);box-shadow:var(--shadow-2);">
```

Remove the `theme-clay` class and the `ph-grain` / `ph-inner` divs inside `.about-photo`.

## Ideas for this photo

- At your desk working
- At a whiteboard or brainstorm session
- At Masters' Union campus
- Speaking or presenting
- Candid at Lil Flea / Khar Gymkhana with ROOS
