# Changelog

## 1.2.0

- Comments now use `$$` for a line comment and `$* ... *$` for a block
  comment, which may span lines. `#` is no longer a comment, so values
  like `#8496AD` need no quotes.
- Block comments that span lines fold on their own.
- Live error checking now uses the `jpcl-lang` package from npm.

## 1.1.1

First release, versioned to match the `jpcl` (PyPI) and `jpcl` (npm)
packages it is built alongside.


- Syntax highlighting for `.jp` files.
- Live error checking with the `jpcl` parser.
- Outline, breadcrumbs, Go to Symbol and folding.
- Format Document, which leaves files with comments untouched unless
  `jpcl.format.allowDroppingComments` is on.
- Preview as JSON command.
