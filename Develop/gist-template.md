

```markdown
# Regex Tutorial: Exploring Regular Expression Components

Welcome to the Regex Tutorial. In this comprehensive guide, we will delve into various components of regular expressions, breaking down each part and explaining its functionality. This tutorial is designed to equip you with a solid understanding of the fundamental building blocks of regex patterns.

## Summary

In this tutorial, we will cover essential components of regular expressions, providing detailed explanations and examples for each. The following is the regex pattern that we will be exploring:

```regex
^pattern$
```

This pattern includes anchors, character classes, quantifiers, and more. Let's dive into the details!

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

Anchors are symbols that specify the position of a match within the text. The most common anchors are `^` (caret), which denotes the start of a line, and `$` (dollar sign), which denotes the end of a line.

**Example:**
```regex
^start
```
This regex matches any string that starts with "start."

### Quantifiers

Quantifiers specify the number of occurrences of a character or group in a regex pattern. Common quantifiers include `*` (zero or more), `+` (one or more), and `{n, m}` (between n and m occurrences).

**Example:**
```regex
\d{3}
```
This regex matches exactly three digits in a row.

### OR Operator

The OR operator (`|`) allows you to match either of two patterns in a regex. It provides a way to create alternatives in your pattern.

**Example:**
```regex
cat|dog
```
This regex matches either "cat" or "dog."

### Character Classes

Character classes enable you to match any character from a specified set. They are defined using square brackets (`[]`).

**Example:**
```regex
[aeiou]
```
This regex matches any single vowel.

### Flags

Flags modify the behavior of a regex pattern. Common flags include `i` for case-insensitivity and `g` for global matching.

**Example:**
```regex
pattern/i
```
This regex matches "pattern" case-insensitively.

### Grouping and Capturing

Grouping (`()`) and capturing in regex allow you to create sub-patterns and extract matched content.

**Example:**
```regex
(\d{2})-(\d{2})-(\d{4})
```
This regex captures a date in the format DD-MM-YYYY.

### Bracket Expressions

Bracket expressions (`[]`) match any single character from a range or a specified set.

**Example:**
```regex
[0-9]
```
This regex matches any single digit.

### Greedy and Lazy Match

Quantifiers in regex are greedy by default, meaning they match as much as possible. Lazy matching can be achieved by adding a `?` after the quantifier.

**Example:**
```regex
\d+
```
This regex greedily matches one or more digits.

### Boundaries

Boundaries (`\b`) in regex specify the edges of word boundaries or string boundaries.

**Example:**
```regex
\bword\b
```
This regex matches the word "word" as a whole word.

### Back-references

Back-references (`\1`, `\2`, etc.) allow you to match the same content that was previously captured in a regex.

**Example:**
```regex
(\w+) \1
```
This regex matches repeated words.

### Look-ahead and Look-behind

Look-ahead (`(?=…)`) and look-behind (`(?<=…)`) assertions in regex check for patterns without including them in the match.

**Example:**
```regex
\d(?= dollars)
```
This regex matches a digit only if it is followed by the word "dollars."

## Author

This tutorial is authored by Ian Cody. For more regex-related content and other projects, check out [CaveManEN](https://github.com/CaveManEN).
```
