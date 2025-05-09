# Alfred Smart Punctuation

Convert "straight" punctuation marks into their “smart” variants with a hotkey or keyword using [SmartyPants](https://daringfireball.net/projects/smartypants/) and [html2text](https://gitlab.com/grobian/html2text).

## Installation

Assuming [Homebrew](https://brew.sh) is installed:

1. Install SmartyPants: `brew install smartypants`
2. Install html2text: `brew install html2text`
3. Download and install [the Alfred workflow](https://github.com/tylersticka/alfred-smart-punctuation/releases/latest/download/SmartPunctuation.alfredworkflow)

## Usage

The default hotkey to transform selected text in place is `Shift` + `⌘` + `'` (quotation mark), but you may override this in the workflow settings however you like.

Or use the `sp {text}` command to transform the provided text and copy to clipboard.
