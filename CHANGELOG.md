# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### 🔁 Changes
 
- Changed the style of headers in PDF export mode
- All font sizes use `em` units. This allows users to configure the font size more easily.

### 🐛 Bugfixes

- Tasks are now correctly indented.
- Links in quote elements are hightlighted correctly in edit mode.

## [1.5.0] - 2021-01-24

### ✨ Features

- Added relationship lines to the tag pane when tags are nested.
- Updated design for search result & backlinks snippets.
- Updated design for window selector tabs.
- Added support for built-in frontmatter.
- Added relationship lines to nested bullet points in preview mode.

### 🔁 Changes

- Added some additional spacing between `li` elements in preview mode.
- Tweak `input` and `textarea` element styling.
- Updated calendar plugin styling.
- Increased the indentation of nested lists to make them more prominent.
- Softened the color of `hr` elements and the borders under `h1`, and `h2` elements.

### 🐛 Bugfixes

- Macro tokens are correctly highlighted in code blocks.

## [1.4.1] - 2021-01-08

Tested against Obsidian v0.10.7, other versions should work, but your results may vary!

### 🐛 Bugfixes

- Active files are correctly highlighted in the file hierarchy.
- Fixed search, query, and backlinks styling.
- Removed erroneous outline around code fence blocks in edit mode.

## [1.4.0] - 2020-12-31

Tested against Obsidian v0.10.4, other versions should work, but your results may vary!

### ✨ Features

- Added support for query blocks.

### 🔁 Changes

- Updated [Todoist plugin](https://github.com/jamiebrynes7/obsidian-todoist-plugin) styling to support v1.6.
- Updated color variables used by Obsidian & other plugins.

### 🐛 Bugfixes

- Removed erroneous margin around inline code elements.

## [1.3.0] - 2020-12-03

Tested against Obsidian v0.9.20, other versions should work, but your results may vary!

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
