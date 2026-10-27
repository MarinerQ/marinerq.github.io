# Qian Hu's personal website

Source for <https://marinerq.github.io>, hosted on GitHub Pages.
Based on [AcademicPages](https://github.com/academicpages/academicpages.github.io)
and [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes).
The inherited MIT license and source attributions are retained in `LICENSE`
and the theme files.

## Content and configuration

- `_pages/about.md`: homepage and research interests.
- `_pages/publications.md`, `_pages/talks.md`, `_pages/teaching.md`, `_pages/cv.md`: main pages.
- `_publications/` and `_teaching/`: older individual pages; keep their public URLs working.
- `_config.yml`: site identity, author profile, analytics and build settings.
- `_data/navigation.yml`: main navigation.
- `files/`: downloadable CV; `images/`: personal photo and Q logo.

## Local preview

Use Ruby 3.3 and a compatible Bundler. The macOS system Ruby 2.6 is too old
for the full GitHub Pages dependency bundle.

```sh
bundle install
bundle exec jekyll serve --config _config.yml,_config.dev.yml
```

Open <http://127.0.0.1:4000>. The development override disables analytics.
Restart the server after editing configuration. To check a production build:

```sh
JEKYLL_ENV=production bundle exec jekyll build --safe
```

The `github-pages` gem keeps Jekyll aligned with the supported
[GitHub Pages versions](https://pages.github.com/versions/).
Run `bundle update github-pages` to refresh compatible dependencies, then
build and preview before committing the resulting `Gemfile.lock`.
Do not delete the lockfile to resolve security notices; update the affected
dependency and verify the build.

## Appearance

Personal styling lives in `_sass/_custom.scss`, imported last by
`assets/css/main.scss`. Keep new visual changes there so the inherited theme
remains easy to identify. Navigation links stay visible at every screen size
and wrap onto a second row on small screens, with no JavaScript or build step
needed for navigation. MathJax is pinned to 4.1.3
and loaded only on pages with math delimiters (or `math: true` in front matter).

The template's sample posts, talks, portfolio, maps, placeholder images,
comment data and unused generators have been removed. Personal pages, the
Q logo, CV PDF and individual research/teaching records are retained. The
current profile photo is `images/photo_QH.jpg`.
