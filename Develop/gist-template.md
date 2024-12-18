# CS_JS17

Regular expression(regex) can be a difficult concept to percieve. With the help of this gist, you will be able to break regex and understand its components.
Introductory paragraph (replace this with your text)

## Summary

Regular expressions are used to search and find patterns with a string of text. Regex is an advance way of searching through text and grouping those searches together. They can also be used in all programming languages.
`/^#?([a-f0-9]{6}|[a-f0-9]{3})$/`

    Breakdown of the regex ^#?([a-f0-9]{6}|[a-f0-9]{3})$:

- ^: Matches the beginning of the string.
- #?: Matches an optional "#" symbol.
- ([a-f0-9]{6}|[a-f0-9]{3}): Matches either 6 or 3 hexadecimal characters (a-f and 0-9).
- $: Matches the end of the string.
- This regex ensures the input string is a valid hexadecimal color code.

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

    Regex components are litteral and need to be wrapped in (/).

### Anchors

    Anchors: ^ $
    - ^ anchor: When ^ is used, it marks that it is a string that will start with a character that follows it.
    Example: ^And
        Using this string will find: "And" & "And you"
        But will NOT find "and" & "and you"
        so make sure to be exact with upper or lowercase, because regex is case sensitive.
    - $ anchor: This marks a string that will end with chararters that come before  it.
    Example: End$
        Using this string will find "the End" & "that End"
        This string is also capital sensitive.

### Quantifiers

    Qualifiers are used to set limits to the string that is being matched. Qualifiers will have the min and max numbers.

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

    Character classes are a set of characters that will attain a match in a string.
    Some characters that you will see often will look like
    - . : With a dot you can match any charater. except newline character(\n)
    - \d : Will match any Arabic numeral digit. This is equal to [0-9] expression.
    - \w : Matchs any alphanumeric character and anything with underscore (_). This is the same as [A-Za-z0-9_].
    - \s : This will match a single whitespace character, tabs, and line breaks.

### The OR Operator

### Flags

### Character Escapes

    Using the backslash (\) allows for a character to escape so it would not be considered literal. When we use the ({), we are starting a quantifier. When a backslash is added (\{), the reges will look for the open curly ({).
    Special characters like the backslash (\) do lose their signifivance when they're inside bracket expressions.

## Author

    Tala Awwad is the author of CS_JS17
    For any questions:
    Email: awwad.tala1@yahoo.com
    Github: https://github.com/awwtala

A short section about the author with a link to the author's GitHub profile (replace with your information and a link to your profile)
