This repository is a Hugo static website for `allenchen1113official.github.io`, built with the `hugo-coder` theme.

Primary focus:
- content authoring in `content/`
- site configuration in `config.toml`
- theme/layout customization in `layouts/`
- styling and assets in `assets/` and `static/`

Important conventions:
- `public/` is generated output and should not be edited directly.
- `resources/` is Hugo-generated build cache.
- `themes/hugo-coder/` is a Git submodule referenced by `config.toml`.
- `archetypes/default.md` defines default front matter for new posts.

Local commands:
- `git submodule update --init --recursive`
- `hugo server --buildDrafts --buildFuture`
- `hugo`

What to work on here:
- create or update markdown posts under `content/posts/`
- change menu/navigation, metadata, or author info in `config.toml`
- edit templates and partials in `layouts/`
- change SCSS in `assets/scss/` or JS in `assets/js/`
- fix broken image/resource paths in `static/`

Notes:
- There is a `workflows/hugo.yaml` file in the repository, but no standard `.github/workflows` directory yet.
- `config.toml.bak.toml` is a backup config file.
- These instructions apply to the Hugo website repository at `Allen_Code/allenchen1113official`.
