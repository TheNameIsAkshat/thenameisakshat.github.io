# Akshat Srivastava – Portfolio

A single-page portfolio with Hero, About, What I do, Projects, Experience, and Footer.

## Run locally

Open `index.html` in a browser, or use a local server:

```bash
# Python 3
python3 -m http.server 8080

# Node (npx)
npx serve .
```

Then visit `http://localhost:8080` (or the port shown).

## Customize

- **Images:** Replace the hero and about image URLs in `index.html` with your own (e.g. `assets/hero.jpg`, `assets/about.jpg`).
- **Links:** Update the Github, Resume, Live Demo, and social links in `index.html` to your profiles.
- **Company logos:** Replace the placeholder logo divs in the Experience section with `<img>` tags pointing to your company logos if you have them.

## Structure

- `index.html` – All sections and content
- `styles.css` – Layout, colors, typography (Poppins, teal accent, light gray background)
- `assets/` – Optional folder for your images
