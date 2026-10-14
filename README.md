# imenben.github.io

Personal academic website of Imen Benzarti, built with Jekyll and the Baleon theme by Artem Sheludko. GitHub Pages builds and hosts it.

## Where to edit things

| What | File |
| --- | --- |
| Name, intro, menu, social links, **News** | `_data/settings.yml` |
| Research projects (home page shows `featured: true`) | `_projects/` |
| Publications | `_publications/` (one file per paper) |
| Courses | `_teaching/` |
| Team, Join us, Community, CV, French page | `_pages/` |
| Blog posts | `_posts/` (name files `YYYY-MM-DD-title.md`) |
| Tools page (hidden) | `_pages/tools.md`, set `published: true` and uncomment the menu item |

## Run locally

```sh
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000.
