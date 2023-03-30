# Tutorial: Understanding the regex for matching phone numbers

Regular expressions are a valuable tool for validating and extracting phone numbers from text. In this tutorial, we will discuss a regex pattern that can match international phone numbers.

## Summary

The regex pattern we will be discussing is `^\+?[1-9]\d{1,14}$`. This pattern matches phone numbers that start with an optional plus sign, followed by a digit between 1 and 9, and up to 14 additional digits.

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [OR Operator](#or-operator)
- [Character Classes](#character-classes)
- [Flags](#flags)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)
- [Boundaries](#boundaries)
- [Back-references](#back-references)
- [Look-ahead and Look-behind](#look-ahead-and-look-behind)

## Regex Components

### Anchors

The `^` and `$` symbols are anchors that match the beginning and end of the string, respectively. In this pattern, they ensure that the entire string matches the phone number format.

### Quantifiers

The `{1,14}` symbol is a quantifier that specifies how many times the preceding character or group should appear. In this pattern, it means that the digit character set should appear between 1 and 14 times.

### OR Operator

The `|` symbol is an OR operator that matches either the expression before or after it. This pattern does not use the OR operator.

### Character Classes

Character classes are sets of characters that match any one character in the set. In this pattern, the following character classes are used:

- `+?`: matches an optional plus sign at the beginning of the phone number.
- `[1-9]`: matches a digit between 1 and 9, ensuring that the phone number does not start with a leading zero.

### Flags

Flags modify the behavior of the regex pattern. This pattern does not use any flags.

### Grouping and Capturing

Grouping and capturing are used to extract specific parts of a match. This pattern does not use grouping or capturing.

### Bracket Expressions

Bracket expressions define a range of characters to match. This pattern does not use bracket expressions.

### Greedy and Lazy Match

Greedy and lazy matching determine how much text a pattern should match. This pattern uses greedy matching by default.

### Boundaries

Boundaries match the start or end of a word. This pattern does not use any boundaries.

### Back-references

Back-references allow you to match a previously captured group. This pattern does not use back-references.

### Look-ahead and Look-behind

Look-ahead and look-behind are used to match text based on what comes before or after it. This pattern does not use look-ahead or look-behind.

## Author

[Kyle Roff](https://github.com/kyleroff112)
