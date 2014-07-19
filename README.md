# Critical-path demo using AngularJS

> Above-the-fold CSS generation + inlining using [Critical](http://github.com/addyosmani/critical) & Gulp

Compare the [normal](http://addyosmani.github.io/critical-path-angular-demo/output/normal/) output with the [critical-path CSS optimized](http://addyosmani.github.io/critical-path-angular-demo/output/critical/) version.


## Installation

```sh
$ cd critical-path-angular-demo
$ npm install && bower install
```

## Usage

You have two options:

The normal build:

```sh
gulp
```

Build including critical-path CSS extraction & inlining:

```sh
gulp critical
```

Either option will write the output to the `dist` directory.