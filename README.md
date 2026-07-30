# Laia Romero — Product Design Portfolio

Personal portfolio site: work, process, skills, about and contact, plus an in-depth
case study for **FlyCalm**.

## Live pages

| Page | File |
| --- | --- |
| Portfolio (home) | `index.html` |
| FlyCalm case study | `case-study-flycalm.html` |

## Structure

```
.
├── index.html               # Portfolio — hero, work carousel, process, skills, about, contact
├── case-study-flycalm.html  # FlyCalm case study — problem, research, decisions, results
├── support.js               # Component runtime
├── image-slot.js            # Drag-and-drop image placeholder element
└── assets/
    ├── icons/               # Tool icons used by the Skills cards
    └── img/                 # Portrait and project imagery
```

## Running locally

The pages are static, but load their runtime over `file://` restrictions — serve the
folder rather than double-clicking:

```bash
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploying

Enable **GitHub Pages** on the `main` branch, root folder. The site is served as-is,
no build step.

## Design notes

- Palette: cream `#FDFCF8` / `#F7F2E6`, ink `#3A342C`, terracotta accent
- Type: Merriweather (display) + Inter (UI)
- Work section is a drag-enabled carousel; Process uses inflating circles with
  drifting particles; Skills cards fan out on hover
