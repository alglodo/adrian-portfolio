# Adrian L. Glodo — Creative Portfolio

A responsive personal portfolio website built with HTML, CSS, and JavaScript.

## Files
- `index.html` — website structure and content
- `style.css` — layout and visual styling
- `script.js` — navigation, project filters, project viewer, and contact form
- `assets/` — portfolio images and graphics

## Run locally
Open `index.html` in a web browser.

## Publish with GitHub Pages
1. Create a new repository on GitHub (for example, `adrian-portfolio`).
2. Upload **all the contents of this folder** to the repository's main branch. Make sure `index.html` is in the repository's root.
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then click **Save**.
6. Wait for GitHub Pages to publish the site. The website link will appear in the Pages section.

## Contact form setup
The contact form opens the visitor's email app. To enable it, open `script.js` and replace the empty value in this line with your email address:

```js
const CONTACT_EMAIL = '';
```

For example, use `const CONTACT_EMAIL = 'you@example.com';`.

## Notes
- Keep the `assets` folder and its files in the same location as `index.html`.
- The Google Fonts connection requires internet access; the rest of the site is static.
