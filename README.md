# hubblejs.com

This site uses a modified version of [Flatdoc](https://github.com/rstacruz/flatdoc) to load in the README.md file from the [HubbleJS](https://github.com/Polyneue/hubblejs) repo.

## Developing
The current build is simple, start by installing the dependencies:

```
$ npm install
```

Then, run two separate processes that will compile the CSS and start a server on `http://localhost:1313`

```
$ npm run build
$ npm run serve
```

## Deploying

The site is automatically deployed when commits land in `master`, via [Github Pages](https://pages.github.com/).

## TODO:
* Create build process for JS
* Switch from Stylus to SCSS
* Remove flatdoc for a lighter weight version