# hack-feed

This project is generated with [yo angular generator](https://github.com/yeoman/generator-angular)
version 0.12.1.

## Installing dev tools
From nothing, download and install [node.js](https://nodejs.org).  This will include `npm`, the node package manager.

Then, install packages from npm (I had to do this as root to install globally)

```
npm install -g grunt-cli
npm install -g bower
npm install -g yo
npm install -g generator-angular
```

You need to install `ruby` and `gem` to get `compass` to compile SASS into CSS.

```
gem install compass
```

## Build & development

When npm or bower dependencies have changed (or after a clean clone), run

```
npm install && bower install
```

Run `grunt` for building and `grunt serve` for preview.

## Testing

Running `grunt test` will run the unit tests with karma.
