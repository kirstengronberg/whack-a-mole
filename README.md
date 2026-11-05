# Garden Dash

A standalone, browser-based Whack-a-Mole game and its UI wireframes.

## Play

- Open the game: [Whack-a-Mole.html](./Whack-a-Mole.html)
- Browse the screen flow: [Whack-a-Mole Wireframes.html](./Whack-a-Mole%20Wireframes.html)
- For local development, open `index.html` in a browser or serve this directory with any static web server.

The game has no build step or runtime dependencies. Scores and the top-ten leaderboard are stored in the browser's local storage, so they are private to that browser and device.

## GitHub Pages

The workflow in `.github/workflows/pages.yml` publishes the repository root when changes are pushed to `main`. A repository administrator must first open **Settings → Pages**, choose **GitHub Actions** as the build and deployment source, and save. The workflow token cannot enable Pages on a repository that has not been configured. After setup and a successful deployment, the site is available at:

<https://kirstengronberg.github.io/whack-a-mole/>
