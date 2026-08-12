   # Regular Expression Syntax
    
    Regular Expression Syntax:
    
    a|b    Matches a or b
    gr(a|e)y    Matches gray or grey
    .    Matches any single character
    [abc]    Matches a single character a, b or c
    [^abc]    Matches any single character except a, b or c
    [a-z]    Matches a single character in the range a to z
    [a-zA-Z]    Matches a single character in the range a to z or A to Z
    ^    Matches the start of the filename
    $    Matches the end of the filename
    ( )    Defines a marked subexpression
    \n    Matches what the nth marked subexpression matched, where n is a digit from 1 to 9
    \b    Match word boundaries
    (*)   Matches the preceding element zero or more times
    ?    Matches the preceding element zero or one times
    (+)   Matches the preceding element one or more times
    *?    Lazily matches the preceding element zero or more times
    +?    Lazily matches the preceding element one or more times
    {x}    Matches the preceding element x times
    {x,}    Matches the preceding element x or more times
    {x,y}    Matches the preceding element between x and y times
    \    Escape special character
    \Q...\E    Literal sequence ...
    \a    Alarm, that is, the BEL character (hex 07)
    \cx    "Control-x", where x is any ASCII character
    \e    Escape (hex 1B)
    \f    Form feed (hex 0C)
    \n    Linefeed (hex 0A)
    \r    Carriage return (hex 0D)
    \t    Tab (hex 09)
    \0dd    Character with octal code 0dd
    \ddd    Character with octal code ddd, or back reference
    \o{ddd..}    Character with octal code ddd..
    \xhh    Character with hex code hh
    \x{hhh..}    Character with hex code hhh..
    \d    Any decimal digit
    \D    Any character that is not a decimal digit
    \h    Any horizontal white space character
    \H    Any character that is not a horizontal white space character
    \s    Any white space character
    \S    Any character that is not a white space character
    \v    Any vertical white space character
    \V    Any character that is not a vertical white space character
    \w    Any "word" character
    \W    Any "non-word" character
    \p{xx}    A character with the xx property
    \P{xx}    A character without the xx property
    \X    A Unicode extended grapheme cluster
    \b    Matches at a word boundary
    \B    Matches when not at a word boundary
    \A    Matches at the start of the subject
    \Z    Matches at the end of the subject also matches before a newline at the end of the subject
    \z    Matches only at the end of the subject
    \G    Matches at the first matching position in the subject
    
    
    