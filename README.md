# Khushbu Kothari — Portfolio

Personal portfolio site for Khushbu Kothari, Brand Strategist and Product Marketer.

## Run locally

No build step. Open `index.html` in a browser, or serve it:

```bash
# Python 3
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploy

| Platform | Steps |
|---|---|
| GitHub Pages | Push repo → Settings → Pages → main branch / root |
| Vercel | Connect repo at vercel.com → auto-deploys on push |
| Netlify | Drag folder to app.netlify.com/drop |

For a custom domain (`khushbukothari.com`): buy on Namecheap or Cloudflare Registrar, point CNAME to your host, enable HTTPS.

## Project structure

```
KK Portfolio/
├── index.html                   Main portfolio (single-file site)
├── CLAUDE.md                    Context file for Claude Code sessions
├── README.md                    This file
├── .gitignore
│
├── assets/
│   ├── images/
│   │   ├── hero/                Headshot — portrait.jpg (4:5 ratio)
│   │   ├── about/               Working photo — about-photo.jpg (4:5 ratio)
│   │   ├── case-studies/        3 featured images (4:3 ratio each)
│   │   └── projects/            6 project card images (16:10 ratio each)
│   ├── pdf/                     Resume PDF
│   ├── favicon/                 favicon.ico + OG image
│   └── brand/                   Any brand assets you own rights to
│
├── case-studies/                Future: individual case study pages
│   ├── _template/               Starter HTML template
│   ├── dabur-starwars/
│   ├── live-history-india/
│   └── roos-india/
│
├── writing/                     Future: articles, essays, thought leadership
│   └── _template/
│
├── data-work/                   Future: Tableau embeds, KNIME exports, data viz
│
└── archive/                     Old versions and experiments
    └── v1-portfolio.html
```

## Editing with Claude Code

Open this folder in Claude Code — it reads `CLAUDE.md` automatically for full context.
