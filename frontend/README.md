# Arun R — Professional Portfolio

A responsive static portfolio built with HTML, CSS and a small amount of JavaScript. It is ready to deploy on Netlify.

## Folder structure

- `index.html` — website content
- `css/style.css` — responsive styling
- `js/main.js` — mobile navigation and dynamic copyright year
- `netlify.toml` — Netlify publish configuration

## Deploy to Netlify

1. Extract `arun-professional-portfolio.zip`.
2. Open Netlify and sign in.
3. From the Netlify dashboard, choose **Add new site → Deploy manually** (the wording may vary).
4. Drag and drop the extracted `arun-professional-portfolio` folder into the deploy area. Upload the folder itself, not the ZIP.
5. Netlify will publish the site and provide a `*.netlify.app` URL.

## Before publishing

- Check your email address and LinkedIn URL in `index.html`.
- Add your GitHub profile link when ready.
- Add a resume PDF only if you want it publicly downloadable; place it in this folder and add a link in the page.
- Review the project descriptions and update them as your work progresses.
- The portfolio is a static website. Django/Python projects described here are separate projects; this portfolio itself does not require a backend.

## Optional Git-based deployment

Push this folder to a GitHub repository, then in Netlify choose **Add new site → Import an existing project**, connect the repository, and use `.` as the publish directory. No build command is required.
