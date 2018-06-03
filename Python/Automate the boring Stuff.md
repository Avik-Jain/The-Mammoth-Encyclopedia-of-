Section 2
Video 5

### What is Truthy and Falsy in python? How is it different from True and False?

This condition is kind of weird the name variable is set to whatever the user is typed in but input
will be returning a string value not a boolean true or false value.
The reason this code works is that the conditions can use truthy and false values for strings.
The blank string is a falsie value condition evaluates to the blank string.
It's considered to be the same as the false Boolean values.
All the other non-blank string values are truthy values.

For instance, to see if a list is not empty, instead of checking like this:

if len(my_list) != 0:
   print "Not empty!"
You can simply do this:

if my_list:
   print "Not empty!"
This is because some values, such as empty lists, are considered False when evaluated for a boolean value. Non-empty lists are True.

Similarly for the integer 0, the empty string "", and so on, for False, and non-zero integers, non-empty strings, and so on, for True.

The idea of terms like "truthy" and "falsy" simply refer to those values which are considered True in cases like those described above, and those which are considered False.

For example, an empty list ([]) is considered "falsy", and a non-empty list (for example, [1]) is considered "truthy".


### To recap an if statement can be used to conditionally execute code depending on whether or not the if statements condition is true or false.

In l if that is an else if statement can follow an if statement in its block executes if the condition is true and all the previous conditions have been false in.

Else statement comes at the end.

Its block is executed if all the previous conditions have been false.

And finally the values zero zero point zero and the empty string are considered to be false values when used in conditions they are considered to be the same as the false Boolean values.
You can always see which for yourself which values are truth your falsie by passing them to the bool function
