# Garden Dash

A standalone, browser-based Whack-a-Mole game and its UI wireframes.

## Play

- Open the game: [Whack-a-Mole.html](./Whack-a-Mole.html)
- Browse the screen flow: [Whack-a-Mole Wireframes.html](./Whack-a-Mole%20Wireframes.html)
- For local development, open `index.html` in a browser or serve this directory with any static web server.

The game has no build step or runtime dependencies. Scores and the top-ten leaderboard are stored in the browser's local storage, so they are private to that browser and device.

## GitHub Pages

The workflow in `.github/workflows/pages.yml` publishes the repository root when changes are pushed to `main`. Once Pages is enabled for the repository, the site is available at:

<https://kirstengronberg.github.io/whack-a-mole/>

If the initial deployment cannot enable Pages automatically, a repository administrator must enable GitHub Pages with **GitHub Actions** as the build and deployment source in the repository's Pages settings.
