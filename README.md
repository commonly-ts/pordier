# Pordier at War Wiki

This repository contains the source for the wiki (built with Jekyll + HTML/CSS) that documents classes, weapons, factions, etc.

## Tech stack
- Static site generator: [Jekyll](https://jekyllrb.com/) (Ruby)
- HTML + CSS for styling
- Directory structure:
  - `_classes/`, `_factions/`, `_weapons/`, `_peoples/` - wiki contents
  - `_includes/` & `_layouts/` - site templates
  - `images/` - assets
- License: MIT (see `LICENSE`)

## Contributing
1. Clone the repo
```
git clone https://github.com/commonly-ts/pordier.git
cd pordier
```
2. Install dependencies (requires Ruby + Bundler)
```
bundle install
```
3. Build & serve locally:
```
bundle exec jekyll serve
```
Then open `http://localhost:4000` in your browser.
4. Make your edits by adding or updating makrdown files in the content folders, update layout/templates if needed, and add images in their correlated folder in `images/`.
5. Preview changes locally before committing and opening a pull request.

## Structure
`_classes/` - pages for playable classes
`_weapons/` - pages for usable weapons
`_factions/` - pages for in-game teams
`_peoples/` - pages for in-game races
`index.md` - homepage content
`_config.yaml` - Jekyll config
`style.css` - styling

## Publishing
Once you're happy with your changes:
- Commit your changes with a clear message.
- Create a pull request
- The site is published via GitHub Pages

## Acknowledgements
Thank you to all contributors!
