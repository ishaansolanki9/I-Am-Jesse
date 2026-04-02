# Shareable Photo Rotation Site

This is a tiny static website that works on phones, tablets, and desktops.

## Add your files

Put these files inside `assets/`:

- `photo-1.jpg`
- `photo-2.jpg`
- `photo-3.jpg`
- `tap-audio.mp3`

You can use `.png`, `.jpeg`, or another audio format if you update the file names in `index.html`.

## Preview locally

Open `index.html` in a browser, or run a small local server:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## How it works

- The first photo shows by default.
- Each tap or click switches to the next photo.
- The audio restarts on every tap.

## Deploy free with GitHub Pages

This is the easiest free option because the site is fully static.

1. Create a new empty repository on GitHub.
2. In this project folder, run:

```bash
git add .
git commit -m "Initial photo rotator site"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git
git push -u origin main
```

3. On GitHub, open your repository.
4. Go to `Settings` -> `Pages`.
5. Under `Build and deployment`, choose `Deploy from a branch`.
6. Set the branch to `main` and the folder to `/ (root)`.
7. Click `Save`.
8. Wait about 1 to 3 minutes for GitHub Pages to publish the site.

Your site URL will usually be:

```text
https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/
```

If the photos or audio do not show up after deploy, make sure your `assets/` files are included in the repo before pushing.
