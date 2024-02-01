## About

tail.css provides _a small subset_ of
[tailwind](https://tailwindcss.com/)
that has been extracted from a hobby project. A prebuilt copy of
[dist/tail.css](dist/tail.css)
is provided in case you don't have access to the nodejs sass compiler,
along with a minimized copy
([dist/tail.min.css](dist/tail.min.css)).
There are gzip-compressed copies of those files included in
[dist/](dist/)
- `tail.css.min.gz`` weighs in at around 8.5KB.

## Why ?

I found it to be near impossible to use tailwind without a nodejs
environment. But not every project I work on has nodejs available.
That's why I decided to build a vanilla CSS file I could include
in any project - with or without nodejs.

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
