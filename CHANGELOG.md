# Change Log
All notable changes to the "vento" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how
to structure this file.

## [0.2.4] - 2026-01-27
### Fixed
- HTML injections and embeddings [#8] [#21]
- Preserve HTML, CSS and JS intellisense in Vento language [#7] [#22]

## [0.2.3] - 2026-01-24
### Fixed
- The `/` in closing tags has the scope of keyword.operator.arithmetic.js [#18] [#20]

## [0.2.2] - 2026-01-04
No visible changes.

## [0.2.1] - 2026-01-04
### Added
- Support for `default` tag.

## [0.2.0] - 2025-09-01
### Added
- Support for `break`, `continue` and `slot` tags.

### Fixed
- GitHub Linguist (support HTML code)

## [0.1.2] - 2025-04-20
### Fixed
- `export function` snippet [#17].

## [0.1.1] - 2025-02-14
### Fixed
- Remove Vento comments in HTML and Markdown files.
- Fix `<script>` highlight breaking in HTML files [#16].

## [0.1.0] - 2025-01-12
### Changed
- Enable Vento snippets and syntax for HTML and Markdown [#14]

## [0.0.9] - 2024-11-18
### Fixed
- Highlight `from` keyword in `import` statements [#11], [#12]
- Optimized `screenshot.jpg` file.

## [0.0.8] - 2024-08-15
### Fixed
- Syntax highlight inside quoted HTML code [#8].

## [0.0.7] - 2024-03-19
### Fixed
- Added `async` and `await` keywords [#4].
- Improved JavaScript tags (`{{> ... }}`)

## [0.0.6] - 2024-03-19
### Fixed
- Missing template keywords [#3].

## [0.0.5] - 2023-09-16
### Added
- Support for front matter [#2].
- Support for new keywords `layout`, `echo`.
- Snippets for the new features (`layout`, `echo`, `function`, `import`,
  `export`).

## [0.0.4] - 2023-07-16
### Added
- Emmet support [#1]

## [0.0.3] - 2023-07-03
### Fixed
- HTML syntax highlight.

## [0.0.2] - 2023-06-14
### Added
- Icon to `package.json`.
- Screenshot to `README.md`.

### Fixed
- `for key,value` snippet.

## [0.0.1] - 2023-06-13
Initial release

[#1]: https://github.com/oscarotero/vscode-vento/issues/1
[#2]: https://github.com/oscarotero/vscode-vento/issues/2
[#3]: https://github.com/oscarotero/vscode-vento/issues/3
[#4]: https://github.com/oscarotero/vscode-vento/issues/4
[#7]: https://github.com/oscarotero/vscode-vento/issues/7
[#8]: https://github.com/oscarotero/vscode-vento/issues/8
[#11]: https://github.com/oscarotero/vscode-vento/issues/11
[#12]: https://github.com/oscarotero/vscode-vento/issues/12
[#14]: https://github.com/oscarotero/vscode-vento/issues/14
[#16]: https://github.com/oscarotero/vscode-vento/issues/16
[#17]: https://github.com/oscarotero/vscode-vento/issues/17
[#18]: https://github.com/oscarotero/vscode-vento/issues/18
[#20]: https://github.com/oscarotero/vscode-vento/issues/20
[#21]: https://github.com/oscarotero/vscode-vento/issues/21
[#22]: https://github.com/oscarotero/vscode-vento/issues/22

[0.2.4]: https://github.com/oscarotero/vscode-vento/compare/v0.2.3...v0.2.4
[0.2.3]: https://github.com/oscarotero/vscode-vento/compare/v0.2.2...v0.2.3
[0.2.2]: https://github.com/oscarotero/vscode-vento/compare/v0.2.1...v0.2.2
[0.2.1]: https://github.com/oscarotero/vscode-vento/compare/v0.2.0...v0.2.1
[0.2.0]: https://github.com/oscarotero/vscode-vento/compare/v0.1.2...v0.2.0
[0.1.2]: https://github.com/oscarotero/vscode-vento/compare/v0.1.1...v0.1.2
[0.1.1]: https://github.com/oscarotero/vscode-vento/compare/v0.1.0...v0.1.1
[0.1.0]: https://github.com/oscarotero/vscode-vento/compare/v0.0.9...v0.1.0
[0.0.9]: https://github.com/oscarotero/vscode-vento/compare/v0.0.8...v0.0.9
[0.0.8]: https://github.com/oscarotero/vscode-vento/compare/v0.0.7...v0.0.8
[0.0.7]: https://github.com/oscarotero/vscode-vento/compare/v0.0.6...v0.0.7
[0.0.6]: https://github.com/oscarotero/vscode-vento/compare/v0.0.5...v0.0.6
[0.0.5]: https://github.com/oscarotero/vscode-vento/compare/v0.0.4...v0.0.5
[0.0.4]: https://github.com/oscarotero/vscode-vento/compare/v0.0.3...v0.0.4
[0.0.3]: https://github.com/oscarotero/vscode-vento/compare/v0.0.2...v0.0.3
[0.0.2]: https://github.com/oscarotero/vscode-vento/compare/v0.0.1...v0.0.2
[0.0.1]: https://github.com/oscarotero/vscode-vento/releases/tag/v0.0.1
