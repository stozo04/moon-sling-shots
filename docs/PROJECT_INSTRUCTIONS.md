# Moon Sling Shots project instructions

The game lives in index.html, with Three.js loaded from a CDN. Preserve the single-file/no-build structure; use README.md for gameplay. Pull distance sets power, angle sets trajectory, collected stars add escalating bonuses, and best score/lifetime stars persist in localStorage. Keep mouse/touch controls, reset, mobile HUD, and existing analytics behavior.

Serve locally with npm run dev or the README's HTTP-server command. npm test runs the agent synchronization check and its regression cases; it does not prove gameplay. For game or UI changes, play the affected launch/reset/scoring flows in a browser and check desktop/touch layouts. Report skipped checks. No browser run is needed solely to reconcile instruction files.

Use a branch from main and a pull request. Preserve the Vercel hosting setup; merges, releases, and deployments need their own authorization.
