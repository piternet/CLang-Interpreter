## CLang-Interpreter
_` (currently under development)`_

__Haskell interpreter of my own imperative language__. Interpreter is being made for Theory of Programming Languages classes.
Repository contains __`grammar.cf`__ file with EBNF grammar of the language. 


Language supports features such as:
* two types of variables: `int` and `bool`
* basic arithmetic and comparisions
* static type-checking
* functions with parameters given by value
* nested functions 
* built-in `puts` instruction, priting to the output
* Pascal-style `for` loop
* operators with side-effects, such as `+=`, `*=` etc.
* explicitly handled errors, such as division by zero
* overlapping identifiers, static scopes
* `int`-indexed arrays, maps
* Python-style tuples
