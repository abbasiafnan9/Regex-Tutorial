# Title (Regex Tutorial)
## What Is a Regex?

A **regex**, which is short for **regular expression**, is a sequence of characters that defines a specific search pattern. When included in code or search algorithms, regular expressions can be used to find certain patterns of characters within a string, or to find and replace a character or sequence of characters within a string. They are also frequently used to validate input. 

For example, the following regular expression can be used to verify that user input is a valid email address:

`/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/`

Each component of this regex has a unique responsibility to make sure that a user enters an email address that begins with an unspecified number of characters preceding the `@` symbol, followed by a domain.
## Summary
A regular expression is a pattern that is matched against a subject string from left to right. Regular expressions are used to replace text within a string, validating forms, extracting a substring from a string based on a pattern match, and so much more. The term "regular expression" is a mouthful, so you will usually find the term abbreviated to "regex" or "regexp".

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Grouping Constructs](#grouping-constructs)
- [Bracket Expressions](#bracket-expressions)
- [Character Classes](#character-classes)
- [The OR Operator](#the-or-operator)
- [Flags](#flags)
- [Character Escapes](#character-escapes)

## Regex Components
=> Matching Fixed Strings.
=> Matching Special Characters.
=> Matching Character Sets.
=> Specifying Groups and Fields.
=> Evaluating Occurrences.
=> Specifying Location.
=> Specifying Alternatives.
### Anchors
In regular expressions, we use anchors to check if the matching symbol is the starting symbol or ending symbol of the input string. Anchors are of two types: The first type is the caret ^ that checks if the matching character is the first character of the input and the second type is the dollar sign $ which checks if a matching character is the last character of the input string.
### Quantifiers
Quantifier matches the preceding element one or more times, but as few times as possible. It is the lazy counterpart of the greedy quantifier + . For example, the regular expression \b\w+?\ b matches one or more characters separated by word boundaries. The following example illustrates this regular expression.
### Grouping Constructs
Grouping constructs delineate the subexpressions of a regular expression and capture the substrings of an input string. You can use grouping constructs to do the following: ... Include a subexpression in the string that is returned by the Regex. Replace and Match.
### Bracket Expressions
A bracket expression is either a matching list expression or a non-matching list expression. It consists of one or more expressions: ordinary characters, collating elements, collating symbols, equivalence classes, character classes, or range expressions.
### Character Classes
The character class is the most basic regex concept after a literal match. It makes one small sequence of characters match a larger set of characters. For example, [A-Z] could stand for any uppercase letter in the English alphabet, and \d could mean any digit. Character classes apply to both POSIX levels.
### The OR Operator
You can use the | operator (logical OR) to match characters or expression of either the left or right of the | operator. For example the (t|T) will match either t or T from the input string.
### Flags
The flag s means dot all. That is, it makes the . dot character (technically refered to as the wildcard character) match everything, even newlines. In other words, with the s flag, the dot matches all possible characters. By default, the dot character in a regular expression matches everything, but newline characters.
### Character Escapes
Now, escaping a string (in regex terms) means finding all of the characters with special meaning and putting a backslash in front of them, including in front of other backslash characters. When you've done this one time on the string, you have officially "escaped the string".
## Author

For any questions => Github: abbasiafnan9
=> mailto: abbasiafnan9@gmail.com 
