# Academic Homepage

A single-page, zero-build academic homepage (plain HTML + CSS). Hosted on GitHub Pages.

```
index.html      # the page (all content + placeholders to fill)
style.css       # styling, light/dark theme
.nojekyll       # tells GitHub Pages to serve files as-is (no Jekyll)
assets/
  cv.pdf        # your CV (currently the compiled English CV)
  avatar.svg    # placeholder portrait — replace with assets/avatar.jpg
```

## 1. Fill in your details

Open `index.html` and replace every `PLACEHOLDER:…` token (search for `PLACEHOLDER:`).
On the page these show in a reddish color (`.ph` class) so you can spot what's left.
The full list is in the comment block at the top of `index.html`.

To use a real photo: drop `assets/avatar.jpg` in, then change the `src` in the
hero `<img>` from `assets/avatar.svg` to `assets/avatar.jpg`.

## 2. Preview locally

```bash
cd homepage
python3 -m http.server 8080
# open http://localhost:8080
```

## 3. Deploy to GitHub Pages

GitHub Pages serves a repo named **`<username>.github.io`** at
`https://<username>.github.io`.

```bash
# one-time: create the repo on github.com named  <username>.github.io  (public)

cd homepage
git add -A
git commit -m "Academic homepage"
git branch -M main
git remote add origin https://github.com/<username>/<username>.github.io.git
git push -u origin main
```

In the repo's **Settings → Pages**, confirm: *Source = Deploy from a branch*,
*Branch = main / (root)*. The site is live within ~1 minute.

> Updating later: edit files, `git add -A && git commit -m "update" && git push`.

## Notes
- This server is in China; pushing to GitHub may need the proxy
  (`HTTP_PROXY=http://127.0.0.1:7890`, already in this shell's env).
- No custom domain / ICP 备案 needed — `github.io` is publicly reachable.
