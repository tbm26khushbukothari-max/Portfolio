# Hero portrait

Place your professional headshot here.

**File name:** `portrait.jpg`
**Ratio:** 4:5 (portrait orientation)
**Recommended size:** 800 × 1000 px
**Max file size:** 200 KB (compress at squoosh.app)

## How to wire it up

In `index.html`, find the `.portrait` div in the Hero section and replace it with:

```html
<img
  src="assets/images/hero/portrait.jpg"
  alt="Khushbu Kothari"
  style="width:100%;aspect-ratio:4/5;object-fit:cover;
         border-radius:var(--r-lg);box-shadow:var(--shadow-3);">
```

Delete the entire `.portrait` div (including the `ph-tag` inside it) once the image is in.

## Tips

- Use a plain or softly blurred background — the cream page colour (`#faf7f0`) will frame it.
- Shoot in natural light if possible.
- Crop so the face occupies the top 60% of the frame.
