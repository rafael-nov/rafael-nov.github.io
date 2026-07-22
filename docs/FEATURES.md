# Feature Status

Living inventory of site features. Update when something ships or changes.

**Legend:** Works | Partial | Idle

| Feature | Location | Status | Notes |
|---------|----------|--------|-------|
| Homepage hub | `index.md`, `_layouts/home.html` | Works | TODO → Professional → Sidequests → Personal |
| Site TODOs | `_data/todos.yml` | Works | Index subsection for site work |
| Domain cards | `_includes/domain_card.html`, `_data/domains.yml` | Works | Section cards on the index |
| Mainquests | `mainquests.md`, `_layouts/mainquests.html` | Works | Intro + inline links (cv, email, github, linkedin…) |
| Sidequests | `sidequests.md`, `_data/sidequests.yml` | Works | Simple interests list |
| Surf / MTB / Racing / Auto | `surf.md`, `mtb.md`, `racing.md`, `auto.md` | Idle | Bare stub pages, content later |
| CV | `cv.md`, `_layouts/cv.html` | Works | Collapsible sections, skill dots |
| Projects | `_projects/`, `projects.md` | Works | Software + studio (`scope`) |
| Self-host initiative | `_projects/0001-self-host.md` | Works | Homelab / personal hosting |
| RCELO-SOFTWARE | `_projects/0002-rcelo-software.md` | Works | Studio project → [rcelo-software.com](https://rcelo-software.com/) |
| Blog | `blog.md`, `_posts/` | Works | Personal writing |
| Dark/light theme | `_config.yml`, `_sass/no-style-please.scss` | Works | CSS invert dark mode |
| RSS feed | jekyll-feed | Works | Auto-generated |
| Favicons | root icons + `site.webmanifest` | Works | Present in repo |
| Docker dev | `docker-compose.yml` | Works | Local serve |

## Content types

| Type | Directory | Key front matter |
|------|-----------|------------------|
| Blog post | `_posts/` | `category: blog` |
| Project | `_projects/` | `scope`, `status`, `visibility` |
