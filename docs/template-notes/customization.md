# Customization
> Customize this app to make it your own

Things to do once you've created a new project from this one:

- [ ] Update title and description of the docs.
- [ ] Add/update badges.
- [ ] Update package.json with scripts and dependencies.
- [ ] Develop your core app.
- [ ] Choose a test framework (Jest, Jasmine, Enzyme, Mocha...) and write tests with it. Bonus points if you write tests before your app for true TDD!
- [ ] Customize lint config:
    - Edit the exiting [.eslintrc.js](/.eslintrc.js) config.
    - Or create a new one:
        ```sh
        rm .eslintrc.js
        npx eslint --init
        ```
    - Or add an `eslintConfig` field to [package.json](/package.json).
- [ ] Update ignore file. 
    - If you use Yarn, take out `npm-debug.log*` and add:
        ```
        yarn-debug.log*
        yarn-error.log*
        ```
- [ ] Add other build tools like Prettier, Husky, Webpack, Vite, or Babel.
- [ ] Customize your build flow:
    - For now JS scripts are just copied to `build` but you might use `dist` or `out` instead.
    - You might use TypeScript or Babel to handle this for you and then split out `build` and `compile` steps.
    - Or maybe you have no build command and so this can beremoved from [package.json](/package.json).
- [ ] Update docs such as usage instructions and add sample image to `Preview` section.
- [ ] Optional - setup the docs directory to server as a _Docsify_ docs site, then enable as GitHub Pages site. See my [Docsify quickstart instructions](https://github.com/MichaelCurrin/docsify-js-template#b-add-docsify-to-an-existing-projects-docs-directory)
- [ ] Update license file details if needed (change type and put on your own name).
- [ ] Customize CI/CD flow.
    - See [Deploy](deploy.md) doc for how this currently works.
    - If you need a more advanced workflow for GitHub Actions, see [Node workflow samples](https://github.com/MichaelCurrin/code-cookbook/tree/master/recipes/ci-cd/github-actions/workflows/node).
- [ ] Add credits
    - [ ] Add a link back to the original repo in - https://github.com/MichaelCurrin/node-project-template
    - [ ] Copy the original license and then put your own name in `LICENSE` file.
        ```sh
        $ cp LICENSE LICENSE-source
        $ edit LICENSE
        ```
- [ ] Delete unneeded sections in `README.md` doc.
- [ ] Delete the `template-notes` directory in `docs/`.
- [ ] Containerize your app. See [Docker Node app quickstart](https://github.com/MichaelCurrin/docker-quickstarts/tree/master/examples/node_app)
