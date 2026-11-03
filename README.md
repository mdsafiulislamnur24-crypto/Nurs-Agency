# Nur's Agency — Static Website

A responsive static website built with plain HTML, CSS and vanilla JavaScript. No framework, package manager or build step is required.

## Files

- `index.html` — complete one-page agency website
- `assets/css/style.css` — layout, responsive styling and visual system
- `assets/js/main.js` — mobile navigation, current year and email-compose contact form

## Run locally

Open `index.html` in a modern browser. For a local development server, you can use VS Code's Live Server extension or run:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Before publishing

1. Replace `hello@nursagency.com` in `index.html` and `assets/js/main.js` with the real agency email.
2. Replace the concept portfolio visuals and project descriptions with genuine work. Keep concept work clearly labelled as concept work.
3. Add real social profile links and a favicon / social sharing image if required.
4. Review all copy and contact details.

## Contact form limitation

The form validates the fields and opens the visitor's default email application with a prefilled message. It does **not** send email automatically, store submissions, or provide a server-side inbox. For automatic submissions, connect a real form backend or service and replace the mailto handler with its documented endpoint.

## Deploy to GitHub Pages

1. Create a repository on GitHub.
2. Upload the contents of this folder so `index.html` is at the repository root.
3. In the repository, open **Settings → Pages**.
4. Choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
5. Wait for GitHub Pages to publish the site and open the URL shown in Pages settings.

The site uses Google Fonts from an external CDN; if visitors are offline or the CDN is unavailable, fallback fonts will be used.
