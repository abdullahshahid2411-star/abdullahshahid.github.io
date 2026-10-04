# Abdullah Shahid portfolio

A single-page static website using semantic HTML, CSS and a small optional JavaScript file. No build, dependencies, backend, analytics or contact form.

## Preview locally

Open `index.html` in a browser, or serve this folder with Python:

```sh
python -m http.server 8000
```

Then visit `http://localhost:8000/`. The Loom player requires an internet connection and may be blocked by browser privacy settings; its fallback link remains available.

## Edit the site

- Edit visible copy, metadata and navigation in `index.html`.
- Adjust layout and colors in `styles.css`; responsive rules are at the end.
- The exact Loom embed and fallback URLs are in the `demo` section of `index.html`.
- Email links are in the header, contact section and footer. LinkedIn links are in contact and footer. Header/contact email buttons include the encoded enquiry subject and body. When changing them, URL-encode subject/body values and escape query separators as `&amp;` in HTML.
- `script.js` updates the footer year. The HTML fallback year is 2026.
- `favicon.svg` contains the AS initials.

## Deploy to GitHub Pages

Copy the contents of this folder (including `.nojekyll`) to the root of the existing `abdullahshahid.github.io` repository. Preserve unrelated files and repository configuration. Review and commit the changes, then push only when ready.

If Pages already serves the root of your deployment branch, retain those settings. Otherwise choose that branch and `/ (root)` under GitHub repository Settings → Pages → Deploy from a branch. No build command is needed.

The intended URL is https://abdullahshahid2411-star.github.io/abdullahshahid.github.io/. Assets use `./` paths and navigation uses fragment links, so the repository subpath works. Canonical and Open Graph URLs point to that address. No social image is fabricated.

Nothing has been published or pushed by this implementation. Email actions open the visitor’s mail application; they do not send a message themselves.
