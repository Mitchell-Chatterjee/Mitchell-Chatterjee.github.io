# mitchellchatterjee.com

Personal website of Mitchell Chatterjee, built with [Hugo](https://gohugo.io) and the [Hugo Blox](https://hugoblox.com) Tailwind theme.

## Local development

Requires Hugo extended 0.135.0 and Go.

```bash
hugo server
```

## Deployment

Pushing to `main` runs `.github/workflows/publish.yaml`, which builds the site, generates the Pagefind search index, and deploys to GitHub Pages at <https://mitchellchatterjee.com>.

## Structure

- `content/authors/admin/_index.md`: profile, education, work history, skills
- `content/_index.md`: homepage sections
- `content/project/`: project pages
- `content/publication/`: publications
- `static/uploads/resume.pdf`: downloadable CV
