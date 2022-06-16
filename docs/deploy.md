# Deploy


## Build app

Run a local production-optimized build.

```sh
$ npm run build
```


## Release

This will run checks and tests, increment the tag version and push the new tagged commit.

```sh
$ npm version minor
```


## Deploy pipeline

This project will run checks and build steps on [GitHub Actions](https://github.com/features/actions) on every commit or push on the `master` branch. 

See the [workflow](/.github/workflows/main.yml) config file.

See results on the [Actions](https://github.com/MichaelCurrin/node-project-template/actions/) tab.


### Note
> A comment on the limitation of this template project

Add your deploy instructions here. Such as now to deploy to GH Pages, Netlify, Vercel, etc.

With the current flow **nothing is persisted** after a build, so this on a CI flow and not a CD flow. 

If you want to deploy your React/Vue app to GitHub Pages, follow this page: [GH Pages workflow](https://github.com/MichaelCurrin/code-cookbook/blob/master/recipes/ci-cd/github-actions/workflows/node/gh-pages.md).
