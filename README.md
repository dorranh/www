# www

[![Netlify Status](https://api.netlify.com/api/v1/badges/de5715b8-86cf-4b23-8168-73f9734ff266/deploy-status)](https://app.netlify.com/sites/appalachian/deploys)

My personal website, [`appalachian.dev`](https://appalachian.dev).

## Adding Content

Content is stored as MDX files under [`src/content`](./src/content/).

## Development

This is a fairly run-of-the-mill [Astro](https://astro.build) project which can
be built using NPM.

You can use the project's Nix flake to get a development shell with all required dependencies.

```sh
nix develop
```

Then install the NodeJS dependencies using NPM:

```sh
npm install
```

And to launch the site locally:

```sh
npm start
```

## Credit

This website was built off of the [Pacamara Astro theme](https://github.com/palmiak/pacamara-astro). Special thanks to its
author!
