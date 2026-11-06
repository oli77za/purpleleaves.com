# Purple Leaves

A lightweight, single-page website for Purple Leaves Ltd, built with Astro and deployed as a static site.

## Development

Requires Node.js 22 and Yarn.

```sh
yarn install
yarn dev
```

The local development server is available at `http://localhost:4321`.

## Build

```sh
yarn build
yarn preview
```

The static site is generated in `dist/`. The build output is not committed.

## Deployment

The GitHub Actions workflow in `.github/workflows/deploy.yml` builds and deploys the site to GitHub Pages when changes are pushed to `main`. Enable GitHub Pages for the repository and select **GitHub Actions** as the build and deployment source.

The site uses root-relative paths (for example, `/favicon.svg`), so configure GitHub Pages to serve it from the domain root, such as a custom domain. A repository project URL with a path segment (for example, `owner.github.io/repository/`) is not supported by this configuration.

## Customisation

Edit the page copy in `src/pages/index.md` and the page metadata in its frontmatter. Replace the clearly marked contact email placeholder before launch. Site structure is in `src/layouts/BaseLayout.astro`, visual styles are in `src/styles/global.css`, and the supplied logo variants are in `public/purple-leaves-horizontal.svg`, `public/purple-leaves-stacked.svg` and `public/favicon.svg`.
