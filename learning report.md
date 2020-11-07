# Week evaluation report

| Table of content   |     |
| --- | --- |
| [Task-1](#Task-1) | [Task-2](#Task-2) |
| [Task-3](#Task-3) | [ Task-4](#Task-4) |

<!--ts-->
   * [Task-1](#Task-1)
   * [Task-2](#Task-2)
   * [Task-3](#Task-3)
   * [Task-4](#Task-4)
<!--te-->



# Task-1

  - What Is Python?
  - What can Python do?
  - How does Python work?
  - Install Python
  - Visual studio code


---


# Task-2

Data Types and Operators
- Variables and Data Types
  - Variable

  Variables are reserved memory locations to store values. This means that when you create a variable you reserve some space in memory.

   - Data Types

  The data type of a value determines which kind of data it can hold and which kind of operations can be performed on it. For example, ‘+‘ operator for numbers mean addition, however, for string(s), it is joining them together into a single string.

  ![alt text](https://dsft.code-data-ai.com/wp-content/uploads/2019/12/data_types.jpg)

  1. Numeric


      - Integer

      Intergers – This value is represented by int class. It contains positive or negative whole numbers (without fraction or decimal). In Python there is no limit to how long an interger value can be.
      - Float – This value is represented by float class. It is a real number with floating point representation. It is specified by a decimal point. Optionally, the character e or E followed by a positive or negative integer may be appended to specify scientific notation.

  2. Bolean

     A Boolean value expresses a truth value (which can be either true or false). So, it can contain the two built-in values, True or False.
  3. Sequential

     In Python, sequence is the ordered collection of similar or different data types.
       - List 

            Lists are just like the arrays, declared in other languages. Lists need not be homogeneous always which makes it the most powerful tool in Python.

          A. List Methods

          Methods that are available with list object in Python programming are tabulated below.

          append() - Add an element to the end of the list
          extend() - Add all elements of a list to the another list
          insert() - Insert an item at the defined index
          remove() - Removes an item from the list
          pop() - Removes and returns an element at the given index
          clear() - Removes all items from the list
          index() - Returns the index of the first matched item
          count() - Returns the count of number of items passed as an argument
          sort() - Sort items in a list in ascending order
          reverse() - Reverse the order of items in the list
          copy() - Returns a shallow copy of the list
      - String

           In Python, Strings are arrays of bytes representing Unicode characters. A string is a collection of one or more characters put in a single quote, double-quote or triple quote.

           A.String Methods

            Here are some of the most common string methods. A method is like a function, but it runs “on” an object.

             s.lower(), s.upper() — returns the lowercase or uppercase version of the string

             s.strip() — returns a string with whitespace removed from the start and end

             s.isalpha()/s.isdigit()/s.isspace()… — tests if all the string chars are in the various character classes

             s.startswith(‘ai’), s.endswith(‘ai’) — tests if the string starts or ends with the given ai strin

             s.find(‘other’) — searches for the given other string (not a regular expression) within s, and returns the first index where it begins or -1 if not found

             s.replace(‘old’, ‘new’) — returns a string where all occurrences of ‘old’ have been replaced by ‘new’

             s.split(‘delim’) — returns a list of substrings separated by the given delimiter. The delimiter is not a regular expression, it’s just text. ‘aaa,bbb,ccc’.split(‘,’) -> [‘aaa’, ‘bbb’, ‘ccc’].
             As a convenient special case s.split() (with no arguments) splits on all whitespace chars.

             s.join(list) — opposite of split(), joins the elements in the given list together using the string as the delimiter.e.g. ‘—‘.join([‘aaa’, ‘bbb’, ‘ccc’]) -> aaa—bbb—ccc


           B. Python String Operations

               - Concatenation of Strings:
               
                 Joining of two or more strings into a single one is called concatenation.

                - Escape Sequence:

                  An escape sequence starts with a backslash and is interpreted differently. If we use single quote to represent a string, all the single quotes inside the string must be escaped. Similar is the case with double quotes. Here is how it can be done to represent the above text.

                - Formatting Strings:

                  The format() method that is  available with the string object is very versatile and powerful in formatting strings. Format strings contains curly braces {} as placeholders or replacement fields which gets replaced.

       - Tuple

           Tuple is an ordered collection of Python objects much like a list. The sequence of values stored in a tuple can be of any type, and they are indexed by integers.

           The important difference between a list and a tuple is that tuples are immutable which means you can not modify the elements in a tuple.

             A. Accessing element of a tuple:

               In order to access the tuple items refer to the index number. Use the index operator [ ] to access an item in a tuple. The index must be an integer.

             B. Deleting/Updating elements of tuple:

               In python, deletion or Updation of a tuple is not allowed.

               This is because tuples are immutable, hence elements of a tuple cannot be changed once it has been assigned. Only new tuples can be reassigned to the same name.



  4. Container
     
     Dictionaries and sets are containers for sequential data.

       - Set

          Set is an unordered collection of data type that is iterable, mutable and has no duplicate elements.

            A. Creating a set:

               Sets can be created by using the built-in set() function with an iterable object or a sequence by placing the sequence inside curly braces, separated by ‘comma’.

               A set contains only unique elements but at the time of set creation, multiple duplicate values can also be passed.

            B. Adding Elements to a Set:

               Elements can be added to the Set by using built-in add() function.

               Only one element at a time can be added to the set by using add() method.
               For addition of two or more elements Update() method is used.

            C. Accessing a Set:
               
               Set items cannot be accessed by referring to an index, since sets are unordered the items has no index. But you can loop through the set items using a for loop, or ask if a specified value is present in a set, by using the in keyword.

            D. Removing elements from a set:

               Elements can be removed from the Set by using built-in remove() function but a KeyError arises if element doesn’t exist in the set. To remove elements from a set without KeyError, use discard(). 

               Pop() function can also be used to remove and return an element from the set, but it removes only the last element of the set.

               To remove all the elements from the set, clear() function is used.

          
          
          
          
          Sets can be used to carry out mathematical set operations like union, intersection, difference and symmetric difference.

        A. Set Union:

        ![alt text](https://dsft.code-data-ai.com/wp-content/uploads/2019/12/set_u.jpg)

          Union of A and B is a set of all elements from both sets.

          Union is performed using | operator.


        B. Set Intersection:

        ![alt text](https://dsft.code-data-ai.com/wp-content/uploads/2019/12/seti.jpg)

           Intersection of A and B is a set of elements that are common in both sets.
           Intersection is performed using & operator. 

        C. Set Difference:

        ![alt text](https://dsft.code-data-ai.com/wp-content/uploads/2019/12/setd.jpg)

            Difference of A and B (A – B) is a set of elements that are only in A but not in B. Similarly, B – A is a set of element in B but not in A.
            Difference is performed using - operator.

        D. Set Symmetric Difference:

        ![alt text](https://dsft.code-data-ai.com/wp-content/uploads/2019/12/setsd.jpg)

            Symmetric Difference of A and B is a set of elements in both A and B except those that are common in both.
            Symmetric difference is performed using ^ operator.

       - Dictionary
          
           Dictionary in Python is an unordered collection of data values, used to store data values like a map.

           Note – Dictionary keys are case sensitive, same name but different cases of Key will be treated distinctly.

              A. Adding elements to a Dictionary:

                 In order to access the items of a dictionary refer to its key name. Key can be used inside square brackets. There is also a method called get() that will also help in accessing the element from a dictionary.

              B. Removing Elements from Dictionary:

                 In Python Dictionary, deletion of keys can be done by using the del keyword.

                 Using del keyword, specific values from a dictionary as well as whole dictionary can be deleted. Other functions like pop() and popitem() can also be used for deleting specific values and arbitrary values from a Dictionary. All the items from a dictionary can be deleted at once by using clear() method.



  

- Understanding operators
  - Arithmetic Operators
  - Comparison (Relational) Operators
  - Assignment Operators
  - Logical Operators
  - Bitwise Operators
  - Membership Operators
  - Identity Operators


---
# Task-3

[Decision Making](https://techvidvan.com/tutorials/decision-making-in-python/)

Decision making is the anticipation of conditions occurring while execution of the program and specifying actions taken according to the conditions.

Decision structures evaluate multiple expressions which produce TRUE or FALSE as an outcome. You need to determine which action to take and which statements to execute if the outcome is TRUE or FALSE otherwise.




 [Conditional Statements and Loop](https://www.openbookproject.net/books/bpp4awd/ch04.html)

  - Conditional execution
    - The if statement
    -  The if else statement
- Chained conditionals
- Nested conditionals
- Iteration
- The for loop
- Tables
- The while statement
- The break statement
- The continue statement
- List comprehensions

[Assignments](https://dsft.code-data-ai.com/python-workshops/)

---

# Task-4 

  - [Functions](https://www.openbookproject.net/books/bpp4awd/ch05.html)
  - How to write a script?
  - [Guessing Game](https://colab.research.google.com/drive/16AN9ABewjIgRZIwrREkJRBVJ1kqJbap1)



# For more information you can find find in following links :


[![alt text][1.1]][1]
[![alt text][2.1]][2]
[![alt text][3.1]][3]


[1.1]: http://i.imgur.com/P3YfQoD.png (facebook icon with padding)
[2.1]: http://i.imgur.com/yCsTjba.png (google plus icon with padding)
[3.1]: http://i.imgur.com/0o48UoR.png (github icon with padding)


[1]: https://www.facebook.com/anup.dey.315
[2]: https://myaccount.google.com/profile?pli=1
[3]: https://github.com/anupdey6





