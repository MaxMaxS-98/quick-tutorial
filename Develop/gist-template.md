# Regex Tutorial

Regular Expressions are a powerful tool for searching and manipulating text. A regular expression is a sequence of characters that define a search pattern. It comes from mathematical notation for describing sets of strings. Regular expressions are used to find text that matches a pattern. Regular expressions are used in many programming languages and text editors.
  
## Summary

In this tutorial you will learn how to match emails with regular expressions using this expression /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

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
Anchors are used to match a position within the string. There are two types of anchors: start and end anchors. The start anchor ^ matches the position before the first character in the string. The end anchor $ matches the position after the last character in the string.So the expression going to end with $ and the expression going to start with ^.

### Quantifiers
Quantifiers are used to specify the number of times a character, group, or character class should be repeated. In this expression we have 3 quantifiers. The first one is {2,6} which means that the string should be between 2 and 6 characters long. The second one is + which means that the string should be at least 1 character long. The third one is * which means that the string should be at least 0 characters long.

### OR Operator
The OR operator is used to match one of several patterns. It is represented by the pipe symbol |. It doesn't seem to be used in this expression.

### Character Classes
Character classes are used to match any one of a specific set of characters. They are enclosed in square brackets. For example, [abc] matches a, b, or c. In this expression we have 3 character classes. The first one is [a-z0-9_\.-] which means that the string should contain only lowercase letters, numbers, underscores, dashes, and dots. The second one is [\da-z\.-] which means that the string should contain only lowercase letters, numbers, dashes, and dots. The third one is [a-z\.] which means that the string should contain only lowercase letters and dots.

### Flags
Flags are used to modify the search. There are three flags: g (global), i (case insensitive), and m (multiline).

### Grouping and Capturing
Grouping and capturing are used to match a sequence of characters. They are enclosed in parentheses. For example, (abc) matches abc.

### Bracket Expressions
Bracket expressions are used to match a single character out of several options. They are enclosed in square brackets. For example, [abc] matches a, b, or c. In this expression we have 3 bracket expressions. The first one is [a-z0-9_\.-] which means that the string should contain only lowercase letters, numbers, underscores, dashes, and dots. The second one is [\da-z\.-] which means that the string should contain only lowercase letters, numbers, dashes, and dots. The third one is [a-z\.] which means that the string should contain only lowercase letters and dots.

### Greedy and Lazy Match
Greedy and lazy match are used to match the longest or shortest possible string. Greedy match is the default behavior. Lazy match is achieved by appending a question mark to the quantifier. In this regular expression we have 2 greedy matches. The first one is {2,6} which means that the string should be between 2 and 6 characters long. The second one is + which means that the string should be at least 1 character long.

### Boundaries
Boundaries are used to match a position between a word character and a non-word character. There are two types of boundaries: word boundaries and non-word boundaries. The word boundary \b matches the position between a word character and a non-word character. The non-word boundary \B matches the position between a non-word character and a word character.

### Back-references
Back-references are used to match the same text as previously matched by a capturing group. They are represented by a backslash followed by a number. For example, \1 matches the same text as most recently matched by the first capturing group.

### Look-ahead and Look-behind
Look-ahead and look-behind are used to match a string without including it in the match. Look-ahead is shown by (?=) and look-behind is represented by (?<=).

## Author

This tutorial is written by Max Sciuclin.
