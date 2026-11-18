# Cael Cernich, portfolio site

A static site. No build step, no dependencies.

## Files

- `index.html`: the whole portfolio
- `demos/real-estate/index.html`: interactive demo of the Real Estate dashboard, built entirely on synthetic data
- `headshot.jpg`: your portrait, shown in the hero

## Before you publish

1. **Headshot:** already included as `headshot.jpg`. To swap it, replace that file with another portrait (3:4 works best, around 800 x 1000 px) using the same name.
2. **Add your LinkedIn.** Open `index.html`, find `var LINKEDIN = '';` near the bottom, and paste your profile URL between the quotes. The button appears automatically.
3. **Check the GitHub links.** The site assumes your GitHub username is `caelcernich` and that the Avalanche Hub lives at `https://caelcernich.github.io/avalanche-hub/`. Search `index.html` for `caelcernich` and fix any that are wrong.

## Publish it (free)

Create a new public repository named exactly `<your-github-username>.github.io` (for example `caelcernich.github.io`). Upload these files, then go to Settings, Pages, choose "Deploy from a branch," pick `main` and `/ (root)`, and save. The site appears at `https://<your-github-username>.github.io/`.

Your existing `avalanche-hub` repository stays as it is, so the NHL app and its hourly refresh keep working.

## How the scroll reveal works

The first screen shows only the headline. Everything else fades in with a soft downward wipe tied to your scroll position, so the page "unpacks" as you move. Content stays revealed once shown. The route graphic in the hero is also scroll-driven. If a visitor has reduced motion turned on in their system settings, everything is simply visible, and printing shows everything too.

To change the pacing, edit these in the script at the bottom of `index.html`: `vh * 0.98` and `vh * 0.62` set where on the screen an item starts and finishes appearing (a wider gap means a slower reveal).
