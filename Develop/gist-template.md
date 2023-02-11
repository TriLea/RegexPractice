# Hex code regex
/^#?([a-fA-F0-9]{6}|[a-fA-F0-9]{3})$/  hex value regex search

## Summary

With this regex you can match hex codes in a string. It will match the following formats: /^#?([a-fA-F0-9]{6}|[a-fA-F0-9]{3})$/

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
Regex components are used to match a pattern in a string. In our example we used the following components:

### Anchors
the two forward slashes // represent the beginning and end of the query found at both
the very start and end
the hat and dollar sign ^$ represent the beginning and end of the String

### Quantifiers
the braces {} after the [] within the paranetheses () 
descries the amount if characters to look for
the question mark ? makes the charater in front of it optional,
such as the hashtag in our example

### OR Operator
the or operator |
represents two potential answers on both sides of the operator

### Character Classes
a-f, A-F, 0-9,
represent ranges of chracters and integers respectively to look for.
a-f being all characters inbetween, 0-9 being all numbers inbetween

### Flags
Flags are used to modify the search. In our example we used the g flag to search for all instances of the hex code

### Grouping and Capturing
Grouping and Capturing are used to match a pattern multiple times in a string.

### Bracket Expressions
the braces [] represent the singular string being searched which can
be searched for multiple times with to find longer instances with the quantifiers 
such as {6} and {3} in our hex example
the parantheses () represent hte returend string

### Greedy and Lazy Match
Greedy and 

### Boundaries
A boundary allows you to match a pattern only at the beginning or end of a word.
We used the boundary to match the beginning of the string with the hat ^ and the 
end of the string with the dollar sign $

### Back-references
Back-references are used to match the same text as previously matched by a capturing group.

### Look-ahead and Look-behind


## Author
Tristan Lea

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
