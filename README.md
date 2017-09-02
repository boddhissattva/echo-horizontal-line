# Horizontal-line (v1.0) 

## Name
`horizontal-line` - print horizontal line of the terminal width with possible sentence in the middle.

## Install

    dpkg -i horizontal-line_1.0-1.deb

##i Synopsis

    horizontal-line [WORDS] [WIDTH] [-h|--help ] [-v|--version ]

## Overview
If `WORDS` is given, an horizontal line is printed with the string WORDS in the middle.

`WIDTH` is the width of the line.

`-h` and `-v` display the manual and the current version respectively.

# Examples
       $ horizontal-line
    ----------------------------------------------------------
       $ horizontal-line "my words"
    ------------------------ my words ------------------------
       $ horizontal-line "my words" 20
    ---- my words ----

##Contacts

For any suggestion or question, please send a mail at jean.yvan.tissot[at]gmail.com. Issues can be reported at http://github.com/boddhissattva/horizontal-line/issues
