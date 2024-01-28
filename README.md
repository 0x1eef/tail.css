## About

tail.css provides a small subset of
[tailwind](https://tailwindcss.com/)
that has been extracted from a hobby project. A prebuilt copy of
[dist/tail.css](dist/tail.css)
is provided in case you don't have access to the Ruby sass compiler,
along with a minimized copy
([dist/tail.min.css](dist/tail.min.css)).
There are compressed copies of those files included in
[dist/](dist/) - they weigh in at around 6KB.

## Why ?

I found it to be near impossible to use tailwind without a nodejs
environment. But not every project I work on has nodejs available.
That's why I decided to build a vanilla CSS file I could include
in any project - with or without nodejs.

## Build

Custom builds provide a way to customize what features are
included in a build. The `@import` directives in [src/](src/)
decide what features to include:

    $ bin/build

## License

Copyright belongs to the
[tailwind project](https://tailwindcss.com/).
<br>
See [tailwindcss/LICENSE](https://github.com/tailwindlabs/tailwindcss/blob/master/LICENSE).
