# X-Team 02 Style Guide

Emphasis on descriptive naming and easily readable code.

## Naming conventions

Descriptive with attention to capitalization.

### Examples
* interfaces - Upper camel cased and describes the purpose of the interface prefixed by a capital I.
* classes - Upper camel cased and describes the purpose of the class.
* exception types - Upper camel cased and specifically describes the exception postfixed by Exception.
* fields - Lower camel cased with a descriptive name.
* methods - Lower camel cased and describes the purpose of the method limit 3 or 4 words.
* parameters - Lower camel cased and describes the purpose of the parameter.
* local variables - Lower camel cased and a breif but descriptive name.
* instance constants - All caps and underscores to separate words. Desciptive name.
* class constants - All caps and underscores to separate words. Desciptive name.

## Commenting style for public and private members of a class or interface:

Clear and consise comments. Describe stuff that's not obvious. Don't over comment.

### Examples

* classes - Javadoc at the top to describe what the class represents.
* fields - Inline comment describing the purpose of the field.
* constructors - Javadoc describing what it does. Use @param to describe parameters.
* methods - Javadoc describing what it does. Use @param and @return.
* coding style (brackets, horizontal, and vertical spacing) for:
  * if statements - `if (boolean) { }` if statements under 100 columns can go on one line.
  * switch statement - `switch (something) {` case blocks are indented and on own line.
  * while loops - Same format as if statements.
  * for loops - Same format as while and if.
  * enhanced for loops - `for (some something : someething) { }` spacing around colon.
