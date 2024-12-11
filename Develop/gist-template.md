# Title (replace with your title)

Introductory paragraph (replace this with your text)

## Summary

Briefly summarize the regex you will be describing and what you will explain. Include a code snippet of the regex. Replace this text with your summary.

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

    Regex components

### Anchors

    The two letters that are considered arches would be: ^ $
    -

### Quantifiers

### Grouping Constructs

    (bcd):(qrs)
    When you use a group constructs, it may look something like what we have above.
    When you are looking for multiple numbers or words at the same time, this is the best method to use.
    Pranthese have to be used followed by a colon, which is the string.
    Each section thats in the parenthese is known as a subexpression.
    When this is written, you are saying that you would like to find an exact match for "bcd" and "qrs".
    The match you want to find has to be the exact writting that is in the parenthese.

### Bracket Expressions

    Bracket expressions [] consist of what we want to match. bracket expressions are also called positive charater group, because they present the characters we want to group together.
    Example: [xyz]
    The brackets will look for a string that will start with either x, y, and z. The length of the string wont matter.

    Bracket expressions can also have hyphens in them. hypens This will indcate that you want to find everything from the first point to the last, everything between.
    Example: [k-z], [1-6].
    Using the hypen between the two letters or numbers will bring back everything k to z and 1 to 6.
    When it comes to letters, if they are written in lowercase inside the bracket, it will only find lowercase.
    We also have [_-]. Both of the underscore and hypen are known as special charaters. We want a string to include either or, because it will look for speical charaters such as punctuations or symbols.

### Character Classes

### The OR Operator

### Flags

### Character Escapes

## Author

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
