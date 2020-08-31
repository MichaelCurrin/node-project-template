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
- [ ] Add credits
    - [ ] Add a link back to the original repo in - https://github.com/MichaelCurrin/node-project-template
    - [ ] Copy the original license and then put your own name in `LICENSE` file.
        ```sh
        $ cp LICENSE LICENSE-source
        $ edit LICENSE
        ```
- [ ] Delete unneeded sections in README.md doc.
- [ ] Delete this customization doc.
