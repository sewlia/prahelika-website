# Prahelika Deka

A lightweight Jekyll academic profile, populated from Prahelika’s supplied resume. Includes research, experience, selected writing, education, recognition, community work, and contact details.

## Run locally

Use Ruby 3.3 or newer:

```sh
bundle install
bundle exec jekyll serve
```

Open http://127.0.0.1:4000. To build only, run `bundle exec jekyll build`.

## Editing

- `index.html`: profile and resume content.
- `_config.yml`: name, description, email, LinkedIn, URL, and base path.
- `assets/style.css`: responsive design and print styles.
- `assets/img/prahelika.jpg`: optimized supplied portrait.
- `_layouts/default.html`: shared navigation and metadata.

Publication titles and dates follow the supplied resume. No publication URLs were supplied, so none are invented. Review ongoing roles and work in revision as they change.

## GitHub Pages

In the repository’s **Settings → Pages**, choose **GitHub Actions** as the source. The included workflow builds pull requests and deploys pushes to `main`. Set `url` in `_config.yml` to the final origin (for example, `https://your-account.github.io`). The workflow supplies the project base path automatically; for local project-path testing use `bundle exec jekyll build --baseurl /prahelika-website`.

## Lightweight by design

No client-side JavaScript, external fonts, trackers, comments, search index, or UI frameworks. One stylesheet and an optimized JPEG. The original resume is not published as a download. A print stylesheet supports printing or saving the page as PDF.

Originally forked from Chirpy. The original MIT license is retained in `LICENSE`; unused theme assets, demo posts, and theme release tooling have been removed.
