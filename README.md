# tahsinjawad.github.io

Personal portfolio of **Tahsin Jawad**, Senior Mobile Engineer based in Sydney.

🔗 **Live:** https://tahsinjawad.github.io

iOS first. Android close behind. React Native when one codebase makes sense. 7+ years shipping apps used by millions, including MyGP (14M+ MAU, 99.3% crash-free) and OneGP (replaced Workday, $7M AUD saved a year).

## What's on the site

- **About:** who I am, key numbers, what I'm looking for
- **Expertise:** iOS, Android and React Native, plus the tools I actually use
- **Work:** MyGP, OneGP, Noor and Meena Bazar, with app icons and store links
- **Experience:** Miaki, Wipro, Hexamatics, MCC and VU Mobile
- **Contact:** email, GitHub, LinkedIn

## Stack

Plain HTML, CSS and vanilla JS. No framework, no build step. `.nojekyll` tells GitHub Pages to serve the files as-is.

```
index.html               single-page site
assets/css/style.css     styles, dark by default with a light toggle
assets/js/script.js      nav, theme toggle, scroll reveal
assets/img/profile.webp  profile photo (4:5, WebP)
assets/img/apps/         app icons (192px WebP)
```

## Run locally

```bash
python3 -m http.server 8000
```

Open http://localhost:8000.

## Editing

- Projects and roles live in the `<article>` blocks in `index.html`.
- Swap the photo by replacing `assets/img/profile.webp`. Keep it 4:5 and save as WebP.
- Accent colour is `--accent` at the top of `style.css`.

## Contact

[tahsanjawad@gmail.com](mailto:tahsanjawad@gmail.com) · [LinkedIn](https://www.linkedin.com/in/tahsinjawad) · [GitHub](https://github.com/tahsinjawad)
