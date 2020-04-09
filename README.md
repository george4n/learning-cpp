# learning-cpp

This repository contains a bunch of example programs written in C++.

### Programs:

Program | Function | Keywords | Libs
------------ | ------------- | ------------- | -------------
001_HelloWorld | Opens a terminal and outputs "HelloWorld" | ```include``` |  ```cout``` ```cin``` ```endl```


## C++ Keywords

Keywords are pre-defined or reserved words in C++. Each keyword is meant to perform a specific function in a program. Since keywords are referred names for a compiler, they can’t be used as variable names because by doing so, we are trying to assign a new meaning to the keyword which is not allowed. You cannot redefine keywords. However, you can specify text to be substituted for keywords before compilation by using C++ preprocessor directives.

Keyword | Function |
---------- | ---------- |
test | Test

## C++ Identifiers

Identifiers are used as the general terminology for naming of variables, functions and arrays. These are user defined names consisting of arbitrarily long sequence of letters and digits with either a letter or the underscore "```_```" as a first character. Identifier names must differ in spelling and case from any **keywords**. You cannot use **keywords** as **identifiers**; they are reserved for special use. Once declared, you can use the **identifier** in later program statements to refer to the associated value. A special kind of identifier, called a statement label, can be used in goto statements.

### C++ Preprocessor Directives

###### The following tokens are recognized by the preprocessor when in context of a preprocessor directive:

``` include ``` - [Reference](https://en.cppreference.com/w/cpp/preprocessor/include) - Includes other source file into current source file at the line immediately after the directive.



### C++ Tokens
A token is the smallest element of a program that is meaningful to the compiler. Tokens can be classified as follows:

* Keywords
* Identifiers
* Constants
* Strings
* Special Symbols
* Operators
