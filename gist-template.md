# Regular Expressions Tutorial

This gist is to give a tutorial on what a regular expression (regex) is and how they can be used. A Regex is a way of describing patterns in a string of data, which allows you to search for data strings that match that pattern. Regexs are important part of programming languages like JavaScript, Phython, PHP, Java and others.

## Summary

This gist is going to cover how to use a Regex for matching emails. This can be used to validate if an email is followng the correct format that is necessary. 

Matching Email - /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

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

The anchor is used to start and end the regex. In the matching email code, /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/ the anchors would be the up carrot (^) and the  dollar sign ($). This email matching code is saying we are looking for something that starts with ^([a-z0-9_\.-]+).

Defining what everything means within the parentheses will be done later in the tutorial, but the anchor is looking for a match while following these initial guidelines. 

The code also ends with .([a-z\.]{2,6})$.

The code must start and end with parameters within the code or it will not match.

### Quantifiers



### Grouping Constructs

### Bracket Expressions

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
