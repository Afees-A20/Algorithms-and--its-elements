# Sentence Analysis Checkpoint

## Overview
This algorithm reads a sentence character by character until a period (.) is encountered. It calculates:

- Total number of characters (length, including the period)
- Number of words (assuming single spaces between words)
- Number of vowels (a, e, i, o, u)

## Counters
The algorithm uses *three counters*:

1. length → counts all characters
2. words → counts words
3. vowels → counts vowels

## Logic
- Read each character individually
- Increment length for every character
- Increment words when a space is found
- Increment oowels when a vowel is found
- Stop reading when . is encountered
- Output all three counters

## Notes
- Strictly follows checkpoint instructions
- Uses exactly three variables as counters
- Character-by-character processing
