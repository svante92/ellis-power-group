# Ellis Power Group — Website

Website for the Ellis Power Group (Power Electronics) at UC Santa Cruz, led by Prof. Nathan Ellis.

## Pages

- **index.html** — Home: group overview, stats, and featured research
- **people.html** — Team: PI, PhD students, MS students, undergrad researchers, and alumni
- **research.html** — Research projects and publications list
- **contact.html** — Contact info, map, and prospective student application

## Structure

```
ellis-power-group/
├── index.html
├── people.html
├── research.html
├── contact.html
├── css/
│   └── style.css
└── images/
    ├── EPG.png        # Standard logo (for light backgrounds)
    └── EPG_white.png  # White logo (for dark backgrounds)
```

## Editing Content

- **Add a person** — Copy a card block in `people.html` and fill in the name, role, and bio. Replace the `person-img placeholder` div with an `<img>` tag pointing to a photo in `images/`.
- **Add a research project** — Copy a card block in `research.html` and fill in the title, description, and paper URL. Replace the `research-img placeholder` div with an `<img>` tag.
- **Update stats** — Edit the `highlight-number` spans in the "Group at a Glance" section of `index.html`.
- **Add a publication** — Copy a publication entry block in `research.html` and fill in the title, authors, venue, year, and DOI.

## Deployment

This is a static site — no build step required. Upload the repository contents to any static host (GitHub Pages, Netlify, etc.).

To deploy via GitHub Pages: go to **Settings → Pages**, set the source to the `main` branch and `/ (root)`.
