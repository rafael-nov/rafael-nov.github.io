# rafaelnovais.dev

Personal hub built with [Jekyll](https://jekyllrb.com/) and a custom [no-style-please](https://github.com/riggraz/no-style-please)-based theme. Hosted on GitHub Pages at [rafaelnovais.dev](https://rafaelnovais.dev).

See [docs/FEATURES.md](docs/FEATURES.md) for the living feature status matrix, and [docs/CONTRIBUTING.md](docs/CONTRIBUTING.md) for how to add content.

## Quick start

### Docker (recommended)

```bash
docker-compose up --build
# http://localhost:4000
```

### Ruby

```bash
bundle install
bundle exec jekyll serve --livereload
```

## Site map

| Path | Purpose |
|------|---------|
| `/` | Hub: Professional → Sidequests → Personal (blog) |
| `/mainquests/` | Mainquests (email, cv, github) |
| `/cv/` | Curriculum vitae |
| `/projects/` | SW / studio projects (`0001` self-host → `0002` [RCELO-SOFTWARE](https://rcelo-software.com/)) |
| `/sidequests/` | Sidequests interests list |
| `/surf/` | Surf |
| `/mtb/` | Mountain biking |
| `/racing/` | Sim racing |
| `/auto/` | Auto / DIY mechanic |
| `/blog/` | Blog posts |

`/surf/`, `/mtb/`, `/racing/`, `/auto/` are bare stubs for now — content comes later.

## Content overview

| Type | Folder | Notes |
|------|--------|-------|
| Blog posts | `_posts/` | `YYYY-MM-DD-title.md`, `category: blog` |
| Projects | `_projects/` | `scope: software`, optional `studio` |
| Data | `_data/` | Domains, sidequests, todos, profile |

## Visibility

- **Public** — linked from hub
- **Unlisted** — built, not linked from the hub
- **Hidden / draft** — `published: false`, `visibility: hidden`, or `_drafts/`

## Deployment

Pushes to `main` deploy via GitHub Pages. Docker CI (`.github/workflows/build.yml`) smoke-tests a local build.

Experimental AWS/Terraform assets live under [`archive/`](archive/) and are not used in production.

## License

MIT — see repository license if present.
