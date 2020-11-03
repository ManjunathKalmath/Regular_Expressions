# Regular_Expressions

This Repository illustrates the Regular Expressions that are useful in reading the files with respect to Chip Design

## Regular Expressions

>Regular Expression way to represent the string

>Strings are sequence of ASCII Characters. Ex - SDFFX2, DFFRX1

## Use of Regular Expressions
1 - used in Chip Design
- Input and Output files are often text files
- Regular Expressions help to extract information from or modify text files

2 - Programming and Scripting Languages support Regular Expressions
- Such as Tool Command Language
- such as Command Line Perl

3 - Unix utilities grep and awk also support Regular Expressions

## Regular Expressions and Pattern Matching
1 -  Regular expressions are used for “pattern matching”
- An “a” followed by any three characters and then followed by “b” almxb, a3yzb, a$$jb: all of these match the pattern
then Regular expression is:  **/a.{3}b/**

- An “SDFF” followed by 0 or 1 letters, then followed by X, then followed by one or more digits
SDFFX1, SDFFRX4, SDFFX16: all of these match the pattern then Regular Expression is: **/SDFF\wX\d+/**

## Regular Expressions Characters
- [ad]   ==> Matches a or d
- [a-d]  ==> Matches any character a through d (a, b, c, or d)
- [^a-d] ==> Matches any character except a through d (e, f, g, h…)
- \w     ==> Matches any “word” character (a-z, A-Z, 0-9, _)
- \W     ==> Matches anything other than a “word” character
- \s     ==> Matches any whitespace character (space, tab or next line)
- \S     ==> Matches anything other than whitespace character (space, tab or next line)
- \d     ==> Matches any digit (0-9)
- \D     ==> Matches anything other than digit
- \n     ==> Matches next line

## Regular Expressions Quantifiers
- . ==>  Matches any character
- + ==> Matches the preceding character one or more times
- * ==> Matches the preceding character zero or more times
- ? ==> Matches the preceding character zero or one time
- {n} ==> Matches the preceding character exactly n times
- {n,} ==> Matches the preceding character n or more times
- {n,m} ==> Matches the preceding character between n and m times

## Regular Expressions Anchors
- ^ ==>  Match at beginning of the line
- $ ==>  Match at the end of the line
- \b ==> Match at a word boundary

## Acknowledgements
- Anand Bariya, VP at Open-Silicon
