# 4.1.2 - 2017-03-07

- Fixed: TypeError: Cannot read property 'breaks' of undefined
  ([#30](https://github.com/medfreeman/markdown-it-toc-and-anchor/issues/30))

# 4.1.1 - 2016-05-05

- Fixed: inexistent environment in markdown-it parsing on second instance

# 4.1.0 - 2016-04-24

- Added: ``tocCallback`` option to allow getting toc elements in addition to / instead of @[toc] transformation

# 4.0.0 - 2016-04-23

- Changed: refactored toc generation to allow full markdown processing
- Removed: ``indentation`` option (the output is now generated by markdown-it and has no indentation)
- Added:   dependency to [clone](https://www.npmjs.com/package/clone)
- Fixed:   link inside heading not rendered correctly
  ([#7](https://github.com/medfreeman/markdown-it-toc-and-anchor/issues/7))

# 3.1.0 - 2016-04-19

- Added: ``tocLastLevel`` option to skip some upper heading levels
  ([#1](https://github.com/medfreeman/markdown-it-toc-and-anchor/issues/1))

# 3.0.2 - 2016-04-19

- Fixed: eslint command now using gitignore (fix for Windows), automatic syntax fix
- Fixed: ava configuration (fix for Windows)
  ([#14](https://github.com/medfreeman/markdown-it-toc-and-anchor/issues/14))

# 3.0.1 - 2016-04-10

- Fixed: Reset anchor ids
  ([#13]((https://github.com/medfreeman/markdown-it-toc-and-anchor/issues/13))

# 3.0.0 - 2016-04-04

**No API changes**.

- Changed: this plugin does not require ``markdown-it`` anymore
  ([#2](https://github.com/medfreeman/markdown-it-toc-and-anchor/issues/2))

# 2.1.0 - 2016-01-17

- Fixed: Should support unicode heading
  ([#5](https://github.com/medfreeman/markdown-it-toc-and-anchor/issues/5)
  via [#6](https://github.com/medfreeman/markdown-it-toc-and-anchor/pull/6))
- Added: ``anchorLinkSpace`` option to enable/disable inserting a space between
  the anchor link and heading
  ([#6](https://github.com/medfreeman/markdown-it-toc-and-anchor/pull/6)).
- Added: ``anchorLinkSymbolClassName`` customize the anchor link symbol class
  name
  ([#6](https://github.com/medfreeman/markdown-it-toc-and-anchor/pull/6)).

# 2.0.0 - 2015-11-01

- Changed: `markdown-it@^5.0.0`.

# 1.0.1 - 2015-06-03

- Fixed: publish dist/ files.

# 1.0.0 - 2015-06-03

✨ Initial release
