## Shell from Scratch

A shell in the style of the Bourne shell, Bash, zsh, etc.

It supports,

  1. running commands with arbitrarily many arguments
  2. quoting those arguments
  3. combining the commands into arbitrarily long pipelines where the output of one command becomes the input of the next.

This requires writing a parser, which we do with [Parslet][parslet], a PEG parser library.

https://www.destroyallsoftware.com/screencasts/catalog/shell-from-scratch

[parslet]: http://kschiess.github.io/parslet/
