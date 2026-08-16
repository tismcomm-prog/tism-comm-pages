# Pages

Static pages, one folder each, served from a single Vercel deployment.

```
build-flow/     the product build flow, steps 2.5 to 6, plus the printed PDF
```

Every page is self-contained: one `index.html`, no build step, no dependencies. Add a page by adding a folder with an `index.html` in it, then adding a row to the root `index.html`.

Pages are generated elsewhere and copied in. Edit them at the source, not here.
