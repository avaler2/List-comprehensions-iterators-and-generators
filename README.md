# List and dict comprehensions, iterators and generators
The topic is related to Python Statements and Loops module but extends it.
In this exercise, we will focus on the usage of the list comprehensions, dictionary comprehensions as well as iterators and function generators.

## Tasks
### Task 1.:heavy_plus_sign: Converting list comprehensions into a for loop
Convert the following list comprehension into a for loop:

- myList = [x for x in range(0, 100, 10)]

Print the results to compare the outcome of both types of loop.

### Task 2.:heavy_plus_sign: Using list comprehensions
- Create a newList using list comprehension 
- Fill a new list with 10 values by raising the contents in myList to the power of 3. 
- Exclude from the new list items equal to or less than 10.
- Print all of the results using manual iteration (use iter function to print individual items)

### Task 3.:heavy_plus_sign: Using dictionary comprehensions
- Create a dictionary of key-value pairs using dictionary comprehension.
- Keys should be strings and values should be numbers from myList variable.
- Write the code to save the dictionary from Task 3 to a file 'dict.txt'
- Print the results of reading the file

### Task 4.:heavy_plus_sign: Generator functions
- Building on the previous example, read the dictionary from 'dict.txt' using a function generator
- Imagine that the file contains 1 mln records and you cannot print them out at once using a for loop
- Create a function that will return each line from the dict.txt file.
- Print only first three results using the next method.
