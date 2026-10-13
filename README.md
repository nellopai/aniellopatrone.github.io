Professional website and blog of Aniello R Patrone.

All material, including texts, images, and layouts, are subject to copyright.

## Setup and development on MacOS

1. Install [prerequisites](https://jekyllrb.com/docs/installation/macos/) using Homebrew
2. Install jekyll and bundler gems
3. Install the gems listed in the `Gemfile` (this includes the Jekyll plugins used in `_config.yml`) via
```bash
bundle install
```
4. Check out the git repository
5. Run
```bash
bundle exec jekyll serve --force_polling
```
6. Browse to [http://localhost:4000](http://localhost:4000)

## To-do

* (done) Logo backing for dark mode — see `custom.sass`.

## Acknowledgements

This page is based on the [Contrast](https://github.com/niklasbuschmann/contrast) Jekyll theme by Niklas Buschmann, which is [public domain](http://unlicense.org/).
Many thanks, Niklas, for this headstart.

## Languages

The site is bilingual. English pages live at the root, German pages under `de/`.
Pages that translate each other share the same `ref` in their front matter
(`home`, `cv`, `publications`); the layout uses it to add `hreflang` tags, the
language switch in the menu and the "also available in …" banner. Menu labels
are in `navigation` / `navigation_de` in `_config.yml`, other interface texts in
`_data/i18n.yml`. When you change a page, update its translation too.
