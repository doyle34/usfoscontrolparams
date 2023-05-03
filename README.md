# usfoscontrolparams README

This program is a simple language extension to VSCode which enables syntax highlighting for Usfos Control Parameters. It works for .fem files, used for control files and structure files of Usfos.

It only highlights the very first strings of each line which is Usfos commands.

Lines starting with `!`, `*`, `'`, `%`, and `#` will be marked as comments.

## Known Issues

The `!` in-line comment is not recognized as a comment.

## Release Notes

### 0.0.1

Beta release

only available for syntax highlighting
