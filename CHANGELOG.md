## 2.0.0

1. **BREAKING**: Add stricter rules to element parsers
   [Issue#29](https://github.com/chenzhiguang/dart_markdown/issues/29).

   _New rules:_

   - `BlockParser` can only return `BlockElement`.
   - `InlineParser` can only return `InlineObject`, which could be
     `InlineElement`, `Text` or `UnparsedContent`.
   - `InlineElement` can only have `InlineObject` as `children` elements.

2. Fix an issue when paragraph is disabled
   [Issue#27](https://github.com/chenzhiguang/dart_markdown/issues/27).

## 1.0.5

1. Add `kbd` support
   [PR#25](https://github.com/chenzhiguang/dart_markdown/pull/25).
2. **BREAKING**: Rename `enableSupscript` to `enableSuperscript`
   [PR#24](https://github.com/chenzhiguang/dart_markdown/pull/24).

## 1.0.4

1. Change element type `supscript` to `superscript`
   [PR#21](https://github.com/chenzhiguang/dart_markdown/pull/21).

## 1.0.3

1. Add sup script and sub script support
   [Issue#3](https://github.com/chenzhiguang/dart_markdown/issues/3).
2. Fix the conflict between footnote and image
   [PR#17](https://github.com/chenzhiguang/dart_markdown/pull/17).

## 1.0.2

1. Do not produce paragraph element in footnote reference when the paragraph is
   disabled
   [Issue#12](https://github.com/chenzhiguang/dart_markdown/issues/12).
2. Fix a task list item issue
   [Issue#13](https://github.com/chenzhiguang/dart_markdown/issues/13).

## 1.0.1

1. Add class name to task list item
   [Issue#6](https://github.com/chenzhiguang/dart_markdown/issues/6).
2. Improve footnote reference
   [Issue#9](https://github.com/chenzhiguang/dart_markdown/issues/9).

## 1.0.0

First version, refactored from
[dart-lang/markdown(5.0)](https://pub.dev/packages/markdown/versions/5.0.0)
