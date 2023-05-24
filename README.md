This page is built with [Jekyll](https://jekyllrb.com/).

## Development

Ruby 3+ is required, you can install it manually or via [asdf](https://asdf-vm.com)

```bash
asdf plugin add ruby
asdf install
```

Install dependencies

```bash
bundle install
```

Start local server

```bash
bundle exec jekyll serve --livereload --port 4000
```

Open [localhost:4000](http://localhost:4000) in your browser.

## Deployment

Site is automatically built and published to Github Pages when commit is pushed to `main` branch.
