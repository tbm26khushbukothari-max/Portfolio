# Khushbu Kothari · Personal Portfolio

A single-page personal portfolio for Khushbu Kothari — Brand Strategist, Product Marketer, and AI-fluent operator. Targeting roles at Google, Meta, and global-scale technology companies.

Built as static HTML/CSS/JS. No build step, no framework, no dependencies. Deploy anywhere that serves a file.

---

## Tech stack

- **Vanilla HTML, CSS, JavaScript.** Everything is inline in `index.html`.
- **Google Fonts** via `<link>`: Fraunces (serif), Inter (sans), JetBrains Mono (mono).
- **No backend.** Contact links are mailto/tel/external URLs.

Do not add a framework, build step, or package.json unless explicitly asked.

---

## File structure

```
KK Portfolio/
├── index.html                   The entire site
├── CLAUDE.md                    This file
├── README.md                    Human-readable overview
├── .gitignore
│
├── assets/
│   ├── images/
│   │   ├── hero/                portrait.jpg — 4:5 ratio headshot
│   │   ├── about/               about-photo.jpg — 4:5 casual/working photo
│   │   ├── case-studies/        dabur-starwars.jpg, live-history.jpg, roos-india.jpg (4:3)
│   │   └── projects/            galleri5.jpg, zyngai.jpg, rusticks.jpg,
│   │                            anita-dongre.jpg, bearcare.jpg, park-avenue.jpg (16:10)
│   ├── pdf/                     resume-khushbu-kothari.pdf — one-page CV
│   ├── favicon/                 favicon.ico (32x32), og-image.jpg (1200x630)
│   └── brand/                   Brand assets Khushbu owns rights to
│
├── case-studies/                Future individual case study pages
│   ├── _template/index.html     Starter template — copy and rename
│   ├── dabur-starwars/
│   ├── live-history-india/
│   └── roos-india/
│
├── writing/                     Future articles and thought leadership
│   └── _template/index.html
│
├── data-work/                   Future data viz, Tableau embeds, KNIME exports
│
└── archive/                     Old versions
```

---

## Design system

### Colours (CSS variables, defined in `:root`)

| Token | Value | Use |
|---|---|---|
| `--bg` | `#faf7f0` | Page background — warm cream |
| `--bg-alt` | `#f1ece1` | Secondary background |
| `--bg-dark` | `#15110d` | Brands section, contact footer |
| `--ink` | `#15110d` | Primary text |
| `--ink-2` | `#2d2620` | Secondary text |
| `--muted` | `#6b6258` | De-emphasised text |
| `--faint` | `#a89e90` | Subtle UI |
| `--line` | `#e3dccc` | Borders |
| `--accent` | `#c4522d` | Rust orange — primary accent |
| `--accent-dark` | `#9a3e21` | Hover state |

### Fonts

- **Fraunces** (`--serif`) — headings, display text, italic flourishes
- **Inter** (`--sans`) — body, UI, navigation
- **JetBrains Mono** (`--mono`) — labels, eyebrows, tags, metadata

### Layout

- Max content width: 1200px
- Page padding: `--page-pad: 2.5rem` (1.25rem on mobile)
- Section padding: 7rem (4.5rem tight, 3.5rem mobile)

---

## Section map

1. **Nav** (`nav.topbar`) — fixed, blurs on scroll
2. **Hero** (`#top`) — name, role, 4 stats, CTA buttons, portrait
3. **Brands** (`.brands-section`) — dark bg, dual animated marquee rows with brand chips + metric pills
4. **Tools strip** — compact AI/data tool tags
5. **Featured Work** (`#work`) — 3 large case studies (Problem / Approach / Impact)
6. **More Work** — 6 smaller project cards (grid)
7. **About** (`#about`) — bio, 3 principles
8. **Experience** (`#experience`) — timeline
9. **Capabilities** (`#capabilities`) — 5 toolkit cards
10. **Education** (`#education`) — timeline
11. **Recognition** — awards grid
12. **Contact** (`#contact`) — dark footer, links

---

## How to add a case study image

Inside the `.case-media` block, replace the placeholder like this:

```html
<div class="case-media">
  <img src="assets/images/case-studies/dabur-starwars.jpg"
       alt="Dabur x Star Wars campaign"
       style="position:absolute;inset:0;width:100%;height:100%;object-fit:cover;">
</div>
```

Remove the `theme-rust` (or other theme) class from `.case-media` once you add the image.

## How to add a project card image

Inside `.gmedia`, replace the placeholder:

```html
<div class="gmedia">
  <img src="assets/images/projects/galleri5.jpg"
       alt="Galleri5 x Myntra EORS"
       style="position:absolute;inset:0;width:100%;height:100%;object-fit:cover;">
</div>
```

Remove the theme class from `.gmedia`.

## Image placeholder themes

`theme-rust`, `theme-olive`, `theme-plum`, `theme-navy`, `theme-sand`, `theme-forest`, `theme-ink`, `theme-clay`

Each renders as a gradient until the real image is dropped in.

---

## Recommended image specs

| Slot | File | Ratio | Recommended size |
|---|---|---|---|
| Hero portrait | `assets/images/hero/portrait.jpg` | 4:5 | 800×1000px |
| About photo | `assets/images/about/about-photo.jpg` | 4:5 | 800×1000px |
| Case study 01 | `assets/images/case-studies/dabur-starwars.jpg` | 4:3 | 1200×900px |
| Case study 02 | `assets/images/case-studies/live-history.jpg` | 4:3 | 1200×900px |
| Case study 03 | `assets/images/case-studies/roos-india.jpg` | 4:3 | 1200×900px |
| Project cards (×6) | `assets/images/projects/*.jpg` | 16:10 | 800×500px |
| OG image | `assets/favicon/og-image.jpg` | 1200:630 | 1200×630px |

Optimise all images before adding (target under 200KB each). Use squoosh.app or imageoptim.

---

## TODOs before sharing with recruiters

- [ ] Add hero portrait (`assets/images/hero/portrait.jpg`)
- [ ] Add about photo (`assets/images/about/about-photo.jpg`)
- [ ] Add 3 case study images
- [ ] Add 6 project card images
- [ ] Add resume PDF (`assets/pdf/resume-khushbu-kothari.pdf`) and update `href` in contact section
- [ ] Replace `href="#"` placeholder links with real URLs
- [ ] Add favicon (`assets/favicon/favicon.ico`)
- [ ] Add OG meta tags for social sharing
- [ ] Register and point a custom domain (`khushbukothari.com`)

## Future additions (already have placeholder folders)

- [ ] Write case study sub-pages — use `case-studies/_template/index.html`
- [ ] Add a writing / articles section — use `writing/_template/index.html`
- [ ] Embed Tableau dashboards or KNIME exports in `data-work/`

---

## Voice and tone

- First person. Calm confidence. Concrete numbers over adjectives.
- No superlatives: no "passionate," "rockstar," "ninja."
- Less copy, not more. If a sentence can be cut, cut it.
- The rust accent colour used sparingly — it earns attention.

---

## Deployment (quickest paths)

**GitHub Pages** — free, fast:
1. `git init` in this folder, push to GitHub
2. Repo Settings → Pages → source: main branch / root
3. Live at `https://username.github.io/repo/`

**Vercel** — cleanest URL, auto-deploys:
1. Connect repo at vercel.com
2. Every push to main auto-deploys

**Netlify** — drag and drop:
1. app.netlify.com/drop → drag entire folder
2. Instant URL, can connect domain later

**Custom domain** — buy on Namecheap or Cloudflare Registrar, point CNAME, enable HTTPS.
