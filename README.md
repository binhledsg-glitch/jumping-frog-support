# Jumping Frog — Support & Privacy

English public support and privacy website for the iPhone game **Jumping Frog**.

Publisher: **Ho Kinh Doanh Binh Le**  
Contact: **binh.le2207@gmail.com**

## Pages

- `index.html`: English home page.
- `support-en.html`: canonical English support page, also used by the app.
- `privacy-en.html`: canonical English privacy policy, also used by the app.
- `support.html` / `privacy.html`: English content aliases for existing links, with canonical links to the corresponding `-en.html` page.
- `styles.css`: shared page styles.

All five HTML pages are in English, with no language chooser.

This repository contains only the static public website. It has no game source, player saves or signing material. Editable source documents and the page generator are maintained locally outside this repository.

The pages use local CSS and system fonts, without JavaScript, analytics, forms or tracking cookies added by the publisher. GitHub Pages hosting data processing is disclosed in the privacy policy.

## Hosting and updates

Publish the repository root with GitHub Pages. Relative links support its project URL, and `.nojekyll` enables direct static serving. No custom domain is required. The privacy policy takes effect upon publication.

For updates, replace the relevant static HTML files and `styles.css`, then commit the changes.
