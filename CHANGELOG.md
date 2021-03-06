### 0.0.9
* Include dot files when moving files to dest directory.
* Fixed a regression on tests.

### 0.0.8
* Added tests
* Fixed the issue with relative paths pointing to tmp directories, see [issue](https://github.com/g13013/broccoli-compass/issues/7)
* Added ignoreErrors option

### 0.0.7
* Use `dargs` module in place of builtin generateArgs function
* Use `merge` module in place of builtin merge function

### 0.0.6
* Added CHANGELOG.md file
* Use `broccoli-caching-writer` in place of `broccoli-writer` to improve performance

### 0.0.5
* Better error reporting
* Added support for compass multiple values options (example: multiple import-path)

### 0.0.4
* [Bugfix] A bug relative to command line generation, see [commit](https://github.com/g13013/broccoli-compass/commit/80908a012943c95d76431d19bad688163c2bf27a).
* Add ability to specify an alternative compass command
