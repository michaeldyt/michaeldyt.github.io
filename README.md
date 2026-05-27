# Yuntian Deng's Personal Homepage

This repository hosts my personal academic homepage at <https://michaeldyt.github.io/>.

The site is built with Jekyll and based on the Academic Pages theme. It contains my academic profile, selected experiences, projects, publications, and contact information.

## Contents

- `/_pages/about.md`: homepage content
- `/_pages/publications.html`: publications listing page
- `/_publications/`: individual publication entries
- `/_config.yml`: site-wide metadata, author profile, collections, and theme settings
- `/_sass/theme/`: light and dark theme color variables
- `/images/`: avatar, favicon, and other image assets

## Common Updates

Edit the homepage:

```bash
_pages/about.md
```

Add or update publications:

```bash
_publications/*.md
```

Update profile metadata, email, social links, or repository settings:

```bash
_config.yml
```

The default branch for this repository is `main`.

## Local Preview

If Ruby and Bundler are installed:

```bash
bundle install
bundle exec jekyll serve -l -H localhost
```

Then open <http://localhost:4000>.

Alternatively, use Docker:

```bash
docker compose up
```

Then open <http://localhost:4000>.

## Credits

This site is based on the Academic Pages template, which is derived from the Minimal Mistakes Jekyll theme.
