# tristan-portfolio

Personal portfolio and blog, built with [Hugo](https://gohugo.io).

## Local development

```bash
hugo server -D
```

Serves the site at `http://localhost:1313` with drafts included. To build the
static site into `public/`:

```bash
hugo
```

## Theme

Built with the [Ananke](https://github.com/gohugo-ananke/ananke) theme,
© Bud Parr and Patrick Kollitsch, MIT licensed.

Ananke is installed as a **Hugo Module**, not a git submodule — it is referenced
from `go.mod` and `go.sum` and fetched into Hugo's module cache on first build.
A fresh clone needs nothing extra; there is no `git submodule update --init`
step. To update the theme:

```bash
hugo mod get -u
```

## License

Three different terms apply in this repository:

- **Code** — layouts, configuration, styles, and build files: [MIT](LICENSE)
- **Content** — posts, project write-ups, and original images under `content/`:
  [CC BY-NC 4.0](content/LICENSE)
- **Photographs of the author** — including `static/images/img.png`:
  **all rights reserved.** Not covered by either license above; no reuse,
  modification, or redistribution without permission.

Third-party material retains its own license terms.
