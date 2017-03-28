# Stylish Styles
This repo is where I store the styles that I write for the Stylish chrome extension, mostly consisting of dark themes for various sites.

## Setup
This project is written in SCSS.  In order to get usable CSS, the SCSS needs to be transcompiled.

To get started:
```
$ npm install
$ npm start
```

## Package.json
Using [node-sass](https://github.com/sass/node-sass) for compilation and [nodemon](https://github.com/remy/nodemon) for file watching.  The advantage of this over just using the `-w` flag for `node-sass` is that nodemon will compile the files initially and then begin watching the directory, instead of just watching for new changes.  Oh and it has pretty colors too.

An alternative watch script (in package.json) could be:
```
"watch": "node-sass -w scss -o css",
```
