clingwrap [![NPM version](https://badge.fury.io/js/clingwrap.png)](http://badge.fury.io/js/clingwrap) [![Build Status](https://travis-ci.org/goodeggs/clingwrap.png)](https://travis-ci.org/goodeggs/clingwrap)
==============

Command line tool for predictable npm-shrinkwrap updates.  Tired of [unexpected changes to npm-shrinkwrap](https://github.com/npm/npm/issues/3581) when you just want to update a package?  Just `clingwrap foo-package`.

```sh
$ npm install -g clingwrap
```

```

  Usage: clingwrap [npmbegone] <package ...>

  Commands:

    npmbegone              strip hardcoded npmjs.org urls from shrinkwrap for faster installs
    *                      update or remove shrinkwrap for named package(s) and dependencies

  Options:

    -h, --help     output usage information
    -V, --version  output the version number


```
