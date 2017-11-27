# Introduction to Programming

## Practical 6: Working with Lists

## Instructions

For this practical please work in pairs. Pair programming is used in practice where one person is the 'driver', works at the keyboard and types the program in, and the other person is the 'navigator'  who keeps a track of the strategic direction of the problem solving and reviews the code as it is entered. Pair programming does not rely on both programmers having the same level of experience in programming.

In pair programming the two participants should swap roles frequently. Try changing over between every exercise listed below.

### Level 1: A List of People

You need a class which includes a list of people (an
`ArrayList<Person>` to be precise). You could use the one of the classes 
from last practical (e.g. _Library_) or something like it. Make sure you have `getAge()`
and `getName()` methods in your _Person_ class. Then write methods
to find the following, making sure you return a value rather than
printing value:

1. The age of the oldest person. __Hint:__ use a local variable to store the biggest age so far in a for loop.
2. The name of the oldest person (the first one, if more than one person shares the greatest age).
3. The total age of the group.
4. The average (mean) age of the group.
5. The standard deviation of the age sqrt(sum((value-mean)^2))
6. Write a method which creates the list of people, executes these methods and displays the result.

### Level 2: Selecting from a list

Write methods to find the following. Think carefully about what the return type should be.

1. A list of all people who are at least 18 years old.
2. The name(s) of the oldest person (or people, if more than one personshares the greatest age).
3. A list of everybody apart from the oldest person.

### Level 3: More complex calculations

These are pretty tricky to do just with loops and lists, so don’t worry if
you can’t do them. There are other ways of doing them with sorting and maps
respectively. If you know how to do that, fine. If you want a challenge then try
to do them just with loops and lists.

Write methods to find:

1. The median age i.e. the middle age if people are put in order of age.
For now you can assume that everybody has a different age. __Hint:__ you could use your answer to the last part of level 2.

2. The mode i.e. the most frequently occurring age.