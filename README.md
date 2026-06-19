# Dr. Rani Shahwan — Bilingual Consultancy Website

A static bilingual website built with HTML, CSS, and plain JavaScript. It is ready to publish with GitHub Pages and requires no build process or backend.

## Website structure

```text
/
├── index.html                  Language selection page
├── .nojekyll                   GitHub Pages static-site marker
├── en/                         English website (left-to-right)
│   ├── index.html
│   ├── about.html
│   ├── services.html
│   ├── projects.html
│   └── contact.html
├── ar/                         Arabic website (right-to-left)
│   ├── index.html
│   ├── about.html
│   ├── services.html
│   ├── projects.html
│   └── contact.html
└── assets/
    ├── css/styles.css
    ├── images/portrait-placeholder.svg
    └── js/main.js
```

The root `index.html` lets visitors choose English or Arabic. Each page has a language switch linking to its matching page in the other language.

## Publish with GitHub Pages

1. Create a new repository on GitHub.
2. Upload the **contents of this folder** to the repository root. `index.html` must be at the top level of the repository.
3. Commit and push the files to the `main` branch.
4. On GitHub, open **Settings → Pages**.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select the `main` branch and the `/ (root)` folder, then click **Save**.
7. After deployment completes, open:

   `https://YOUR-USERNAME.github.io/YOUR-REPOSITORY/`

No base URL changes are required because the website uses relative internal links.

## Current contact details

- Email: `r.shahwan@najah.edu`
- WhatsApp: `+970 592918081`
- Location: Nablus, Palestine
- Profile photograph: `assets/images/portrait.jpg`

The contact page includes working links to the An-Najah staff profile, Google Scholar, ORCID, LinkedIn, ResearchGate, and the CV on Google Drive.

The website has no contact-form backend. Email and mobile actions use standard `mailto:` and `tel:` links, and WhatsApp opens through `wa.me`.

## Test locally

Open `index.html`, or serve the folder with a simple static web server. Check:

- `/en/` for English
- `/ar/` for Arabic
