#Metacharacters

```^``` Start of a string

```$``` End of a string

```.``` Any character (except \n newline)

```|``` Alternation (OR)

```{...}``` Explicit quantifier notation

```[...]``` Explicit set of characters to match

```(...)``` Logical grouping of part of an expression

```*``` 0 or more of previous expression

```+``` 1 or more of previous expression

```?``` 0 or 1 of previous expression; also forces minimal matching when an expression might match several strings within a search string

```\``` Preceding on of the above, it makes it a literal instead of a special character.


#Character Classes

```[aeiou]``` Matches any single character included in the specified set of characters

```[^aeiou]``` Matches any single character not in the specified set of characters

```[0-9a-fA-F]``` Use of a hyphen (-) allows specification of contiguous character ranges

```\w``` Matches any word character

```\W``` Matches any non-word character

```\s``` Matches any white-space character

```\S``` Matches any non-white-space character

```\d``` Matches any decimal digit

```\D``` Matches any non-decimal digit


#Examples

###Username

- username can have letters, numbers, underscores and hyphens.
- username must be from 3 to 16 characters long

``` ^[a-z0-9_-]{3, 16}$ ```

###Hex

- must be 3 or 6 characters long
- can include numbers and letters a-f
- can optionally be prefixed with #

```^#?([a-f0-9]{6}|[a-f0-9]{3})$ ```

###Email

- first part can have numbers, letters, underscores, hyphens and dots
- username part is followed by @ symbol
- second part can also have numbers, letters, underscors, hyphens, dots
- then followed by domain suffix that can be 2 to 6 letters, and can include dots (e.g. co.uk)


``` ^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$ ```



#Regex Golf solutions - http://regex.alf.nu/

###Warmup

```foot*```

###Anchors

```ick$```

###Ranges

```[a-f]{4}```

###Backrefs

```(.{3}).*\1```

###Abba

?
