# penguinpowerup.github.io

Source for my personal webpage, served by GitHub Pages at <https://penguinpowerup.github.io/>.

## Structure

```
index.html          # the whole page (intro, education, publications, research, awards & service, skills)
css/style.css       # styles (light/dark follows the OS setting)
assets/avatar.jpg   # profile photo
assets/favicon.svg, favicon.png, apple-touch-icon.png
.nojekyll           # tell GitHub Pages to serve the files as-is
```

## Updating

1. Edit `index.html` (content) or `css/style.css` (styling).
2. Commit and push to `main`; GitHub Pages redeploys automatically within a minute or two.

To preview locally:

```
python3 -m http.server 8000
# then open http://localhost:8000
```
