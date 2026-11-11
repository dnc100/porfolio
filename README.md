# dnc100 — Developer Portfolio

A GitHub Pages portfolio built with [TeXt](https://github.com/kitian616/jekyll-TeXt-theme), a Jekyll theme.

**Site:** https://dnc100.github.io/porfolio/

## Projects

Edit [`_data/projects.yml`](_data/projects.yml) to add, remove, or update the project cards on the home page.

## Publish with GitHub Pages

1. Fork [TeXt](https://github.com/kitian616/jekyll-TeXt-theme) into the `dnc100` account and name the fork `porfolio`.
2. Push this customized `master` branch to `dnc100/porfolio`.
3. In the repository, open **Settings → Pages** and set the build and deployment source to **GitHub Actions**.
4. The workflow deploys on every push to `master`. The site URL is `https://dnc100.github.io/porfolio/`.

The site URL and project base path are set in [`_config.yml`](_config.yml). If the repository is renamed, update `baseurl` there and the URL in this README.

## Local preview

With Ruby and Bundler installed:

```sh
bundle install
bundle exec jekyll serve --baseurl /porfolio
```

Then open `http://localhost:4000/porfolio/`.

## Theme and license

The original TeXt theme is maintained by [kitian616](https://github.com/kitian616/jekyll-TeXt-theme) and is MIT licensed. Its original `LICENSE` file is retained in this repository.
