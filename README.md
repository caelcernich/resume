# Cael Cernich, portfolio site

A static site. No build step, no dependencies, and no folders. Every file sits at the top level on purpose, so uploading through the GitHub website can't scramble the structure.

## Files

- `index.html`: the portfolio home page
- `real-estate.html`: interactive demo of the Real Estate dashboard
- `supplier-spend.html`: interactive demo of the Supplier Spend dashboard
- `capital.html`: interactive demo of the Capital Availability dashboard
- `headshot.jpg`: your portrait, shown in the hero

All three demos run entirely on synthetic data generated in the browser. Nothing in them is real.

## Before you publish

1. **LinkedIn:** open `index.html`, find `var LINKEDIN = '';` near the bottom, and paste your profile URL between the quotes. The button appears automatically.
2. **GitHub links:** the site assumes your GitHub username is `caelcernich` and that the Avalanche Hub lives at `https://caelcernich.github.io/avalanche-hub/`. Search `index.html` for `caelcernich` and fix any that are wrong.

## Publish it (free)

Create a public repository named exactly `<your-github-username>.github.io`. Use Add file, then Upload files, and drag in all six files. Then go to Settings, Pages, choose "Deploy from a branch," pick `main` and `/ (root)`, and save. The site appears at `https://<your-github-username>.github.io/`.
