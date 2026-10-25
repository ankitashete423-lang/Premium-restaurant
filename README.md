# Saffron & Stone — Restaurant Website

Saffron & Stone is a premium fine-dining restaurant website built as a frontend portfolio project with **only HTML5 and CSS3**. It has no JavaScript and uses no frameworks.

> The menu, prices, reviews, address and contact details are sample content for demonstration. Reservations use `mailto:` and `tel:` links, not a working booking system.

## Features

- Sticky navigation with a CSS-only mobile menu and a "Reserve a Table" call to action
- Full-bleed hero photograph with a large serif headline
- Four signature dish cards with images, descriptions and prices
- Two-column philosophy section with an offset gold frame
- Menu highlights for starters, main courses and desserts
- Wide photographic dining-experience section
- Responsive six-photo gallery
- Three guest review cards
- Reservation section using email and phone links
- Footer with address placeholder, opening hours, contact details and social links
- Accessible contrast, visible focus styles, skip link and `prefers-reduced-motion` support

## Technologies

- HTML5 (semantic markup)
- CSS3 (custom properties, Grid, Flexbox, media queries, transitions)
- Google Fonts: Cormorant Garamond and Jost
- Photography hosted on Unsplash

## Structure

```
saffron-and-stone/
├── index.html
├── style.css
└── README.md
```

## Run locally

1. Clone or download this repository.
2. Open `index.html` in a modern browser. An internet connection is needed for fonts and photographs.

Optional: run `python3 -m http.server 8000` in the project folder and visit `http://localhost:8000`.

## Deploy to GitHub Pages

1. Create a new GitHub repository, for example `saffron-and-stone`.
2. Push the files to the repository root:
   ```
   git init
   git add .
   git commit -m "Add Saffron & Stone restaurant website"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/saffron-and-stone.git
   git push -u origin main
   ```
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the **main** branch and the **/ (root)** folder, then save.
6. The site will be live at `https://YOUR-USERNAME.github.io/saffron-and-stone/`.

Before publishing, replace the sample email, phone number and address with real details.

## Credits

Photographs from [Unsplash](https://unsplash.com). Design and code are original.
