# Jibin Song Personal Homepage

Static personal academic homepage ready for GitHub Pages deployment.

## Files

- `index.html` — main page
- `styles.css` — visual design and responsive layout
- `script.js` — mobile nav and scroll reveal interactions
- `assets/CV_JibinSong_public.pdf` — CV link target
- `assets/profile-placeholder.svg` — temporary profile image

## How to deploy on GitHub Pages

1. Create a new GitHub repository, for example `jibin-song-homepage`.
2. Upload all files in this folder to the repository root.
3. Go to `Settings` → `Pages`.
4. Under `Build and deployment`, select:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
5. Save.

Your website will be available at:

```text
https://<your-github-username>.github.io/<repository-name>/
```

## Replace the profile photo

Replace `assets/profile-placeholder.svg` with your own photo, for example:

```text
assets/profile.jpg
```

Then update this line in `index.html`:

```html
<img src="assets/profile-placeholder.svg" alt="Profile placeholder for Jibin Song" />
```

to:

```html
<img src="assets/profile.jpg" alt="Jibin Song" />
```

## Notes

- Some publication links are placeholders because final paper/project links may not be available yet.
- Edit the disabled `href="#"` links in `index.html` when links become available.
