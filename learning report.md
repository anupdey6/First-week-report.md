# Week evaluation report
## Data Types and Operators
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


      



      

  

- Understanding operators
  - Arithmetic Operators
  - Comparison (Relational) Operators
  - Assignment Operators
  - Logical Operators
  - Bitwise Operators
  - Membership Operators
  - Identity Operators




