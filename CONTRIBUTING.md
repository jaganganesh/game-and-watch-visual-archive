# Contributing to Game & Watch Visual Archive

Thank you for your interest in improving the archive.

This repository is open to contributions that make the collection more accurate, more complete, easier to browse, and more useful to collectors, researchers, and retro gaming fans.

# Important Branch Rule

All pull requests should target:

- `develop`

Do not open pull requests directly against:

- `main`

The `main` branch is treated as the release branch. Documentation updates, image additions, fixes, and archive improvements should go through `develop` first.

# Good Areas to Contribute

You can help by improving:

- Missing Game & Watch titles
- Regional variants or alternate releases
- Image quality and consistency
- Title naming and labeling
- README clarity, navigation, and discoverability
- Release year, model number, and hardware series notes
- Source attribution or provenance details

# Local Setup

This repository does not require a build step.

Recommended setup:

1. Fork the repository
2. Clone your fork
3. Check out `develop`
4. Create a focused branch for your change

```bash
git clone https://github.com/your-username/game-and-watch-visual-archive.git
cd game-and-watch-visual-archive
git checkout develop
git checkout -b docs/improve-archive-entry
```

# Image Contribution Guidelines

If you add or replace images:

- Place files in `images/`
- Prefer clear, high-quality `.jpg` images that match the archive's existing format
- Follow the current naming style when possible, such as `Game-Watch-Title.jpg`
- Update the README gallery or related documentation if your change affects visible archive coverage
- Mention image provenance, ownership, or source context in the pull request

Only submit images that you created yourself, have permission to redistribute, or otherwise have a clear right to share in the repository.

# Documentation Contribution Guidelines

Documentation improvements are welcome too.

Helpful examples:

- Clarifying what the archive currently covers
- Improving Game & Watch history context
- Fixing title names or inconsistent formatting
- Expanding keywords that help GitHub discovery
- Adding structure that makes the collection easier to browse

# Pull Request Guidelines

Please keep pull requests:

- Small enough to review comfortably
- Focused on one main change
- Clearly described
- Targeted to `develop`

Useful things to include in your pull request description:

- What changed
- Why it changed
- Which titles or files were added or updated
- Any source or provenance notes for images
- How you manually verified the result

# Suggested Checks Before Opening a PR

There is no automated test suite in this repository, so manual verification matters most.

Before opening a pull request:

- Confirm that new or updated images open correctly
- Confirm that file names are consistent with the archive style
- Confirm that README image links and section links still render correctly
- Confirm that the gallery labels match the files you changed

# Commit Style

A simple commit style is helpful. Examples:

- `docs: improve README discoverability`
- `assets: add missing game and watch title`
- `fix: correct title naming in gallery`

You do not need to follow these examples perfectly, but clear commit messages make the history easier to understand.

# Questions

If you are unsure whether a change fits the project, open an issue or draft pull request first.

Thank you for helping improve Game & Watch Visual Archive.
