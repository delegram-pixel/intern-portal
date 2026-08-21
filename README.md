# Intern Demo

A starter project with a clean, organized HTML & CSS structure.

## Project structure

```
intern-demo/
├── index.html          # Main page (semantic HTML5)
├── css/
│   ├── reset.css       # Minimal CSS reset — normalizes browser defaults
│   └── style.css       # Site styles (design tokens, layout, components)
├── js/
│   └── main.js         # JavaScript (small enhancements)
├── assets/
│   └── images/         # Images and other static assets
└── README.md           # This file
```

## Getting started

Open `index.html` in a browser, or serve the folder locally:

```bash
# Python 3
python3 -m http.server

# Node (if you have it)
npx serve
```

Then visit http://localhost:8000 (or the port shown).

## Conventions

- **HTML** — semantic elements (`header`, `nav`, `main`, `section`, `footer`).
- **CSS** — [BEM](https://getbem.com/)-style class names (`block__element--modifier`)
  and CSS custom properties (design tokens) defined in `:root`.
- **Assets** — keep images and fonts under `assets/`.
# intern-portal
