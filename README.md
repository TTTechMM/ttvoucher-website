# TTVoucher Website

This folder contains a small static website for the TTVoucher app.

## Pages

- `/` - home page
- `/privacy-and-policy/` - privacy policy
- `/terms-and-conditions/` - terms and conditions

## Local preview

Run a simple local server from this folder:

```bash
python3 -m http.server 3000
```

Then open:

```text
http://localhost:3000
```

## Deploy on Vercel

1. Create a new Vercel project.
2. Set the project Root Directory to `website`.
3. Keep the framework preset as `Other`.
4. No build command is required.
5. No output directory is required.
6. Deploy.

Because this folder is plain static HTML, CSS, and route folders, Vercel can
serve it directly.

## Files

- `index.html` - landing page
- `assets/styles.css` - shared styles
- `privacy-and-policy/index.html` - privacy page
- `station-data-deletion.md` - source text for station data deletion requests
- `terms-and-conditions/index.html` - terms page
- `vercel.json` - small static-site config for Vercel

## Notes

- The legal pages are based on the project policy files in the repository root:
  - `../privacy-and-policy.md`
  - `../terms-and-conditions.md`
- If those source documents change, update the matching HTML pages in this
  folder too.
