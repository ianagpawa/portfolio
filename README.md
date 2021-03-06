# [Start Bootstrap - Grayscale](https://startbootstrap.com/themes/grayscale/)

[Grayscale](https://startbootstrap.com/themes/grayscale/) is a multipurpose, one page HTML theme for [Bootstrap](https://getbootstrap.com/) created by [Start Bootstrap](https://startbootstrap.com/).

## Preview

[![Grayscale Preview](https://startbootstrap.com/assets/img/screenshots/themes/grayscale.png)](https://startbootstrap.github.io/startbootstrap-grayscale/)

**[View Live Preview](https://startbootstrap.github.io/startbootstrap-grayscale/)**

## Status

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/StartBootstrap/startbootstrap-grayscale/master/LICENSE)
[![npm version](https://img.shields.io/npm/v/startbootstrap-grayscale.svg)](https://www.npmjs.com/package/startbootstrap-grayscale)
[![Build Status](https://travis-ci.org/StartBootstrap/startbootstrap-grayscale.svg?branch=master)](https://travis-ci.org/StartBootstrap/startbootstrap-grayscale)
[![dependencies Status](https://david-dm.org/StartBootstrap/startbootstrap-grayscale/status.svg)](https://david-dm.org/StartBootstrap/startbootstrap-grayscale)
[![devDependencies Status](https://david-dm.org/StartBootstrap/startbootstrap-grayscale/dev-status.svg)](https://david-dm.org/StartBootstrap/startbootstrap-grayscale?type=dev)

## Download and Installation

To begin using this template, choose one of the following options to get started:

- [Download the latest release on Start Bootstrap](https://startbootstrap.com/themes/grayscale/)
- Install using npm: `npm i startbootstrap-grayscale`
- Clone the repo: `git clone https://github.com/StartBootstrap/startbootstrap-grayscale.git`
- [Fork, Clone, or Download on GitHub](https://github.com/StartBootstrap/startbootstrap-grayscale)

## Usage

### Basic Usage

After downloading, simply edit the HTML and CSS files included with `dist` directory. These are the only files you need to worry about, you can ignore everything else! To preview the changes you make to the code, you can open the `index.html` file in your web browser.

### Advanced Usage

Clone the source files of the theme and navigate into the theme's root directory. Run `npm install` and then run `npm start` which will open up a preview of the template in your default browser, watch for changes to core template files, and live reload the browser when changes are saved. You can view the `package.json` file to see which scripts are included.

#### npm Scripts

- `npm run build` builds the project - this builds assets, HTML, JS, and CSS into `dist`
- `npm run build:assets` copies the files in the `src/assets/` directory into `dist`
- `npm run build:pug` compiles the Pug located in the `src/pug/` directory into `dist`
- `npm run build:scripts` brings the `src/js/scripts.js` file into `dist`
- `npm run build:scss` compiles the SCSS files located in the `src/scss/` directory into `dist`
- `npm run clean` deletes the `dist` directory to prepare for rebuilding the project
- `npm run start:debug` runs the project in debug mode
- `npm start` or `npm run start` runs the project, launches a live preview in your default browser, and watches for changes made to files in `src`

You must have npm installed in order to use this build environment.

## Bugs and Issues

Have a bug or an issue with this template? [Open a new issue](https://github.com/StartBootstrap/startbootstrap-grayscale/issues) here on GitHub or leave a comment on the [theme overview page at Start Bootstrap](https://startbootstrap.com/themes/grayscale/).

## About

Start Bootstrap is an open source library of free Bootstrap themes and templates. All of the free themes and templates on Start Bootstrap are released under the MIT license, which means you can use them for any purpose, even for commercial projects.

- <https://startbootstrap.com>
- <https://twitter.com/SBootstrap>

Start Bootstrap was created by and is maintained by **[David Miller](http://davidmiller.io/)**.

- <http://davidmiller.io>
- <https://twitter.com/davidmillerskt>
- <https://github.com/davidtmiller>

Start Bootstrap is based on the [Bootstrap](https://getbootstrap.com/) framework created by [Mark Otto](https://twitter.com/mdo) and [Jacob Thorton](https://twitter.com/fat).

## Copyright and License

Copyright 2013-2020 Start Bootstrap LLC. Code released under the [MIT](https://github.com/StartBootstrap/startbootstrap-grayscale/blob/gh-pages/LICENSE) license.


Update dist folder to docs in scrips
For the sake of this example, let’s pretend the subfolder containing your site is named `dist`.

### Step 1

Remove the `dist` directory from the project’s `.gitignore` file (it’s ignored by default by Yeoman).

### Step 2

Make sure git knows about your subtree (the subfolder with your site).

```sh
git add dist && git commit -m "Initial dist subtree commit"
```

### Step 3

Use subtree push to send it to the `gh-pages` branch on GitHub.

```sh
git subtree push --prefix dist origin gh-pages
```

Boom. If your folder isn’t called `dist`, then you’ll need to change that in each of the commands above.

On master.
Need to define the build first initial build.
But then may only need to push to master on wards.  
Looking for /docs on master.
do feature branches, then merge to master with git merge --squash branchName