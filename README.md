[![progress-banner](https://backend.codecrafters.io/progress/grep/19cfe16b-b5fa-4d9b-96bc-f188ecb7e639)](https://app.codecrafters.io/users/codecrafters-bot?r=2qF)

##Python Grep Tool

This repository contains a basic implementation of the classic grep command-line tool, written in Python. The tool allows for pattern matching in input strings using simplified regular expressions. It supports various common features found in grep, such as anchors, character classes, and backreferences.

##Features

* Anchor Matching: Supports ^ (start of line) and $ (end of line) anchors.
* Character Classes: Handles patterns like \w (word characters), \d (digits), and custom character sets using square brackets [].
* Wildcards: Matches any single character using the dot ..
* Backreferences: Supports backreferences such as \1, \2, allowing repeated groups to be matched later in the pattern.
* Grouping: Supports capturing groups with parentheses () to enable backreference functionality.

