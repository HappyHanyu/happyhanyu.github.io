# Yanghanyu Zhao — Academic Homepage

Personal academic website for [happyhanyu.github.io](https://happyhanyu.github.io), built as a classic static GitHub Pages site.

## Local preview

Open `index.html` in a browser, or serve locally:

```bash
python -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000).

## GitHub Pages deployment

This repo is named `happyhanyu.github.io`, so it publishes automatically as a **user site** at:

**https://happyhanyu.github.io**

### First-time setup

1. Push this repo to `HappyHanyu/happyhanyu.github.io` on GitHub.
2. Go to **Settings → Pages** in the repository.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Choose branch **`main`** and folder **`/ (root)`**, then save.
5. After a minute or two, the site will be live at the URL above.

No build step is required — the site is plain HTML and CSS (`.nojekyll` disables Jekyll processing).

## Project structure

```
├── index.html              # Main page
├── css/style.css           # Styles
├── resource/
│   └── Yanghanyu_Zhao_CV.pdf
├── .nojekyll
└── README.md
```

## Customization

- **LinkedIn URL** — Update the LinkedIn links in `index.html` if your profile URL differs.
- **Research interests** — Edit the `#research` section to match your target PhD programs.
- **Photo** — Add a headshot under `assets/` and include it in the hero section if desired.
- **CV** — Replace `resource/Yanghanyu_Zhao_CV.pdf` when you update your CV; the download links will stay the same.
