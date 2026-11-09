# Academic Homepage

Personal academic website of Patrick Morales, built with Jekyll
(academicpages-style layout).

- `_publications/` - one Markdown file per publication, with YAML front matter.
- `_includes/archive-single.html` - listing template. It renders a "Code"
  button only when a publication's front matter defines `codeurl`.
- `_config.yml`, `index.md` - site configuration and landing page.

Build locally with `bundle exec jekyll serve`.
