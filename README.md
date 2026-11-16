# Academic Portfolio — Thisara R. Weerakoon

Personal academic website: research, publications, teaching and service.

## Structure

| File | Purpose |
| --- | --- |
| `index.html` | Home — bio, research interests, news, publications, education, experience, honors, references |
| `research.html` | Research projects in detail (problem / approach / result), interests, ongoing work |
| `projects.html` | Engineering projects grouped by area |
| `teaching.html` | Teaching, outreach, open-source service, leadership, certifications |
| `style.css` | Design system: tokens, layout, components, responsive and print rules |
| `script.js` | Theme toggle (light/dark, remembered) and mobile navigation |
| `CV-Thisara_Weerakoon.pdf` | CV linked from every page |

Static site — no build step. Open `index.html`, or serve locally:

```sh
python -m http.server 8000
```

## Updating

- **New publication** — add a `.pub` block in the Publications section of `index.html`, and a
  `.section` entry in `research.html` if it deserves a full write-up.
- **News** — prepend an `li` to the `.news` list in `index.html`; keep it reverse-chronological
  and short.
- **Colours and spacing** — change the tokens in the `:root` block of `style.css`. Dark-mode
  values are redefined in the two blocks directly beneath it.
