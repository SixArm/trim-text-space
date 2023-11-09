# trim-text-spaces

Trim text spaces that are typically extraneous:

  * Leading lines that are empty

  * Trailing lines that are empty

  * Trailing spaces on any line

## Purpose

This kind of trim is helpful for many kinds of text files, such as source code
text files in many popular programming languages, documentation content text
files in many popular markup languages, and more.

## Notes

Markdown caution: If your text uses markdown syntax, be aware that some markdown
variations use a double-space at the end of a line to indicate a line break.
If you need the double-space at the end of a line, then don't use this tool

## Thanks

Thanks to dicussion:
<https://stackoverflow.com/questions/7359527/removing-trailing-starting-newlines-with-sed-awk-tr-and-friends>

Thanks to Glenn Jackman for the awk answer:
<https://stackoverflow.com/users/7552/glenn-jackman>

## Tracking

* Command: trim-text-spaces
* Version: 1.0.0
* Created: 2023-11-09T20:57:02Z
* Updated: 2023-11-09T21:08:23Z
* License: GPL-2.0 or GPL-3.0 or contact for custom
* Contact: Joel Parker Henderson (joel@joelparkerhenderson.com)
 