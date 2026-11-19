# Cael, portfolio site

A static site. No build step, no dependencies, and no folders. Every file sits at the top level on purpose, so uploading through the GitHub website can't scramble the structure.

## Files

- `index.html`: the portfolio home page
- `real-estate.html`: interactive demo of the Real Estate dashboard
- `supplier-spend.html`: interactive demo of the Supplier Spend dashboard
- `capital.html`: interactive demo of the Capital Availability dashboard
- `headshot.jpg`: your portrait, shown in the hero and the top navigation
- `gt-logo.png`: the Georgia Tech mark shown in the education badge

All three demos run entirely on synthetic data generated in the browser. Nothing in them is real.

## Before you publish

1. **LinkedIn:** open `index.html`, find `var LINKEDIN = '';` near the bottom, and paste your profile URL between the quotes. The button appears automatically.
2. **GitHub links:** the site assumes your GitHub username is `caelcernich` and that the Avalanche Hub lives at `https://caelcernich.github.io/avalanche-hub/`. Search `index.html` for `caelcernich` and fix any that are wrong.

## Publish it (free)

Create a public repository named exactly `<your-github-username>.github.io`. Use Add file, then Upload files, and drag in all seven files. Then go to Settings, Pages, choose "Deploy from a branch," pick `main` and `/ (root)`, and save. The site appears at `https://<your-github-username>.github.io/`.

## Linking straight to a case study

Each case study has its own link. Add the project's ID to your site address: `#case-real-estate`, `#case-supplier-spend`, `#case-capital`, `#case-mhe`, `#case-digital-twin`, `#case-assortment`, or `#case-avalanche`. For example, `https://caelcernich.github.io/#case-capital` opens that case study directly. The "Copy link to this case study" button inside each pop-up does the same thing.

## Editing your role lines

Each project's "My role" text lives in the `ROLES` list near the top of the script in `index.html`. The first entry is the short version shown on the card, and the second is the longer version shown in the pop-up.

## Quick editing guide

Open `index.html` in any text editor. The very top of the file has a "How to edit this site" guide, and every section has a labeled note above it that says exactly which words to change. Project text, tool descriptions, and "My Role" lines live in labeled lists near the bottom of the file, inside the script.
