# CSC649 Setup – Word and Character Counter

## What the program does
Asks the user for a sentence, then shows the word count and the character count
(including spaces). If nothing is entered, it shows a message instead.

## How to run
1. Open the project in PyCharm (interpreter: .venv, Python 3.12).
2. Open main.py and click Run, or in the terminal: python main.py
3. Type a sentence when prompted.

## Test results
| Test | Input | Output |
|---|---|---|
| Normal sentence | I love learning Python | Word count: 4, Character count: 22 |
| Empty input | (empty) | You did not enter a sentence. |
| Extra spaces | "  Hello   world  " | Word count: 2, Character count: 17 |

## Limitation
The character count includes leading, trailing and repeated spaces, so it can
look larger than the visible text. Also, words are separated only by whitespace,
so "well-known" counts as one word.