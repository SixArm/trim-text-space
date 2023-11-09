# trim-text-space

Trim text space is a simple script to delete extraneous spaces:

  * Delete empty leading lines

  * Delete empty trailing lines

  * Delete spaces at the end of any line

Syntax:

```sh
stdin | trim-text-space
```

Example:
```
cat file.txt | trim-text-space
```

## Purpose

This kind of trim is helpful for many kinds of text files, such as source code
text files in many popular programming languages, documentation content text
files in many popular markup languages, and more.

## Notes

Markdown caution: If your text uses markdown syntax, be aware that some markdown
variations use a double-space at the end of a line to indicate a line break.
If you need the double-space at the end of a line, then don't use this tool

## Thanks

Thanks to dicussion [here](https://stackoverflow.com/questions/7359527/removing-trailing-starting-newlines-with-sed-awk-tr-and-friends)

Thanks for the awk answer [Glenn Jackman](https://stackoverflow.com/users/7552/glenn-jackman)

## Tracking

* Command: trim-text-spaces
* Version: 1.0.0
* Created: 2023-11-09T20:57:02Z
* Updated: 2023-11-09T22:01:25Z
* License: GPL-2.0 or GPL-3.0 or contact for custom
* Contact: Joel Parker Henderson (joel@joelparkerhenderson.com)
 