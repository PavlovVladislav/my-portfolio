# Portfolio site

A responsive, static portfolio site deployed with GitHub Pages.

## Site content

The portfolio content is based on `Vladyslav_Pavlov_CV.pdf` and project details shared in chat. The downloadable CV is stored at `assets/Vladyslav_Pavlov_CV.pdf`. Update that file and the matching download links in `index.html` when publishing a revised CV. Colors, layout, and typography live in `style.css`.

## Publish on GitHub Pages

1. Create a GitHub repository and push this project to its `main` branch (or keep `master`; both are supported).
2. In the repository, open **Settings → Pages**. If Pages is not enabled yet, set **Build and deployment → Source** to **GitHub Actions** and save. This one-time setup is required before the workflow can find the Pages site.
3. Push a change to `main`/`master`, or run **Deploy portfolio to GitHub Pages** from the **Actions** tab.
4. Once the workflow succeeds, the Pages URL appears under **Settings → Pages** and in the workflow deployment.

This site is plain HTML and CSS, so it needs no build step or package installation.
