# Sanjay H H - Developer Portfolio

A responsive React and Vite portfolio for Sanjay H H, with a Three.js interactive hero and live GitHub REST API repository integration.

## Run locally

1. Install Node.js 20 or later.
2. Install dependencies with `npm install`.
3. Start the development server with `npm run dev`.
4. Open the local URL printed by Vite.

## Build for production

Run `npm run build`. The production-ready site is written to `dist/`.

## Personalize

All portfolio configuration is intentionally easy to find near the top of `src/App.tsx`:

- `GITHUB_USERNAME` controls the live profile and repository integration.
- `CONTACT_EMAIL` activates the contact form's mail client delivery. It is left as a clear editable value because no personal email address was supplied.
- Skills, navigation, and role text are also grouped at the top of the file.

The Download Profile button generates a text profile using only the confirmed personal information on the site.

## GitHub Pages deployment

1. Push this project to a GitHub repository.
2. Build the project with `npm run build`.
3. Publish the contents of `dist/` to the `gh-pages` branch, or configure a GitHub Actions workflow to deploy that folder.
4. In the repository settings, open **Pages** and select the publishing branch/folder.

Because the GitHub data is loaded client-side from the public REST API, repositories created later appear automatically without rebuilding the website. GitHub's unauthenticated rate limit still applies.
