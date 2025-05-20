# Alfred Smart Punctuation

Convert "straight" punctuation marks into their “smart” variants with a hotkey or keyword.

Uses [SmartyPants](https://daringfireball.net/projects/smartypants/) for the conversion, followed by [a Perl command to decode HTML entities](https://stackoverflow.com/a/13161719).

## Installation

Assuming [Homebrew](https://brew.sh) is installed:

1. Install SmartyPants: `brew install smartypants`
2. Download and install [the Alfred workflow](https://github.com/tylersticka/alfred-smart-punctuation/releases/latest/download/SmartPunctuation.alfredworkflow)

## Usage

The default hotkey to transform selected text in place is Shift-Command-Apostrophe (`⇧⌘'`), but you may override this in the workflow settings however you like.

Or use the `sp {text}` command to transform the provided text and copy to clipboard.

| Feature             | Input             | Output            |
| ------------------- | ----------------- | ----------------- |
| Quotes, Apostrophes | "How's it going?" | “How’s it going?” |
| Ellipses            | Hold on...        | Hold on…          |
| Em Dashes           | Wait--what?!      | Wait—what?!       |
