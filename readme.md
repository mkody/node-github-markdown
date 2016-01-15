# [node-github-markdown](https://npmjs.org/package/github-markdown)

[![Build Status](https://travis-ci.org/mkody/node-github-markdown.svg?branch=master)](https://travis-ci.org/mkody/node-github-markdown)
[![GitHub version](https://badge.fury.io/gh/mkody%2Fnode-github-markdown.svg)](http://badge.fury.io/gh/mkody%2Fnode-github-markdown)
[![Dependency Status](https://david-dm.org/mkody/node-github-markdown.svg)](https://david-dm.org/mkody/node-github-markdown)
[![devDependency Status](https://david-dm.org/mkody/node-github-markdown/dev-status.svg)](https://david-dm.org/mkody/node-github-markdown#info=devDependencies)

## About

Parse GitHub flavored markdown to static html.

## Usage

Install.

```sh
$ git clone https://github.com/mkody/node-github-markdown.git
$ cd node-github-markdown
$ npm install -g .
```

Parse markdowns.

```sh
$ ghmd readme.md
```

### `--title`

Specify HTML title.

```sh
$ ghmd --title Target target.md
```

### `--dest`

Specify the destination file path.

```sh
$ ghmd --dest index.html readme.md
```

### `--template`

Specify custom template (defaults to standard template)

```sh
$ ghmd --template custom.jade markdown.md
```

### `--help`

Show help message.

### `--version`

Show package version.

## Sublime Text Build File

The `ghmd.sublime-build` can be used as a build file for Sublime Text (at least the version 3).
It will create the *.html* file on the parrent directory of the .md file. I'm using this as the *.md* files are in a "source" folder (currently only tested on Windows).

## License

MIT: http://1000ch.mit-license.org
