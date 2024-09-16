## About

tail.css provides **a small subset** of
[tailwind](https://tailwindcss.com/)
as pure CSS files that can be used with
or without nodejs. The motivation behind
tail.css is to be able to use tailwind in
simple environments that don't have access
to nodejs or other runtimes. The [dist/](dist/)
directory includes pure CSS files that can be
easily dropped into any project.

## Build

Custom builds can customize what features are included in a build. <br>
The `@import` directives in [src/](src/) decide what features to
include:

    $ npm install -g sass
    $ bin/build

## Sources

* [GitHub](https://github.com/0x1eef/tail.css)
* [brew.bsd.cafe/@0x1eef](https://brew.bsd.cafe/0x1eef/tail.css)

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
See [LICENSE](./LICENSE)
