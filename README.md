# mitchellchatterjee.com

Personal website of Mitchell Chatterjee, built with [Hugo](https://gohugo.io) and the [Blowfish](https://blowfish.page) theme.

## Local development

Requires Hugo extended 0.164–0.167 (Blowfish v3.9 range) and Go.

```bash
hugo server
```

## Deployment

Pushing to `main` runs `.github/workflows/publish.yaml`, which builds the site and deploys to GitHub Pages at <https://mitchellchatterjee.com>.

## Structure

- `config/_default/languages.en.toml`: name, headline, social links
- `config/_default/params.toml`: theme options (layout, colour scheme, homepage)
- `content/_index.md`: homepage bio
- `content/experience/`: work history, education, skills
- `content/projects/`: project pages
- `content/publications/`: publications
- `static/uploads/resume.pdf`: downloadable CV
