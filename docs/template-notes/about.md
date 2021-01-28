# About

<!-- 
This page can be removed when making a new project from this one, but the documentation section of README.md and the docs directory would be good to keep.
-->

This is a template project for new JavaScript projects, whether making a frontend app, server-side app or CLI tool.


## How to use this template

<div align="center">

[![Use this template](https://img.shields.io/badge/Use_template-Generate-2ea44f?style=for-the-badge&logo=github)](https://github.com/MichaelCurrin/node-project-template/generate)

</div>

1. Click the button above to generate a new repo based on this template.
2. Install the app locally using the [Installation](/docs/installation.md) doc.
3. Run it locally using the [Usage](/docs/usage.md) docs.
3. Follow the [Customization](/docs/customization.md) doc.


## What is included

This template saves you time as it already contains boilerplate that will work for most projects:

- Base files
    - [.gitignore](/.gitignore) file
    - [package.json](/package.json) file
    - [src](/src/) directory.
- Linting with ESLint.
- Boilerplate documentation in the [docs](/docs/) directory.
- A CI [workflow](/.github/workflows/main.yml) to lint, test and build using GitHub Actions 

The `test` command in the package file is just a placeholder - you'll have to setup a test suite yourself as recommended in the Customization doc.


## Purpose

Why does this project exist? I'm tired of running `git init` and `npm init` and starting with an empty repo each time.  I know mostly what my git configs, `package.json` details and docs will look like and I don't want to have to type from memory or copy and paste - I want to get to the core code.

So now I just use this repo as a starting point and reference, to make new projects faster to setup and also to keep them consistent.

This project is deliberately open-ended so you can make choices about your own NPM commands and test framework. The only dependency here is _ESLint_.
