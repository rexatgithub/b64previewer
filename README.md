# b64previewer
https://rexatgithub.github.io/b64previewer/

A simple single-file base64 image previewer.

## Usage

Open `index.html` in a browser, then either:

**Paste** a base64 string or data URI into the textarea — the image renders automatically.

```
index.html?image=iVBORw0KGgo...
```

## Supported input formats

- Bare base64 string — `iVBORw0KGgo...`
- Full data URI — `data:image/png;base64,iVBORw0KGgo...`
- URL-safe base64 — `-` and `_` are normalised to `+` and `/` automatically
