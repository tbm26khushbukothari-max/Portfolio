# Data Work

Space for data visualisation, analytics exports, and AI/tool demos.

## What to add here

| File / Folder | What it is |
|---|---|
| `tableau-embeds/` | Embed codes or screenshots from Tableau dashboards |
| `knime-exports/` | KNIME workflow screenshots, outputs, or write-ups |
| `ai-experiments/` | Google AI Studio prompts, outputs, comparisons |
| `data-viz/` | Any charts, infographics, or visual data work |

## How to link to this from the portfolio

Option 1 — add a new project card in the More Work grid in `index.html`:

```html
<article class="gcard reveal">
  <div class="gmedia theme-olive">
    <div class="ph-grain"></div>
    <div class="ph-inner">
      <div class="ph-top">Image</div>
      <div class="ph-name">Data<br>Work</div>
    </div>
  </div>
  <div class="gbody">
    <div class="gtag">Analytics · Data Visualisation</div>
    <h4>Tableau dashboard / KNIME workflow title</h4>
    <p class="gdesc">One paragraph describing what the data shows and what decision it informed.</p>
    <a href="data-work/your-file.html" class="glink">View work <span class="arr">→</span></a>
  </div>
</article>
```

Option 2 — link directly to a Tableau public embed URL in an existing project card.

## Embedding a Tableau Public dashboard

```html
<div class='tableauPlaceholder' style='width:100%;aspect-ratio:16/9;'>
  <noscript>
    <a href='#'><img alt='Dashboard' src='your-static-preview.png'></a>
  </noscript>
  <object class='tableauViz' style='display:none;'>
    <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
    <param name='embed_code_version' value='3' />
    <param name='path' value='views/YourWorkbookName/YourDashboardName' />
    <param name='toolbar' value='yes' />
  </object>
</div>
<script type='text/javascript' src='https://public.tableau.com/javascripts/api/viz_v1.js'></script>
```
