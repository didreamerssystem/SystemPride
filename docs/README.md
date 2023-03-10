# SystemPride docs
The documentation is built using [Vuepress](https://vuepress.vuejs.org/). All website content is located in the `content/` subdirectory.

Most site parameters, including the sidebar layout, are defined in `content/.vuepress/config.js`. Some additional CSS is defined in `content/.vuepress/styles`.

## Building
First, install [Node.js](https://nodejs.org/en/download/) and [Yarn](https://classic.yarnpkg.com/en/). Then, run the `dev` command:

```sh
$ yarn
$ yarn dev
```

This will start a development server on http://localhost:8080/. Note that changes to the sidebar or similar generally need a full restart (Ctrl-C) to take effect, while content-only changes will hot-reload.

For a full HTML build, run `yarn build`. Files will be output in `content/.vuepress/dist` by default.

## Deployment
The docs are deployed using [Netlify](https://www.netlify.com/) with CI.