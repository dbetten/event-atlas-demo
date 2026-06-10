# Event Atlas — Static Demo

Static build of the Event Atlas prototype with a 2-year archive of real
weather events generated from NOAA outlook archives (SPC, WPC, NHC).

Built by `scripts/build-static-site.ts`. To deploy on GitHub Pages:

```bash
npx tsx scripts/build-static-site.ts
cd dist-pages
git init && git add -A && git commit -m "Deploy Event Atlas demo"
git push -f <repo-url> HEAD:gh-pages
```

Then enable Pages for the `gh-pages` branch in repo settings.
