# Pigg Logic website

A small, static company website for [Pigg Logic, LLC](https://pigglogic.com). Plain HTML, shared CSS, system fonts, and local images. No build step or JavaScript dependencies.

## Preview locally

From this directory:

```sh
python3 -m http.server 8080 --bind 127.0.0.1
```

Open http://127.0.0.1:8080. Root-relative URLs assume the existing `pigglogic.com` custom domain, or a server running from this directory.

## Pages

- `/`: company introduction, work, studio, and contact.
- `/privacy/`: company website and correspondence data practices.
- `404.html`: GitHub Pages error page.

The existing `/#support` and `/#privacy` fragments remain valid. The site follows the visitor’s light or dark appearance preference.

The visual system uses native sans-serif typography, heather charcoal text, denim blue accents, and an off-white canvas. Dark appearance uses charcoal surfaces and lighter denim accents.

Chordstep has a small listing linking to `https://chordstep.com/`. Its product pages, app documentation, support, and app policies belong on that separate website; they are not built in this project.

## Maintenance

The Chordstep listing links to chordstep.com for product and release details. Keep the company’s privacy policy aligned with the website’s hosting provider and correspondence practices.

The `CNAME` is preserved for GitHub Pages. Publish these files through the repository’s existing Pages configuration; no hosting migration is required.
