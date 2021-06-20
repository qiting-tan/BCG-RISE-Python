# Program-list-o-matic
This program requires creating a function using def and return, using print output, input, if, in keywords, .append(), .pop(), .remove() list methods. As well as other standard Python
Program: list-o-matic
This program takes string input and checks if that string is in a list of strings

if string is in the list it removes the first instance from list
if string is not in the list the input gets appended to the list
if the string is empty then the last item is popped from the list
if the list becomes empty the program ends
if the user enters "quit" then the program ends
program has 2 parts

program flow which can be modified to ask for a specific type of item. This is the programmers choice. Add a list of fish, trees, books, movies, songs.... your choice.
list-o-matic Function which takes arguments of a string and a list. The function modifies the list and returns a message as seen below.


[ ] initialize a list with several strings at the beginning of the program flow and follow the flow chart and output examples

example input/output

look at all the animals ['cat', 'goat', 'cat']
enter the name of an animal: horse
1 instance of horse appended to list

look at all the animals ['cat', 'goat', 'cat', 'horse']
enter the name of an animal: cat
1 instance of cat removed from list

look at all the animals ['goat', 'cat', 'horse']
enter the name of an animal: cat
1 instance of cat removed from list

look at all the animals ['goat', 'horse']
enter the name of an animal:          (<-- entered empty string)
horse popped from list

look at all the animals ['goat']
enter the name of an animal:          (<-- entered empty string)
goat popped from list

Goodbye!
example 2

look at all the animals ['cat', 'goat', 'cat']
enter the name of an animal: Quit
Goodbye!
