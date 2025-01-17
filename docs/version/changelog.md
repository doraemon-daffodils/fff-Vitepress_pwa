---
title: 'Changelog'
outline: deep
---

# Changelog

::: info
For non-version-related changes, please refer to the [git commit history](https://github.com/importantimport/fff/commits/main).
:::

## [Version 0.2](/version/0.2.html) (2022-07-21)

- Remove: `alt`
- Add: [`authors`](/version/0.2.html#authors) [`lang`](/version/0.2.html#lang) [`location`](/version/0.2.html#location)
- Rename: [`photo => image`](/version/0.2.html#image)
- Improve:
  - optional advanced type for [`image`](/version/0.2.html#image) [`audio`](/version/0.2.html#audio) [`video`](/version/0.2.html#video)
  - optional type for [`created`](/version/0.2.html#created) [`updated`](/version/0.2.html#updated) [`published`](/version/0.2.html#published)
- Chore:
  - make [`audio`](/version/0.2.html#audio) [`video`](/version/0.2.html#video) as base variables
  - more accurate descriptions

### Version 0.2.2 (2022-08-17)

- Improve:
  - make [`author.name`](/version/0.2.html#additional) optional
- Chore:
  - fix yaml install command in package README.md
  - update package description

### Version 0.2.1 (2022-07-23)

- Chore:
  - add README.md for package
  - add `// deno-fmt-ignore-file` in fff.ts
  - update keywords & homepage in package.json
  - Published as a deno module to [deno.land/x](https://deno.land/x/fff)

## [Version 0.1](/version/0.1.html) (2022-07-18)

- Initial version
