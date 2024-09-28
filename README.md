![grep-command](https://github.com/user-attachments/assets/3f4ccabc-1979-4c1e-b2ef-819a65f1c63b)

## Python Grep Tool

This repository contains a basic implementation of the classic grep command-line tool, written in Python. The tool allows for pattern matching in input strings using simplified regular expressions. It supports various common features found in grep, such as anchors, character classes, and backreferences.

## Features

* Anchor Matching: Supports ^ (start of line) and $ (end of line) anchors.
* Character Classes: Handles patterns like \w (word characters), \d (digits), and custom character sets using square brackets [].
* Wildcards: Matches any single character using the dot ..
* Backreferences: Supports backreferences such as \1, \2, allowing repeated groups to be matched later in the pattern.
* Grouping: Supports capturing groups with parentheses () to enable backreference functionality.

