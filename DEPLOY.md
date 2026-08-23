# Hosting the Operation Series at operation.peterstam.eu

Same free-subdomain trick as chalkboard/worlds (GitHub Pages).

## 1. New GitHub repo (e.g. operation-series-site)
Upload EVERYTHING in this folder (keep names): the .html pages, the .js files,
social-card.png, all the .pdf files, HOW-TO-SHARE-THIS.txt, and CNAME.
(~110 files, ~29 MB. If web-upload is slow, drag it in a few batches, or use GitHub Desktop.)

## 2. GitHub Pages
Settings -> Pages -> Deploy from a branch -> main -> / (root). It auto-fills operation.peterstam.eu from CNAME.

## 3. GoDaddy DNS
Add a CNAME record: Name = operation , Value = pstamberlin.github.io (same as worlds/chalkboard, different name).

## 4. Wait for "DNS check successful", tick Enforce HTTPS.

Notes: 46 characters, all downloads bundled here (Vader's guide = the combined manual_*.pdf).
PDFs are the recompressed set (~27 MB total) — same content, a third of the size.
