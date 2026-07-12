# Renault Trafic Campervan — For Sale

Static single-page ad for a 2014 Renault Trafic campervan conversion.
Located in Dee Why, Sydney NSW.

## What this is
Plain static site — one `index.html` plus an `images/` folder. No build step,
no dependencies. Deployed via GitHub Pages.

## Local preview
```bash
python3 -m http.server 8080
# open http://localhost:8080
```

## Structure
```
index.html      # the whole page (HTML + CSS + JS inline)
images/         # 20 optimised JPGs (~12MB total)
```

## Editing
- **Price / contact:** edit the `#contact` section in `index.html`.
- **Photos:** edit the `photos` array near the bottom of `index.html`.
