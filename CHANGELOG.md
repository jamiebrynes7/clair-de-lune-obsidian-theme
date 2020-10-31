# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### ✨ Features

- The new suggestions popup for completing note or block references is now styled in keeping with the theme.
- Tags in preview mode now have special styling, certain tag references will have emojis instead of hashtags. See [tags.scss](./src/modules/preview/tags.scss) for a list of these.

### 🔁 Changes

- Improved styling around folded lists.
- Updated the quick open styling to match the suggestions popup.
- Math blocks are now slightly larger.

### 🐛 Bugfixes

- Aligned wrapped text next to checkboxes properly.
- A folded list item containing inline code where the folded content contains a code block no longer has additional padding.

## [1.1.0] - 2020-10-25

### ✨ Features

- Added support for some Mermaid diagrams (flowchart, sequence, gantt, class).

### 🐛 Bugfixes

- Fixed an issue where checkboxes were occasionally not rendered correctly.
- Fixed an issue where `hr` elements were not styled correctly in preview mode.
- Fixed an issue where code & inline code-like elements had the wrong font & sizing in editor mode.
- Fixed an issue where LaTeX math elements where styled incorrectly in editor mode.
- Fixed an issue where the delete buttons were not styled correctly.

## [1.0.0] - 2020-10-19

Initial release of the Clair de Lune Obsidian theme.
