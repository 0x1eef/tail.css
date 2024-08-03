## About

tail.css provides _a small subset_ of
[tailwind](https://tailwindcss.com/)
that was originally extracted from a hobby project.
The CSS files [dist/tail.css](dist/tail.css)
and [dist/tail.min.css](dist/tail.min.css) are provided
in case you don't have access to the nodejs sass compiler.

## Rationale

The motivation behind this project is to be able to use tailwind
without a nodejs environment. tail.css can be used within a vanilla
CSS environment, or within an environment that uses
[sass](https://sass-lang.com).
Most of the time I use tail.css within a sass environment, and
sprinkle small amounts of CSS on top.

## Build

Custom builds can customize what features are included in a build.
The `@import` directives in [src/](src/) decide what features to
include:

    $ npm install -g sass
    $ bin/build

## License

Copyright of src/tail/ belongs to the
[tailwind project](https://tailwindcss.com/).
<br>
See [tailwindcss/LICENSE](https://github.com/tailwindlabs/tailwindcss/blob/master/LICENSE)

Copyright of src/normalize/ belongs to the
[normalize.css project](https://raw.githubusercontent.com/necolas/normalize.css).
<br>
See [normalize/LICENSE.md](https://github.com/necolas/normalize.css/blob/master/LICENSE.md)

The remaining copyright is covered by the [0BSD License](https://choosealicense.com/licenses/0bsd/).
<br>
See [./LICENSE](./LICENSE)
