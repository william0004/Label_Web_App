# Label — Brand Website (Bootstrap)

## Project Overview

Label is a small static brand website template built with Bootstrap. It provides a simple site framework and several basic pages (for example: home, about, product, and terms). This project is a good starting point for a static showcase site or a lightweight marketing page.

## Highlights

- Built with Bootstrap for responsive layouts
- Simple, clear file structure that is easy to modify and extend
- Includes common pages: `Index.html`, `About.html`, `Necklaces page.html`, `Terms.html`

## Tech Stack

- HTML5 and CSS
- Bootstrap (CDN or local files — check each HTML page for the actual include)
- Static assets: styles are under `ccs/` and images are stored in `Image/`

## Project Structure (important files/dirs)

- `Index.html` — site homepage
- `About.html` — about page
- `Necklaces page.html` — example product page for necklaces
- `Terms.html` — terms / legal page
- `ccs/Untitled-3.css` — current project stylesheet (likely contains custom styles)
- `Image/` — image assets

Note: Paths or names may vary depending on local copies; use the repository files as the source of truth.

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src="https://github.com/william0004/Label_Web_App/blob/main/Label_Web_App/gif/project.gif" title='Video Walkthrough' width='' alt='Video Walkthrough' />

## Local Preview (recommended)

This is a static website, so you can open `Index.html` directly in a browser. However, serving the files from a local static server avoids some browser restrictions and is recommended.

PowerShell example (from the project root):

```powershell
cd "g:\study\Projects\Label_Web_App\Label_Web_App"
# Start a simple static server with Python 3 on port 8000
python -m http.server 8000
# Then open http://localhost:8000/Index.html in your browser
```

If you use Visual Studio Code, the Live Server extension is convenient: right-click `Index.html` and choose "Open with Live Server" for auto-reload while editing.

## Development notes

- Styles: edit `ccs/Untitled-3.css`, or create a new CSS file and include it from each HTML `<head>`.
- Images: add new images to `Image/` and reference them with relative paths (for example `Image/logo.png`).
- Bootstrap: the project assumes Bootstrap is included (likely via CDN). You can replace the CDN with local files or upgrade to a newer Bootstrap version; be aware class names and layout rules may change between versions.

Common changes you might make:
- Update navigation links and labels
- Replace hero images and copy in `Index.html`
- Add or edit product cards on `Necklaces page.html`

## Deployment (quick tips)

This is a static site. Common hosting options:

- GitHub Pages: push the repository to GitHub and enable Pages from the repository settings (choose main branch or `gh-pages`).
- Static hosts (Netlify, Vercel, Surge): connect the repo and deploy — no build step is required for plain static files.
- Copy files to any static web server (Nginx, Apache).

GitHub Pages minimal flow (PowerShell example):

```powershell
# Assuming repo is initialized and remote origin set
git add .
git commit -m "Add Label static site"
git push origin main
# Then enable GitHub Pages from the repository Settings -> Pages
```

## Assumptions & Notes

- The project is expected to use Bootstrap; if CDN includes are missing, add them to each HTML page or include Bootstrap locally.
- Filenames with spaces (for example `Necklaces page.html`) can cause issues in some environments and deployments. Consider renaming files to a dash-separated format such as `necklaces-page.html`.

## Authors & Contact

- Yaowei Lei
- Yuemei Zhu

---

## Assets & Copyright

All photographs and logos used in this project were taken or created by the authors and are original works. All rights to these images and logos are reserved by the authors. Commercial use, redistribution, or reuse of the photographs and logos is prohibited without explicit written permission from the authors.

If you need to use any image or logo for commercial or public distribution, please contact the authors to request permission and licensing terms.
