# Website

This website is built using [Docusaurus](https://docusaurus.io/), a modern static website generator.

### Bun Stuff

  `bun start`
    Starts the development server.

  `bun run build`
    Bundles your website into static files for production.

  `bun run serve`
    Serves the built website locally.

  `bun run deploy`
    Publishes the website to GitHub pages.

We recommend that you begin by typing:

  `cd my-website`
  `bun start`

Happy building awesome websites!

### Installation

```
$ yarn
```

### Local Development

```
$ yarn start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

```
$ yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Deployment

Using SSH:

```
$ USE_SSH=true yarn deploy
```

Not using SSH:

```
$ GIT_USER=<Your GitHub username> yarn deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.
