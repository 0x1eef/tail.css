## About

tail.css provides _a small subset_ of
[tailwind](https://tailwindcss.com/)
that was originally extracted from a hobby project. A prebuilt copy of
[dist/tail.css](dist/tail.css)
is provided in case you don't have access to the nodejs sass compiler,
along with a minimized copy
([dist/tail.min.css](dist/tail.min.css)).
There are gzip-compressed copies of those files included in
[dist/](dist/)
... `tail.css.min.gz` weighs in at around 8.5KB.

## Rationale

The motivation behind this project is to be able to use tailwind
without a nodejs environment. You can use tail.css within a vanilla
CSS environment, or within an environment that uses
[sass](https://sass-lang.com).
Most of the time I use tail.css within a sass environment, and
sprinkle small amounts of CSS on top.

## Build

Custom builds provide a way to customize what features are
included in a build. The `@import` directives in [src/](src/)
decide what features to include:

    $ npm install -g sass
    $ bin/build

## License

Copyright of src/tail/ belongs to the
[tailwind project](https://tailwindcss.com/).
<br>
See [tailwindcss/LICENSE](https://github.com/tailwindlabs/tailwindcss/blob/master/LICENSE).

Copyright of src/normalize/ belongs to the
[normalize.css project](https://raw.githubusercontent.com/necolas/normalize.css).
<br>
See [normalize/LICENSE.md](https://github.com/necolas/normalize.css/blob/master/LICENSE.md).

The remaining copyright is covered by the [0BSD License](https://choosealicense.com/licenses/0bsd/).
<br>
See [./LICENSE](./LICENSE).
