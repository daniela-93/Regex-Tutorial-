# Regex-Tutorial-
# Understanding a Hex Value Regular Expression

This gist will contain information and explanations surrounding the regular expression for matching a Hex value.

## Summary
This expression is used to validate a string for an email. 

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/ 

## Table of Contents

- [Anchors](#anchors)
- [Quantifiers](#quantifiers)
- [Character Classes](#character-classes)
- [Grouping and Capturing](#grouping-and-capturing)
- [Bracket Expressions](#bracket-expressions)
- [Greedy and Lazy Match](#greedy-and-lazy-match)



## Regex Components
/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/ 
- Anchors /^ and $/
- Quantifiers + {2,6}
- Character classes /d 
- Grouping and Capturing ()
- Bracket Expressions [a-z0-9_\.-] [\da-z\.-] [a-z\.]

### Anchors
- Anchors are the start and the end of a line. 
-  /^ and $/ 
- When a regex begins with ^ and ends with $ they work to search for an exact match for the string that is in between them. 

### Quantifiers
- Quantifiers are used to show how many characters in the expression need to be found based on the preceeding criteria 
- {2,6}
- {2,6} are used to make sure that 2,3,4,5, or 6 characters are found. 

### Character Classes
- Character classes are used to show if theres a digit, White space, not digit, or not word. 
- /d 
- /d in this case theres a digit before a letter that could be anything between a-z lowercase only. 


### Grouping and Capturing
- () is used to place all criteria into an array 
-([a-z0-9_\.-]+)@([\da-z\.-]+) ([a-z\.]{2,6})

### Bracket Expressions
- Meant to capture a single character within the specified criteria. 
- [a-z0-9_\.-] [\da-z\.-] [a-z\.]
- The a-z and 0-9 signifies any letter or number in that range and case. 



## Author
Daniela Acuna [Github](https://github.com/daniela-93)
