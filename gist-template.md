# Regex Tutorial - Email

## Summary

Tutorial explaining a for Expression matching an Email.
  /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

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
Regex Tutorial matching an Email.
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

- Always starts with /
- The ^ matches the beggining of the line
- Enclose each section in a pair of parenthesis. Parenthesis have no effect.
- [] Denotes character class.
- a-z Means any letter between a and z.
- 0-9 Means any number between 0 and 9.
- _ Allows underscore.
- \. Allows a literal period. A period (.) in Regex means any character whatsoever.
- -Allows hyphen.
- +Means it needs to be at least one letter but as many as you would like.
- @ At sign. The second part is the domain. Again it starts and ends ([ ]).
- \d Means any number between 0 and 9.
- a-z Means any letter between a and z.
- \. Allows period.
- -Allows hyphen.
- +Means it needs to be at least one letter but as many as you would like.
- \. Period between domain and extension.
- The third part is the extension. Again it starts and ends ([ ]).
- a-z Means any number between 0 and 9.
- \. Allows period.
- {2,6} Is the lenght. Allows a minimum of two letters and a maximum of 6.
- The $ matches the end of line
- Ends with /


### Anchors
Anchors are tokens that don't match any characters but that assert something about the string or the matching process.

### Quantifiers
Indicate numbers of characters or expressions to match.

### OR Operator
Match characters or expressions of either the left or right of the operator.

### Character Classes
Distinguish different types of characters.

### Flags
Flags affect the search.

### Grouping and Capturing
Indicate groups of expression characters. Parenthesis define the text between then as a group.

### Bracket Expressions
Used to match a single character or collating element.

### Greedy and Lazy Match
"Greedy" allows you to find the longest match while "Lazy allows the shortest.

### Boundaries
Make assertions about what can be matched.

### Back-references
Match the same text as previously matched by a capturing group.

### Look-ahead and Look-behind
Zero length assertions that matches characters but then gives up the match, returning only the result as match or no match.

## Author

Damaris Palacios
https://github.com/dslpz


