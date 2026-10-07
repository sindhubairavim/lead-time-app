# Lead Time Mock-ups

Static site, no build step.

- `/` landing page
- `/supplier/` Supplier Portal (entry + history views)
- `/buyer/` Buyer Portal (lead time comparison)

## Deploy to Vercel

Option 1, CLI (from this folder):

    npx vercel        # preview
    npx vercel --prod # production

Option 2, Git: push this folder to a repo, then Import Project in Vercel.
Framework preset: Other. Build command: none. Output directory: leave blank (root).

## Run locally

    npx serve .
