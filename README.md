# openautonomylab.github.io

Source for the Open Autonomy Lab website, built with Jekyll and the
[Bulma Clean Theme](https://github.com/chrisrhymes/bulma-clean-theme)
(adapted from [castacks.github.io](https://github.com/castacks/castacks.github.io)).

Pages: Home, Team, Research, Publications, Openings, Contact.

## Local development

```bash
docker compose up
```

or, with Ruby installed:

```bash
bundle install
bundle exec jekyll serve
```

Then visit http://localhost:4000.

## Structure

- `index.md`, `team.md`, `research/index.html`, `publications.md`, `openings.md`, `contact.md`
  — the six top-level pages, linked from `_data/navigation.yml`.
- `_team/` — one Markdown file per team member (`_team/example_member.md` is a placeholder —
  duplicate it per member and delete the example).
- `_posts/` — research project write-ups; posts with `categories: research` show up on
  the Research page, `categories: highlights` also show up on the homepage.
- `_bibliography/references.bib` — publications, in BibTeX, rendered on the Publications
  page grouped by year via [jekyll-scholar](https://github.com/inukshuk/jekyll-scholar).
- `img/` — currently placeholder SVG/PNG assets only; swap in real photos/logos.

## Deploy

Pushing to `main` builds and deploys via `.github/workflows/jekyll.yml` (GitHub Actions →
GitHub Pages). Make sure Pages is set to the "GitHub Actions" source in the repo settings.
