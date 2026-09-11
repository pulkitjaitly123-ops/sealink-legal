# SeaLink legal pages

The published privacy policy and terms of use for the SeaLink mobile app.

Served by GitHub Pages so the App Store and Google Play have a stable public URL,
which both stores require.

These pages are generated from `docs/PRIVACY.md` and `docs/TERMS.md` in the app
repository by `tools/build_site.mjs`. Do not edit the HTML here by hand: change
the markdown, run `npm run build:legal && npm run build:site`, and copy the
output across. The same markdown is bundled into the app itself, so the
published page and the text users agreed to cannot drift apart.
