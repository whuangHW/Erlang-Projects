# Erlang - Projects:
![][logo]
[logo]:https://github.com/weihuang023/Erlang-Projects/blob/master/ErlangLogo.png 
[Cheat Sheet](https://github.com/weihuang023/Erlang-Projects/blob/master/CheatSheet.jpg)

## tut - _Basic Information about Erlang file_
* Each file contain an Erlang Module
* "." is End of the line
* file name is ".erl"
* -export contain argument and that is funcation can be use from outside module

## tut1 - _What is in Fucntion?_
* A Fuction have many arguments. (- export: fac/1 and mult/1)

## tut2 - _What are arguments?_
* Converting from inch to centimeter or converting from centimeter to inch
* One arugments can have many fucntion 

## tut3 - _Fucntion and Argument_
* tut3:convert_length(tut3:convert_length({inch,5})). This is reassurinigly get back to the original value.
* metric conversion : the arugment to a fucntion can be result of another fucntion

## Data Types
-
* There are two types of  numberic literals, integers and floats
* number < atom < reference < fun < port < pid < tuple < list < bit string
* Variable is binding a value and mutiple variable are able to assign values simultaneously 

#### Atom
-
* Identifying a value 
* boolean logic 
* start with lower case charater or delimit with singlw quotes

#### Tuple 
-
* Composite date type and store collections of items
* delimited by curly brackets
* Term in Tuple is an element and element Index with 1 as the first value instead of 0
* the number of element is the size of tuple
* First value is an atom, _a tag and this can be used to identify or classify the contents_

#### List
-
* denoted by Square Brackets
* using ++ operator to merge list 
* diff between list and tuple
  + a tuple can only be used in comparison
  + a list allow a wider variety of manipulation operation to be performed

#### Strings
-
* Can be store as a list of the ASC II Character values (int)
* use $, double quote, single quote to specify character in List of Character

## Write output to a Terminal _io:format_
* io:format("Display in Terminal~n",[]).
* io:format("Display the variable word: ~w~n",[Word]).
* space will show in terminal.
* ~n new line
* function itself returns the atom ok if everything goes as planned.



