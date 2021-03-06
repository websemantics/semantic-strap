```   
 _________________________    
|░░░░░░░░░░░░░░░░░░░░░░░░░░|
|░░░░░░░░░|`     ,|░░░░░░░░|
|░░░░░░░|          |░░░░░░░|
|░░░░░░░|   |░░░░░░░░░░░░░░|__.__  ___. __ .__   _._______.__  ____    ____._______.____   __  .______
|░░░░░░░|      `|░░░░░|   ____|  \/   |/  \|  \ | |        | |/    |  /    |       | _  \ /  \ |   _  \
|░░░░░░░░░░|       |░░|  |__ |  \  /  /    |   \| `--|  |--`|  ,--'__|   (-`-|  |--`|_)  |    \|  |_)  |
|░░░░░░░░░░░░░░|    |░|   __||  |\/| /  /\ |  . `  | |  | | |  |  |__|\   \  |  ||      /  /\  \   ___/     
|░░░░░░░|   `.,.   .|░|  |___|_ |  |/  ____|  |\   | |  | | |  `--.  .-)   | |  ||  |\  \ ____  \ |
|░░░░░░░░|        |░░░|_______|_|  /__/    |__| \__| |__| |__\____|  |____/  |__|| _| \__|    \__\|   
|░░░░░░░░░░░░░░░░░░░░░░░░░░|
|░░░░░░░░░░░░░░░░░░░░░░░░░░|

___  ___ ____ _  _ ___ _ ___ _  _ _      _  _ ___ ___ ___ ____    ___  ____ _ _ _ ___ ___ ___ _  _ _       
|__] |__ |__| |  |  |  | |__ |  | |      |\/| |__ |__  |  [__     |__] |  | | | | |__ |_/ |__ |  | |       
|__] |__ |  | |__|  |  | |   |__| |__    |  | |__ |__  |  ___]    |    |__| |_|_| |__ | \ |   |__| |__  


           ░░░░░░░░░░▒▒▒▒▒▒▒▓▓▓▓▓███  W O R K   I N   P R O G R E S S  ███▓▓▓▓▓▒▒▒▒▒▒░░░░░░░░░░░


```


> Beautiful and responsive CSS toolkit inspired by [Semantic-UI](http://semantic-ui.com/) and built with [Bootstrap 4](http://v4-alpha.getbootstrap.com/).

[![Build Status](https://travis-ci.org/websemantics/ant-strap.svg?branch=master)](https://travis-ci.org/websemantics/ant-strap)

### [Showcase](http://websemantics.github.io/ant-strap)&nbsp;&nbsp;&nbsp;[Getting Started](#getting-started)&nbsp;&nbsp;&nbsp;[Submit Issue](https://github.com/websemantics/ant-strap/issues)


## Getting Started

Three quick start options are available:

- [Download the latest release](https://github.com/websemantics/ant-strap/archive/1.0.0.zip).
- Clone the repo: `git clone https://github.com/websemantics/ant-strap.git`.
- Install with [Bower](http://bower.io): `bower install ant-strap`.
- Install with [npm](https://www.npmjs.com/): `npm install ant-strap`.


### What's included

Within the download you'll find the following directories and files for the framework and the docs, logically grouping common assets and providing both compiled and minified variations,

```
ant-strap/
├── dist/
|   ├── css/
│   |   ├── ant-strap.css
│   |   ├── ant-strap.css.map
│   |   └── ant-strap.min.css
│   |   └── ant-strap.min.css.map
|   ├── js/
│   |   ├── ant-strap.js
│   |   └── ant-strap.min.js
├── js/
|   ├── dist/
│   |   ├── custom.js
│   |   └── custom.min.js
|   ├── src/
│   |   ├── custom.js
│   |   └── util.js
├── docs/
|   ├── dist/
|   ├── assets/
│   |   ├── brand
│   |   ├── css
│   │   |   ├── docs.css
│   │   |   └── docs.min.css.map
│   |   ├── js
│   |   └── scss
|   └── index.html
└── scss/
    └── and-design

```

All css override styles for Bootstrap and Ant Design are stored in `scss` and `scss/primer` folders respectively, while compiled and minified CSS and JS are in `dist` folder.


## Contributions

We are more than happy to accept external contributions to the project in the form of feedback, bug reports and even better - pull requests :)

To start development on your local machine following these steps,

- First, clone,

  ```bash
  git clone https://github.com/websemantics/ant-strap
  ```

- Install npm dependencies,

  ```bash
  cd ant-strap

  npm i
  ```

- Build sass styles into `dist`,

  ```bash
  npm run build
  ```

- Build project pages into `_gh_pages`, and before running the following script, comment-out `baseurl` line in
`_config.yml` or set to empty string,

  ```bash
  npm run prep-release
  ```

- Watch changes and refresh browser automatically,

  ```bash
  npm run watch
  ```

- Deploy into Github Pages (owner),

  ```bash
  npm run deploy
  ```

### Progress

- [ ] Reset
- [ ] Site

## Screenshot

[![Semantic Strap](https://raw.githubusercontent.com/websemantics/themeblr/master/docs/assets/img/semantic-strap.png)](https://websemantics.github.io/semantic-strap/)

Love the Github *repository buttons* used and want to use them to showcase your own GitHub repositories? the name is Bragit, [Brag It](http://websemantics.github.io/bragit/).


## Resource

[Themeblr](https://websemantics.github.io/themeblr/), A powerful CSS framework boilerplate and Bootstrap 4 themes builder .

[Bootstrap 4](http://v4-alpha.getbootstrap.com/), The most popular HTML, CSS, and JS framework in the world for building responsive, mobile-first projects on the web.

[Semantic-UI](http://semantic-ui.com/), An enterprise-class UI design language and React-based implementation.

[Bootstrap 4 Cheatsheet](https://hackerthemes.com/bootstrap-cheatsheet/), A quick reference for Bootstrap v4.0.0-alpha.3.

[Awesome Semantic-UI](https://github.com/websemantics/awesome-semantic-ui/), A curated list of Semantic-UI resources and related projects.

[Semantic Ant](https://github.com/websemantics/semantic-ant), Ant Design inspired theme for [Semantic-UI](http://semantic-ui.com/).


## Support

Need help or have a question? post a questions at [StackOverflow](https://stackoverflow.com/questions/tagged/ant-strap)

*Please don't use the issue trackers for support/questions.*


## Credits

This project was built using [Ant Strap](https://websemantics.github.io/ant-strap/), on top of the awesomeness known as [Bootstrap](https://github.com/twbs/bootstrap/) and closely followed, [Ant Design](http://ant.design/).


## Copyright and license

[MIT license](http://opensource.org/licenses/mit-license.php)
Copyright (c) Web Semantics, Inc.
