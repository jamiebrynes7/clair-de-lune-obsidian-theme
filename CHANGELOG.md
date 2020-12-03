# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.3.0] - 2020-12-03

Tested against Obsidian v0.9.20, other versions should work, but you results may vary!

### ✨ Features

- Font sizes set by this theme are now controllable by CSS variables. See [index.scss](./src/index.scss) for details.
- Restyled code blocks and added support for [Editor Syntax Highlight Obsidian Plugin](https://github.com/deathau/cm-editor-syntax-highlight-obsidian).
- Drag-n-drop operations in the file browser are styled in keeping with the theme.
- Added support for `textarea` elements.

### 🔁 Changes

- Tweaked how embedded blocks are rendered.
- Tweaked how code blocks are rendered in preview mode.
- Unified how buttons are rendered in Obsidian.
- Updated [calendar](https://github.com/liamcain/obsidian-calendar-plugin) styling to support v1.3/v1.4

### 🐛 Bugfixes

- Fixed some issues introduced by Obsidian v0.9.15
- Fixed a bug where block embeds in hover popups were incorrectly sized.
- Fixed an issues where **bold** or _italics_ in headings could cause strange formatting.

## [1.2.1] - 2020-11-05

### 🐛 Bugfixes

- Page references within headers are now rendered with the correct whitespace.

## [1.2.0] - 2020-11-05

This version was tested against Obsidian 0.9.10.

### ✨ Features

- The new suggestions popup for completing note or block references is now styled in keeping with the theme.
- Tags in preview mode now have special styling, certain tag references will have emojis instead of hashtags. See [tags.scss](./src/modules/preview/tags.scss) for a list of these.
- Added support for state diagrams in Mermaid.
- Added support for the new [sliding panes](https://github.com/deathau/sliding-panes-obsidian) plugin. This replaces the `obsidian-andy.css` variant.
- Added support for the [calendar](https://github.com/liamcain/obsidian-calendar-plugin) plugin.

### 🔁 Changes

- Improved styling around folded lists.
- Updated the quick open styling to match the suggestions popup.
- Math blocks are now slightly larger.
- Hover popups are now larger.
- Collapse arrows in preview mode are now styled.
- Bulleted lists are now styled.

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
