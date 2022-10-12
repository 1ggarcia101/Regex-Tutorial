# Regex-Tutorial

Basic and concise tutorial on Regex.

## Summary


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

### Anchors

^The        matches any string that starts with The 
end$        matches a string that ends with end
^The end$   exact string match (starts and ends with The end)
roar        matches any string that has the text roar in it


### Quantifiers

abc*        matches a string that has ab followed by zero or more c 
abc+        matches a string that has ab followed by one or more c
abc?        matches a string that has ab followed by zero or one c
abc{2}      matches a string that has ab followed by 2 c
abc{2,}     matches a string that has ab followed by 2 or more c
abc{2,5}    matches a string that has ab followed by 2 up to 5 c
a(bc)*      matches a string that has a followed by zero or more copies of the sequence bc
a(bc){2,5}  matches a string that has a followed by 2 up to 5 copies of the sequence bc

### Grouping Constructs

### Bracket Expressions

[abc]            matches a string that has either an a or a b or a c -> is the same as a|b|c 
[a-c]            same as previous
[a-fA-F0-9]      a string that represents a single hexadecimal digit, case insensitively 
[0-9]%           a string that has a character from 0 to 9 before a % sign
[^a-zA-Z]        a string that has not a letter from a to z or from A to Z. In this case the ^ is used as negation of the expression 

### Character Classes

### The OR Operator

### Flags

g (global) does not return after the first match, restarting the subsequent searches from the end of the previous match
m (multi-line) when enabled ^ and $ will match the start and end of a line, instead of the whole string
i (insensitive) makes the whole expression case-insensitive (for instance /aBc/i would match AbC)

### Character Escapes

## Author

https://github.com/1ggarcia101/Regex-Tutorial