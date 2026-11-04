# janglos.eu

Personal website of Jan Glos, published at <https://www.janglos.eu> via GitHub Pages.

Built with Jekyll and the [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes) theme,
loaded as a `remote_theme` (version pinned in `_config.yml`).

- Content: `_pages/`, navigation in `_data/navigation.yml`
- Custom styles: `assets/css/main.scss` (after the theme imports)
- Theme overrides in `_includes/`: favicons and Twitter card (`head/custom.html`),
  GoatCounter analytics (`analytics-providers/custom.html`), extended Person
  structured data (`schema.html`). English UI strings live in `_data/ui-text.yml`
  (theme `_data` is not loaded from a remote theme; `follow_label` is customised).
  When bumping the theme version, compare these against the new upstream copies.

Local preview: `bundle install && bundle exec jekyll serve`
