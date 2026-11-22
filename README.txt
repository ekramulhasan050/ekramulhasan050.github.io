Md. Ekramul Hasan - portfolio website (ready to deploy)

FILES
- index.html                 the whole site (photo, logos and styles are inside the file)
- Md-Ekramul-Hasan-CV.pdf    used by the "Download CV" button (keep this exact name)
- 404.html                   custom "page not found" page
- robots.txt, sitemap.xml    for search engines

DEPLOY ON GITHUB PAGES (current) OR NETLIFY
- GitHub Pages: upload these files to the root of the ekramulhasan050.github.io repository.

NETLIFY (alternative)
1. Unzip this folder.
2. In Netlify choose "Add new site" > "Deploy manually" and drag the folder in.

UPDATING
- New CV: replace Md-Ekramul-Hasan-CV.pdf with a new PDF using the same name.
- Text, projects and links: edit index.html (or ask Claude to update it).

WHEN YOU HAVE A CUSTOM DOMAIN
- Add a sitemap.xml with your real address and put this line in robots.txt:
  Sitemap: https://YOUR-DOMAIN/sitemap.xml
- Add <link rel="canonical" href="https://YOUR-DOMAIN/"> inside <head> of index.html.
