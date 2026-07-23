# Feature Status

Living inventory of site features. Update when something ships or changes.

**Legend:** Works | Partial | Idle

| Feature | Location | Status | Notes |
|---------|----------|--------|-------|
| Homepage hub | `index.md`, `_layouts/home.html` | Works | TODO → Professional → Sidequests → Personal |
| Site TODOs | `_data/todos.yml` | Works | Index subsection for site work |
| Domain cards | `_includes/domain_card.html`, `_data/domains.yml` | Works | Section cards on the index |
| Mainquests | `mainquests.md`, `_layouts/mainquests.html` | Works | Intro + links (cv, linkedin, github) |
| Sidequests | `_data/sidequests.yml`, `sidequests.md` | Works | Numbered list, no pages yet |
| CV | `cv.md`, `_layouts/cv.html` | Works | Collapsible sections, skill dots |
| Projects | `_projects/`, `projects.md` | Works | Software + studio (`scope`) |
| Blog | `blog.md`, `_posts/` | Works | Personal writing |
| Docker dev | `docker-compose.yml` | Works | Local serve |

## Content types

| Type | Directory | Key front matter |
|------|-----------|------------------|
| Blog post | `_posts/` | `category: blog` |
| Project | `_projects/` | `scope`, `status`, `visibility` |
| Sidequest | `_data/sidequests.yml` | `number`, `title` |
