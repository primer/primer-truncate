# Primer CSS Truncate

[![NPM version](http://img.shields.io/npm/v/primer-truncate.svg)](https://www.npmjs.org/package/primer-truncate)
[![Build Status](https://travis-ci.org/primer/truncate.svg?branch=master)](https://travis-ci.org/primer/truncate)

> .css-truncate will shorten text with an ellipsis. The maximum width of the truncated text can be changed by overriding the max-width of the .css-truncate-target.

This repository is a module of the full [primer-css][primer] repository.

## Documentation

You can read more about truncate in the [docs][docs].

## Install

This repository is distributed with [npm][npm]. After [installing npm][install-npm], you can install `primer-truncate` with this command.

```
$ npm install --save primer-truncate
```

## Usage

The source files included are written in [Sass][sass] (`scss`) You can simply point your sass `include-path` at your `node_modules` directory and import it like this.

```scss
@import "primer-truncate/index.scss";
```

You can also import specific portions of the module by importing those partials from the `/lib/` folder. _Make sure you import any requirements along with the modules._

## Build

For a compiled **css** version of this module, a npm script is included that will output a css version to `build/build.css`

```
$ npm run build
```

## Related

* [Primer Documentation][docs]
* [primer-css][primer]
* [primer-support][primer-support]

## License

MIT &copy; [GitHub](https://github.com/)

[primer]: https://github.com/primer/primer
[primer-support]: https://github.com/primer/primer-support
[docs]: http://primercss.io/
[npm]: https://www.npmjs.com/
[install-npm]: https://docs.npmjs.com/getting-started/installing-node
[sass]: http://sass-lang.com/
