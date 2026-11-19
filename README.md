# Portfolio Website

A fast, accessible, dependency-free portfolio. Plain HTML, CSS and JavaScript.

## Folder structure

```
portfolio/
├── index.html            # Page markup and content
├── css/
│   └── style.css         # Colours, fonts and layout (edit the tokens at the top)
├── js/
│   └── main.js           # Theme switch, menu, project filter, contact form
├── assets/
│   ├── images/           # Put project screenshots and your photo here
│   ├── icons/
│   │   └── favicon.svg
│   └── resume.pdf        # Add your résumé (link already in index.html)
└── README.md
```

## Make it yours

1. In `index.html`, replace the name, text, projects, links and experience.
2. In `js/main.js`, change `EMAIL` to your address.
3. Replace the coloured project thumbnails with screenshots: put images in `assets/images/`
   and swap each `<div class="thumb">` for `<img class="thumb" src="assets/images/xyz.png" alt="...">`.
4. Change colours or fonts in the `:root` block of `css/style.css`.

## Run locally

Open `index.html` in a browser, or serve the folder:

```
python -m http.server 8000
```

## Deploy free

Push the folder to GitHub and enable GitHub Pages, or drag it onto Netlify or Vercel.
