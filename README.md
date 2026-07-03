# Priority Bags · High Spirit — Catalogue & Contact Hub

A single-page hub linking all of **High Spirit Commercial Ventures Pvt. Ltd.**'s bag
catalogues, brands (Priority Bags, Hashtag, Traworld) and contact channels — built for
international clients. One shareable link, with a printable QR code for standees and
printed materials.

## Files
- **index.html** — the hub (static, no build step). All content lives in the `SITE`
  config object near the bottom of the file; edit it to add catalogues and links.
- **qr-poster.html** — A4 print-ready poster with the QR code for standees. Open it in a
  browser and print.
- **qr.svg** — the QR code on its own, encoding the live site URL.

## Live
Deployed on Vercel: https://scanner-bice-gamma.vercel.app

## Adding a catalogue
In `index.html`, find `catalogues:` in the `SITE` object and paste each PDF's shareable
link (Google Drive / Dropbox / website) into its `url`. An empty `url` shows a
"Coming soon" card. Commit and redeploy.
