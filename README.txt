# Devika Prasad — 3D Portfolio Starter

## Files
- `index.html` — interactive 3D homepage (Three.js loaded from a CDN)
- `portfolio.css` — homepage styles
- `project.html` — Day to Live calculator
- `style.css` — calculator styles
- `README.txt` — setup notes

Keep your existing `profile.jpg` in the repository if you want to use it later. This first 3D version does not require it.

## Run it locally
Because `index.html` loads Three.js as a JavaScript module, open it through a local web server rather than double-clicking the file:
1. Put these files in one folder.
2. Open that folder in VS Code.
3. If you have the Live Server extension, right-click `index.html` and choose **Open with Live Server**.
4. If you do not have Live Server, you can publish to GitHub Pages and open the public site.

An internet connection is required to load Three.js and the Google Fonts.

## Publish using your existing GitHub repository
1. Open your repository: `devikaprasad663-cloud` on GitHub.
2. Open `index.html`, choose the pencil/edit button, select all the old code, and replace it with the new `index.html` from this folder. Commit the change.
3. Add a new file named `portfolio.css` and paste the contents of `portfolio.css`. Commit.
4. Open `project.html`, replace its contents with the new `project.html`, and commit.
5. Open `style.css`, replace its contents with the new `style.css`, and commit.
6. Check **Settings → Pages**. If Pages is enabled, choose the `main` branch and `/ (root)` as the publishing source, then save.
7. Wait for GitHub Pages to publish. Your homepage will be at `https://devikaprasad663-cloud.github.io/portfolio/` if the repository is named `portfolio`; if the repository has a different name, the URL uses that repository name instead.

## Personalise before publishing
- In `index.html`, replace `yourmail@gmail.com` with your real email address.
- Replace the LinkedIn URL with your actual profile URL.
- Update the About, Skills and project descriptions so they accurately reflect your work.
- Keep `profile.jpg` in the repo; it can be added to the design in a later iteration.

## Controls
Use **W/A/S/D** or the **arrow keys** to move the character around the 3D island. Approach the labelled islands to open information cards. Press **Escape** to close a card. On mobile, this first version is view-only; keyboard movement is intentionally enabled for laptop use.

## Notes
This is an original, lightweight portfolio inspired by interactive 3D portfolio experiences. It is not a copy of Bruno Simon's site or assets. The first stage uses simple geometric models and does not yet include a drivable car.
