# Ellis Power Group — Website

Website for the Ellis Power Group (Power Electronics) at UC Santa Cruz, led by Prof. Nathan Ellis.

Live site: [ellispowergroup.github.io/ellis-power-group](https://ellispowergroup.github.io/ellis-power-group)

## Pages

- **index.html** — Home: group overview, news, and featured conference presentations
- **people.html** — Team: PI, PhD students, MS students, undergrad researchers, and alumni
- **research.html** — Research projects (converter cards with images and paper links) and publications list
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
    ├── EPG_simple_blue.png              # Favicon
    ├── EPG_simple_transparent_white.png # Navbar / footer logo
    └── ...                              # Headshots and converter images
```

## Editing Content

### People
- Copy a card block in `people.html` and fill in the name, role, and bio.
- Replace the `<div class="person-img placeholder">` with an `<img>` tag pointing to a photo in `images/`.
- Name headshot files in `FirstnameLastname.jpg` format.

### News
- Copy a card block in the News section of `index.html`, newest first.
- Set `src="images/your-image.jpg"` on the card's `<img>` tag (or use the no-image placeholder block).
- The full description appears in a modal popup when "Read More" is clicked.

### Featured Conference Presentations
- Copy a card block in the Featured Conference Presentations section of `index.html`.
- Set the iframe `src` to `https://www.youtube.com/embed/VIDEO_ID`.
- Fill in the title, description, and paper URL.

### Research / Converters
- Copy a card block in `research.html` and fill in the title, description, and paper URL.
- Replace the `<div class="research-img placeholder">` with an `<img class="research-img">` tag.
- Name image files with hyphens (no spaces) and save to `images/`.

### Publications
- Copy a publication entry block in the "All Publications" section of `research.html`.
- Fill in the title, authors, venue, year, and DOI link.

## Deployment

Static site — no build step required.

Hosted via GitHub Pages on the [EllisPowerGroup](https://github.com/EllisPowerGroup) account.
To update: push to the `main` branch of `EllisPowerGroup/ellis-power-group` and GitHub Pages will redeploy automatically.
