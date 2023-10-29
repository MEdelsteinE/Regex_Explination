# Title (replace with your title)

Break down of an e-mail regex,

## Summary

/^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/. This is an e-mail regex. I will be describing 6 parts of this expression. For example the first parenthesis looks for lowercase letters, numbers, underscores, dots, and/or hyphens.


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
The anchors of  this regex are the '^' and the '$'. The '^' is the start of the expression and the '$' is the end of the expression
### Quantifiers
A quantifier controls the number of times a character or characters can repeat in a pattern. in this case the '+' is the quantifier.
### OR Operator
An OR operator is marke dby a vertical bar. It allows to match one pattern or another. This regex does not include an OR Operator.
### Character Classes
Character Classes define a set of characters that you want to match in a single position in the input string. They make it easier to match characters regardless of their order in the inputted string. In this regex the '/d' matches a digit from 0-9. The '/w' matches a word charcter including digits. The'/s' matches a whitespace character. The '/D' is for any non digit character. The 'W/' matches a non word character. The '/S' matches with a non whitespace character. '[]' matches a singular character inside of the brackets. 
### Flags
Whereas there ar eno Flags in this regex, Flags are used to enable matching options. For example case insensitive macthing.
### Grouping and Capturing
Grouping and Capturing allows for multiple characters to be treated a sigle unit and allows for captured text to be processed as a group. In this regex the '(' ')' are used for grouping and capturing.
### Bracket Expressions
Bracket expressions are used to define a character class. such as lowercase characters. In this regex the '[' ']' are Bracket expressions.
### Greedy and Lazy Match
Greedy and Lazy Match refers to quantifiers when they are used to match pattersn in a string. An example of a greedy qualifier is the '+' symbol. When applied to a character it will match all cosecutive characters attacthed to the '+'. An example of a lazy qualifier is the '?'. When applied to a character its will  match the shortest part of the string. In this regex all of our qualifiers are greedy.
### Boundaries
Boundries specifiy edges of words or lines. They don't match any characters but instead determin if a match is possible at the begining or end of a word or string. '/b' and '/B' are examples of Boundires.  Boundries are focused on the inner text of a regex.
### Back-references
Back refences refer to captured groups inside the regex. They are captured by parenthesis and can be refenced later in the expression or replacement string. 
### Look-ahead and Look-behind
Look-aheads and Look-behinds make sure that a pattern is not followed or proceeded by another without including the matched pattern. These are used for making sure a particular pattern is included or not lincluded  without it being included in the matching result. Combined with Boundries you can create more complex regex to match patterns or perform complex text manipulations.
## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)