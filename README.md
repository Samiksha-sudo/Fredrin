# Fredrin

A one-page "About Me" site for Samiksha Kad. It is a single static `index.html` file with inline CSS and no build step or dependencies. It switches to a dark theme automatically when the visitor's system prefers dark mode.

## Install

Nothing to install. Clone the repository:

```sh
git clone https://github.com/Samiksha-sudo/Fredrin.git
cd Fredrin
```

## Run locally

Open `index.html` directly in a browser, or serve the folder with any static file server, for example:

```sh
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## Customize

Edit `index.html` and replace the content marked with `<!-- TODO -->` comments:

- **Tagline**: the one-line tagline under your name
- **About Me**: your short bio
- **Skills & Interests**: the list of tags
- **Find Me**: your email, LinkedIn and any other links

The avatar is loaded from your GitHub profile picture, and the footer year updates automatically.
