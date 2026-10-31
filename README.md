# ✦ NEBULA

**Build beyond the stars.** NEBULA is a browser-based incremental idle game about turning a tiny Flux reactor into a cosmic energy empire.

## Play

Open [`index.html`](index.html) locally, or publish the repository with GitHub Pages.

## Features

- Manual Flux clicking and passive Flux-per-second production
- Eight generator tiers with escalating costs and output
- Upgrade shop for clicking, automation, critical harvesting, research, and synergies
- Four research disciplines with branching progression
- Overdrive active ability and random production anomalies
- Contracts, milestones, and empire statistics
- Singularity prestige and permanent Dark Matter upgrades
- Offline earnings (up to 8 hours, at 50% of normal production)
- Automatic local saves plus JSON export/import
- Responsive mobile-first controls and layouts
- No external libraries, APIs, or build tools

## Run locally

Download the repository and open `index.html` in a modern browser. For the best PWA installation behavior, serve it over HTTPS (GitHub Pages does this automatically).

## Publish with GitHub Pages

1. Create a GitHub repository named `nebula` (or any name you prefer).
2. Upload the contents of this project to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **GitHub Actions** as the source.
5. Push to the `main` branch. The included workflow publishes the site.
6. Your site will appear at `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

If you prefer the simpler Pages deployment, you can also select **Deploy from a branch**, choose `main` and `/ (root)`.

## Save data

The game stores progress in browser local storage on the current device and browser profile. Use Settings → Export Save to create a backup. Import that JSON file on another device to transfer progress. Clearing browser data can erase local saves.

## Project structure

```text
nebula/
├── index.html
├── manifest.json
├── css/style.css
├── js/game.js
├── pages/
│   ├── guide.html
│   ├── changelog.html
│   └── statistics.html
├── assets/icons/nebula.svg
└── .github/workflows/pages.yml
```

## Version

`0.1.0` · Initial playable release

## License

MIT. See [LICENSE](LICENSE).
