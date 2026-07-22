# Adding content

Conventions for keeping the hub consistent. Prefer lowercase titles in lists (`theme_config.lowercase_titles`).

## Blog post

1. Create `_posts/YYYY-MM-DD-slug.md`
2. Front matter:

```yaml
---
layout: post
category: blog
title: "My post"
date: 2025-07-21
published: true
---
```

Use `published: false` or move the file to `_drafts/` to keep it out of the build.

## Project

1. Create `_projects/XXXX-slug.md` (number sorts descending on lists)
2. Front matter:

```yaml
---
layout: project
title: "Project name"
category: project
project_number: "0003"
start_date: 2025-07-21
last_updated: 2025-07-21
status: "In Progress"   # Planning | In Progress | On Hold | Completed | Archived
scope: software
studio: "RCELO-SOFTWARE" # optional brand
featured: true
visibility: public
tech_stack: ["Jekyll"]
github_url: "https://github.com/..."
---
```

- All projects use `scope: software`; use `studio:` when it’s RCELO work
- Self-host is `0001`; [RCELO-SOFTWARE](https://rcelo-software.com/) is `0002`

## Site TODOs (index)

Edit `_data/todos.yml`. Items show under the `todo` divider at the top of the homepage. Delete an item when it’s done.

## Hub domains

Edit `_data/domains.yml`. Sections control homepage order:

- `professional` — mainquests (CV / contact), SW projects (pays the bills)
- `sidequests` — surf, mtb, sim racing, auto
- `personal` — blog (end of homepage)

### Add a sidequest interest

1. Append under `interests` in `_data/sidequests.yml` (`name`, optional `url`)
2. Optional: add a stub page later (`layout: page`) and point `url` at it

Homepage links to `/sidequests/`.

## Unlisted pages

Create a page with a `permalink:` and **do not** add it to `_data/domains.yml`. It gets built but stays out of the nav — share the URL directly.

## Site config

Key knobs in `_config.yml`:

- `description`
- `theme_config.appearance`: `light` | `dark` | `auto`
- Collections: `projects`

## Feature tracking

When you add or retire a feature, update [FEATURES.md](FEATURES.md).
