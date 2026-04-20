# Lavrador Modding — landing page source

Source for the public GitHub Pages site at `github.com/lavrador-modding/lavrador-modding.github.io`. Single static page — `index.html` + `style.css` + vendored assets (`assets/`, `fonts/`). No JavaScript, no build step, no external resource loads. Palette and typography track `_assets/brand/BRAND.md`; change brand tokens there first, mirror here.

Preview locally from inside this folder:

```fish
cd _assets/site
python3 -m http.server 8000
```

Open `http://localhost:8000/`. Publishing to the `lavrador-modding.github.io` repo is out-of-band — handled by Tiago outside this mono-repo.
