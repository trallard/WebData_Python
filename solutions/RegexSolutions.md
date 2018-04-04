## Exercise 1.1

a) option iii) fits the description. You might also have chosen option ii), which would match the described pattern, but would also match other non-vowel letters in the middle two positions.

b) [A-z] matches all letter characters (both upper and lower case). [a-Z] is an invalid set. [A-9] will match any letter or digit character.

## Exercise 1.2

a) \d\d\-\d\d\-\d\d\d\d

b) There are 25 matches in the file (every even record). Note that there are a few caveats with that regex, such that it will also match strings like 131.01.20171 or 99.99.9999.

```person = open('./example_files/person_info.csv', 'r')
people = person.read().split()
show_matches(r'\d\d\.\d\d\.\d\d\d\d', people)```


## Exercise 1.3
a) `ATG?CT+CG`
b) `show_matches(r'(.*)-(.*)-(.*)', words)`


## Exercise 1.4
a) `[a-zA-Z0-9]\S*@\S*[a-zA-Z]`
Translating this regular expression, we are looking for substrings that start with a single lowercase letter, uppercase letter, or number "[a-zA-Z0-9]", followed by zero or more non-blank characters ("\S*"), followed by an at-sign, followed by zero or more non-blank characters ("\S*"), followed by an uppercase or lowercase letter. Note that we switched from "+" to "*" to indicate zero or more non-blank characters since "[a-zA-Z0-9]" is already one non-blank character. Remember that the "*" or "+" applies to the single character immediately to the left of the plus or asterisk.

b) Use the regex `Pictures\/(France-2015)\/`

