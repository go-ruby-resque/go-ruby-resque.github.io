<p align="center"><img src="https://raw.githubusercontent.com/go-ruby-resque/brand/main/social/go-ruby-resque.png" alt="go-ruby-resque/go-ruby-resque.github.io" width="720"></p>

# go-ruby-resque.github.io

The organization's institutional landing page, served at
<https://go-ruby-resque.github.io> and built with [Hugo](https://gohugo.io). It is a
single page (custom `layouts/index.html`).

Documentation lives in a separate repository,
[go-ruby-resque/docs](https://github.com/go-ruby-resque/docs), served at
<https://go-ruby-resque.github.io/docs/>. This page links there.

`.github/workflows/deploy-pages.yml` builds the landing with Hugo and deploys it
to GitHub Pages on every push to `main`.

## Local preview

```bash
hugo server      # http://localhost:1313
```
