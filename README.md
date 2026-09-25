# Felipe Cordera’s academic website

Jekyll / AcademicPages site hosted at https://felipecordera.github.io.

## Content

- `_pages/about.md`: homepage and research overview.
- `_pages/research.md`: working papers, publications, ongoing research, and selected talks.
- `_pages/teaching.html`: teaching approach and experience.
- `_pages/cv.md`: CV overview.
- `files/Felipe_Cordera_CV.pdf`: downloadable CV; replace this file to preserve the public URL.
- `_config.yml`: profile, metadata, and build exclusions.
- `_data/navigation.yml`: navigation.
- `_sass/_academic.scss`: visual refinements.

Content was drafted from the CV, research statement, and teaching statement in the sibling `Materials` directory in September 2026. Publication statuses reflect those materials. Research and teaching statements are summarized, not distributed as PDFs. Add verified paper URLs when available. The original template examples remain in source but are excluded from the build.

## Local preview

```sh
bundle install --path vendor/bundle
bundle exec jekyll serve --config _config.yml,_config.dev.yml
```

Open http://localhost:4000. For a production build, run `bundle exec jekyll build`.

Before publishing, review publication statuses and any desired job-market announcement. Commit and push through the repository’s configured GitHub Pages workflow after reviewing the preview.
