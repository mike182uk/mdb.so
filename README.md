# [michaelbarrett.io](http://michaelbarrett.io)

## Prerequisites

1. [Node](http://nodejs.org/)
2. [Ruby](https://www.ruby-lang.org/)

## Install

1. Clone this repo
2. `cd` into repo and run:

```bash
gem install bundler
bundle install
npm install -g gulp
npm install
```

## Development

Run `gulp` to start developing. This will watch the project files for changes and start a local web server that can be accessed on [http://localhost:3000](http://localhost:3000).

## Deployment

The site will be deployed automatically when the master branch is pushed to github. See [.travis.yml](.travis.yml) for how this is done. The site is hosed on [Github Pages](https://pages.github.com/).

## Tools Used

- [Jekyll](https://jekyllrb.com/)
- [Gulp](http://gulpjs.com/)
- [BrowserSync](https://www.browsersync.io/)
- [SASS](http://sass-lang.com/)
- [CoffeeScript](http://coffeescript.org/)
