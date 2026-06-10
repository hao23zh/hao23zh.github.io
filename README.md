# Hao Zhou Homepage

This is a Quarto website. Edit the source files, then render to update the
published files in `docs/`.

## Common Edits

- Homepage: `index.qmd`
- Site navigation and metadata: `_quarto.yml`
- News table: `posts/post-links.yml`
- Notes list: generated from `notes/*/index.qmd`
- Note pages: `notes/`
- Publications table: `publications/paper.yml`
- Talks and slides: `talks.qmd` and `publications/talks/`
- Contact page: `contact.qmd`
- Global styles: `styles.css`
- Images and CV: `files/`

## Render

```powershell
quarto render
```

GitHub Pages should publish from the `docs/` directory.
