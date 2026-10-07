# Pengyu Zha — Personal Homepage

Public site: https://zpyc1oud.github.io/

The homepage is a self-contained static HTML page. It presents research interests, EmbodiedUE, Beyond-Lip, and contact information.

## Edit and preview

Edit `index.html`. Its CSS is in the same file. No build step or package installation is required.

Run `python -m http.server 8000` from the repository root. Open http://localhost:8000/ and check desktop and phone layouts, navigation links, and the expandable paper description.

## Publish

GitHub Pages publishes the repository root from `master`. `.nojekyll` disables Jekyll processing. Wait for the Pages build and deployment workflow to succeed after a commit.

Keep `sitemap.xml`, the canonical URL, and `robots.txt` consistent with the public URL. Preserve the Google verification file.

The old Jekyll configuration, layout, and stylesheet are retained for reference; the new homepage does not use them.
