# Qazi Shamsud Tahmeed — Personal Site

A single-page site showing the profile, current work, portfolio highlights, experience, and skills, with the CV available as a direct download.

## Files

- `index.html` — the whole site
- `style.css` — styling
- `photo.jpg` — headshot
- `Qazi_Shamsud_Tahmeed_CV.pdf` — downloadable CV (linked from the "Download CV" button)

No build step — these are plain static files.

## Publishing with GitHub Pages

1. Create a new GitHub repository (public), e.g. `qazi-tahmeed.github.io` for a root-level personal site, or any name for a project site.
2. Upload/push these four items (`index.html`, `style.css`, and the `assets/` folder) to the repository root.
3. In the repo, go to **Settings → Pages**.
4. Under **Build and deployment → Source**, select **Deploy from a branch**.
5. Choose the `main` branch and `/ (root)` folder, then **Save**.
6. GitHub will publish the site within a minute or two, at:
   - `https://<your-username>.github.io/` (if the repo is named `<your-username>.github.io`), or
   - `https://<your-username>.github.io/<repo-name>/` (for any other repo name)

## Updating later

To update content (a new portfolio piece, a role change, a new CV version):
- Edit `index.html` directly for text changes.
- Replace `assets/Qazi_Shamsud_Tahmeed_CV.pdf` with a new export to update the download.
- Push the change — GitHub Pages redeploys automatically within a minute or two.
