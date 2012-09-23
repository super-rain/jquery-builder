#jQuery Builder

jQuery Builder lets you easily build a version a custom version of jQuery without downloading the source, grabbing the submodules, installing grunt and building yourself.

##Install

	npm install jquery-builder

##Usage

	jQuery Builder 0.0.3
	Usage: node ./bin/builder.js

	Options:
		-e, --exclude  Modules to exclude [module,module]              [string]
		-m, --minify   Minify output                                   [boolean]
		-l, --ls       List available modules                          [boolean]
		-v, --version  Version of jQuery to use (1.8.0, 1.8.1, 1.8.2)  [string]  [default: "1.8.2"]

##Example

	jquery-builder --exclude ajax,css -m > jquery.min.js

##Available Modules

- ajax
- deprecated
- css
- dimensions
- effects
- offset