# tahsinjawad.github.io

Personal portfolio for Tahsin Jawad, Senior Mobile Engineer in Sydney.

Live at https://tahsinjawad.github.io

## Stack

Plain HTML, CSS and vanilla JS. No build step. `.nojekyll` makes GitHub Pages serve the files as-is.

```
index.html            single-page site
assets/css/style.css  styles, dark default with light toggle
assets/js/script.js   nav, theme toggle, scroll reveal
assets/img/           drop profile.jpg here to replace the TJ placeholder
```

## Local preview

```
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Updating

- Profile photo: add `assets/img/profile.jpg` (4:5 ratio works best).
- Projects and roles: edit the matching `<article>` blocks in `index.html`.
