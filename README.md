# Aarvines Jewells — Digital Catalogue

Live catalogue at: https://aarvines-jewells.vercel.app (once deployed)

---

## Deploy to Vercel (one time, 5 minutes)

1. Go to https://github.com/new
2. Create a repo called `aarvines-jewells` (private or public)
3. Upload all 3 files: `index.html`, `pieces.json`, `rates.json`
4. Go to https://vercel.com → New Project → Import from GitHub
5. Select `aarvines-jewells` → Deploy
6. Done — you get a live URL like `aarvines-jewells.vercel.app`

Optional: add a custom domain like `catalogue.aarvinesjewells.com` in Vercel settings.

---

## Adding a new piece

Open `pieces.json` and add a new object to the array:

```json
{
  "id": "KELR-9999",
  "name": "Your Piece Name",
  "category": "ring",
  "catLabel": "Ring",
  "metal": "14KT White Gold",
  "finish": "Polished",
  "netWt": 2.5,
  "diaWt": 0.75,
  "stoneWt": 0,
  "available": true,
  "isNew": true,
  "image": "data:image/jpeg;base64,PASTE_BASE64_HERE",
  "notes": "Any extra details here."
}
```

To get base64 for the image: https://www.base64-image.de — upload photo, copy the base64 string.

Push to GitHub → Vercel auto-deploys in ~30 seconds.

---

## Updating gold/diamond rates

Open `rates.json` and change the numbers:

```json
{
  "gold": 9300,
  "labour": 1500,
  "diamond": 18000,
  "stone": 1000,
  "gst": 3,
  "wa": "919667330138"
}
```

Push to GitHub → all prices update live instantly.

---

## Marking a piece as sold

In `pieces.json`, find the piece and set `"available": false`.

---

## Store Details

Aarvines Jewells
573, Sector 27, Gurgaon
+91 96673 30138
info@aarvinesjewells.com
GSTIN: 06ABDCA8515B1Z3
