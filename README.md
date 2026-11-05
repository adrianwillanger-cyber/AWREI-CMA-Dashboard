# AWREI CMA Dashboard — GitHub Pages

Interactive browser-based CMA dashboard with uploaded MLS/Realty Toolkit CSV data, comparable-sale rankings, three pricing scenarios, and estimated seller net proceeds.

## Publishing

Create a GitHub repository called `AWREI-CMA-Dashboard`. Upload all files at the repository root including `.github/workflows/deploy.yml`. Under **Settings → Pages**, set the source to **GitHub Actions**. The workflow runs after a push to `main`.

Expected site URL: `https://adrianwillanger-cyber.github.io/AWREI-CMA-Dashboard/` after successful deployment.

## Privacy

This **public-safe edition** contains no workbook-derived comparables, pricing notes, property addresses, or MLS identifiers. Its example subject is fictional and for interface demonstration only. Upload CSV data directly in your own browser; it remains within the browser tab and is not sent to GitHub. Do not commit live or restricted MLS exports to a public repository. Do not assume the site provides login or persistent/private storage.

## Important caveats

Comp rankings reflect an editable heuristic scoring model, not an appraisal. Pricing timeframes and net proceeds are illustrative and must be validated with transaction data and local tax/closing cost assumptions. The empty dataset state is intentional: import verified records to produce a CMA.