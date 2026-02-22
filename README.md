# hugo-theme-fs

A minimalist monospace Hugo theme. "fs" stands for [Fabien Sanglard](https://fabiensanglard.net), whose blog inspired this theme.

## Installation

```bash
git submodule add https://github.com/OctopusET/hugo-theme-fs.git themes/hugo-theme-fs
```

Then in `hugo.toml`:

```toml
theme = "hugo-theme-fs"
```

## Configuration

```toml
[markup.goldmark.renderer]
  unsafe = true

[markup.goldmark.extensions.typographer]
  disable = true
```

## Shortcodes

- `{{</* footnote "text" "url" */>}}` -- inline footnote with auto-generated references table
- `{{</* img "path" "width%" "style" */>}}` -- image with lazy loading
- `{{</* picture "path" "width%" "style" */>}}` -- picture with WebP source

## License

MIT
