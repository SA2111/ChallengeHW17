# Regex Tutorial

Introductory paragraph:
This is a tutorial on Regex and all of its components.

## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

What is Regex? Regex or regular expression is a type of syntex that can be used in changing and/or editing text strings. It can be used in any language and can make it easier and shorter to write code.

Example: Hello\nworld

Output: Hello
        world

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
* ^start- connects a string that begins with start
* finish$- connects a string that ends with finish
* ^start finish$- connects the strings from begining to end

### Quantifiers
* Quantifiers set a limt as to how meny times a charecter is present in the input for a match to be present. Quantifies can be classified as "greedy" or "lazy. Most quantifires are greedy. A greedy quantifier matches as meny times as possible. A lazy quantifier matches matches a few times as possible. They both match occuances of specific patterns.
* Example:
* Greedy Quantifier = *
* Lazy Quantifier = *?
* Referance = https://learn.microsoft.com/en-us/dotnet/standard/base-types/quantifiers-in-regular-expressions#Greedy
### OR Operator
* The OR Operator give the user the ability to find substrings that match with similar strings. An example would be if a user wants to match the string 'car' and 'bike'. A way to use this in python is by adding a "|" sign in bettween the two strings.
* Example
* (car|bike)
* Referance- https://blog.finxter.com/python-regex-or/
### Character Classes
* Charecter classes allowes the user to match one out of multiple charecters. You would do this by puting the charecter you want to match into the brackets. For example [a] would match a string that has an "a" in it. If you want to math two charecters such as a or y then you would put them in brackets such as [ay]. This could be used in the word 'delay' to match 'dela' or dely.
* Referance- https://www.regular-expressions.info/charclass.html
### Flags
* Regex can contain flags that disrupt the search. These are the types of flags a regex can have:
* i - This occures when the search is case sensitive
* s - This occures when the search allows a . to match a newline charecter
* y - This occures when the search allows the user to search at the position of the source string
* Referance - https://javascript.info/regexp-introduction
* Referance - https://javascript.info/regexp-sticky
### Grouping and Capturing
* Capturing allows the user to take a group of charecters and use them as one.
* Referance - https://docs.oracle.com/javase/tutorial/essential/regex/groups.html
### Bracket Expressions
* 
### Greedy and Lazy Match
* Quantifies can be classified as "greedy" or "lazy. Most quantifires are greedy. A greedy quantifier matches as meny times as possible. A lazy quantifier matches matches a few times as possible. They both match occuances of specific patterns.
* Example:
* Greedy Quantifier = *
* Lazy Quantifier = *?
* Referance = https://learn.microsoft.com/en-us/dotnet/standard/base-types/quantifiers-in-regular-expressions#Greedy
### Boundaries
* 
### Back-references
* A back referance is described as a backslash with the number of the group the user is using.
* Example: ([abc])\1
* Referance - https://docs.oracle.com/javase/tutorial/essential/regex/groups.html


### Look-ahead and Look-behind
* 
## Author
* 
A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
