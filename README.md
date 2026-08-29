# Throttle & Steel

A multi-page motorbike dealership site built with HTML5, CSS3, and Bootstrap 4 —
a dark, motorsport-inspired home page with a hero, bike carousel, and rider
reviews, plus a full browsing flow across 8 bike categories, a "Garage" (saved
bikes) page, and sign-up/login screens.

## Features
- **Home page** — full-height hero with an ember/amber accent palette, an
  auto-rotating bike carousel, a "Why Ride With Us" section, rider reviews, an
  8-category fleet grid, a test-ride & financing section, and a rider
  community/gallery section
- **Bike category pages** (`bikes/`) — 8 categories (Cruisers, Sportbikes,
  Vintage, Off-Road, Naked Bikes, Touring, Electric, Scooters), each listing 6
  bikes with specs and pricing
- **Garage page** — saved bikes with Featured / Available / Sold / Reserved
  status badges
- **Sign-up & Login pages** — matching dark auth screens, cross-linked
- Fully responsive layout with a shared `styles.css` driving the whole site

## Built with
- HTML5 & CSS3 (custom properties for theming — asphalt/ember/amber palette)
- [Bootstrap 4.5.2](https://getbootstrap.com/) for grid, navbar, and carousel behavior
- Google Fonts: Bebas Neue (display) + Barlow Condensed (body/UI)
- Photos via [Unsplash](https://unsplash.com/license); avatars via [randomuser.me](https://randomuser.me/)

## Project structure
```
throttle-steel-site/
├── index.html          # home page
├── garage.html          # saved bikes / cart-equivalent page
├── sign-up.html         # sign-up page
├── login.html           # login page
├── styles.css            # shared stylesheet
└── bikes/
    ├── cruisers.html
    ├── sportbikes.html
    ├── vintage.html
    ├── off-road.html
    ├── naked.html
    ├── touring.html
    ├── electric.html
    └── scooters.html
```

## Usage
Open `index.html` directly in a browser, or enable **GitHub Pages** on this
repo (root folder as source) to view it live — navigation between pages, the
fleet grid, and the garage all work as static links.

## Notes
- Bike images are reused/tinted stock photos, not unique inventory photography — swap in real bike photos when available.
- Forms on the sign-up and login pages are static (no backend) — placeholders for future wiring.

## License
This project is licensed under the MIT License — see the `LICENSE` file for details (add one via GitHub when creating or importing the repo).
