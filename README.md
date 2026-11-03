# WaGen Malatang

Company website for WaGen Malatang, built with Jekyll and deployed via
GitHub Pages.

## Pages

- Home (`/`)
- Menu (`/menu/`)
- Our Stores (`/our-stores/`)
- Join Us (`/join-us/`)
- Franchise (`/franchise/`)

## Local Development

Use Ruby 3.3. The GitHub Pages dependencies are not compatible with Ruby 4.
On macOS with Homebrew:

```sh
brew install ruby@3.3
export PATH="/opt/homebrew/opt/ruby@3.3/bin:$PATH"
```

```sh
bundle install
bundle exec jekyll serve
```

Then visit `http://localhost:4000`.

## Deployment

This site uses GitHub Pages' built-in Jekyll build. Push to the repository's
default branch and enable GitHub Pages in the repo settings (Settings →
Pages → Source: Deploy from a branch).
