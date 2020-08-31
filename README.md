# Node Project Template
> Template for creating new Node.js projects

[![GitHub tag](https://img.shields.io/github/tag/MichaelCurrin/node-project-template)](https://github.com/MichaelCurrin/preact-quickstart/tags/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue)](#license)


## Preview

_This is a placeholder section for a screenshot of a future app_.

    ![preview screenshot](/sample.png)


## Purpose

Why does this project exist? I'm tired of running `git init` and `npm init` and starting with an empty repo each time.  I know mostly what my git configs, `package.json` details and docs will look like and I don't want to have to type from memory or copy and paste - I want to get to the core code.

So now I just use this repo as a starting point and reference, to make new projects faster to setup and also to keep them consistent.

For Python projects, see also [py-project-template](https://github.com/MichaelCurrin/py-project-template)


## Customization
> Things to do once you've created a new project from this one

- [ ] Update title and description of this doc
- [ ] Add/update badges
- [ ] Update package.json with scripts and dependencies
- [ ] Develop your core app
- [ ] Choose a test framework (jest, enzyme, mocha...) and write tests with it. Bonus points if you write tests before you app!
- [ ] Customize lint config
    - Edit the exiting [.eslintrc.js](/.eslintrc.js) config.
    - Or create a new one.
        ```sh
        rm .eslintrc.js
        node_modules/.bin/eslint --init
        ```
    - Or add an `eslintConfig` field to [package.json](/package.json).
- [ ] Customize build flow
    - For now JS scripts are just copied to `build` but you might use `dist` or `out` instead.
    - You might use TypeScript or Babel to handle this for you and then split out `build` and `compile` steps.
    - Or maybe you have no build command and so this can beremoved from [package.json](/package.json).
- [ ] Update docs such as usage instructions and add sample image to `Preview` section.
- [ ] Optional - add docs folder built around a Docsify site, then enable as GitHub Pages site. See my [Docsify quickstart instructions](https://github.com/MichaelCurrin/docsify-js-template#b-add-docsify-to-an-existing-projects-docs-directory)
- [ ] Update license file details if needed (change type and put on your own name)
- [ ] Add CI/CD - link TBC
- [ ] Delete this section!


## Documentation

...


Either delete Documentation section and the docs directory, or delete Installation and Usage below, depending on if how complex your app is and if you want one doc or several.

...


## License

Released under [MIT](/LICENSE).

TBC...
