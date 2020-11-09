

# First Week Evaluation CABerlin #

![Header picture](https://2s7gjr373w3x22jf92z99mgm5w-wpengine.netdna-ssl.com/wp-content/uploads/2018/09/data_science_shutterstock_shutterstock_Trueffelpix.jpg)

Learning the sexiest job in the market with [CA Berlin](https://www.codeacademyberlin.com/)


Table of contents:
<!--ts-->
   * [Chapter 1](#chapter1)
   * [Chapter 2](#chapter2)
   * [Chapter 3 ](#chapter3)
   * [Chapter 4](#chapter4)
<!--te-->

---
**Chapter 1 :**

This chapter we learned about the basics of [Python](https://en.wikipedia.org/wiki/Python_(programming_language)) why it is impotant for [data science](https://de.wikipedia.org/wiki/Data_Science) and how the basics works. Python is basically a [High Level Language](https://en.wikipedia.org/wiki/High-level_programming_language). 


The second part we got introduced with [Visual Studio](https://code.visualstudio.com/docs/setup/setup-overview) and how it reacts with [Git Hub](https://github.com/CodeAcademyBerlin/content). And for the last part we started working with the famously used [calendly](https://calendly.com/jost_cab/meetin) for Code Academy Berlin. 


---
**Chapter 2 :**
This chapter of the week we actually started coding with python but before we learned how to put all of our team workflow in the same line by using [Trello](https://trello.com/en). 

[Data Types](https://dsft.code-data-ai.com/data-types-python/)- Basically in this segment we learned about different types of data types and operators in python.



![Data Types](https://dsft.code-data-ai.com/wp-content/uploads/2019/12/data_types.jpg) 

1. Numeric : 

- [Intergers](https://www.geeksforgeeks.org/python-int-function/) – This value is represented by int class. It contains positive or negative whole numbers (without fraction or decimal). In Python there is no limit to how long an interger value can be.

- [Float](https://www.programiz.com/python-programming/methods/built-in/float) – This value is represented by float class. It is a real number with floating point representation. It is specified by a decimal point. Optionally, the character e or E followed by a positive or negative integer may be appended to specify scientific notation.

2. [Boolean](https://www.w3schools.com/python/python_booleans.asp) :

A Boolean value expresses a truth value (which can be either true or false). So, it can contain the two built-in values, True or False. Boolean objects that are equal to True are truthy (true), and those equal to False are falsy (false). However, non-Boolean objects can be evaluated in Boolean context as well and determined to be true or false. It is denoted by the class bool.

3. Sequential :

- [List](https://www.w3schools.com/python/python_lists.asp) - Lists are just like the arrays, declared in other languages. Lists need not be homogeneous always which makes it the most powerful tool in Python.

      A.**List Methods :**
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

- [String](https://www.w3schools.com/python/python_strings.asp) - In Python, Strings are arrays of bytes representing Unicode characters. A string is a collection of one or more characters put in a single quote, double-quote or triple quote

      A.**String Methods :**
       s.lower(), s.upper() — returns the lowercase or uppercase version of the string
       s.strip() — returns a string with whitespace removed from the start and end
       s.isalpha()/s.isdigit()/s.isspace()… — tests if all the string chars are in the various character classes
       s.startswith(‘ai’), s.endswith(‘ai’) — tests if the string starts or ends with the given ai strin
       s.find(‘other’) — searches for the given other string (not a regular expression) within s, and returns the first index where it begins or -1 if not found
       s.replace(‘old’, ‘new’) — returns a string where all occurrences of ‘old’ have been replaced by ‘new’
      s.split(‘delim’) — returns a list of substrings separated by the given delimiter. The delimiter is not a regular expression, it’s just text. ‘aaa,bbb,ccc’.split(‘,’) -> [‘aaa’, ‘bbb’, ‘ccc’].
      As a convenient special case s.split() (with no arguments) splits on all whitespace chars.
      s.join(list) — opposite of split(), joins the elements in the given list together using the string as the delimiter.
      e.g. ‘—‘.join([‘aaa’, ‘bbb’, ‘ccc’]) -> aaa—bbb—ccc 

- [Tuple](https://www.w3schools.com/python/python_tuples.asp) - Tuple is an ordered collection of Python objects much like a list. The sequence of values stored in a tuple can be of any type, and they are indexed by integers.

   In python, deletion or Updation of a tuple is not   allowed.

This is because tuples are immutable, hence elements of a tuple cannot be changed once it has been assigned. Only new tuples can be reassigned to the same name.

4. Container : 

- [Set](https://www.w3schools.com/python/python_sets.asp) - Set is an unordered collection of data type that is iterable, mutable and has no duplicate elements.The major advantage of using a set, as opposed to a list, is that it has a highly optimized method for checking whether a specific element is contained in the set.

- [Dictionary](https://realpython.com/python-dicts/) - Dictionary in Python is an unordered collection of data values, used to store data values like a map.Unlike other Data Types that hold only single value as an element, Dictionary holds key:value pair.



---
**Chapter 3 :**

This chapter is segmented in three parts- 

|Seg1|Seg2|Seg3|
|---|---|---|
|[Decision Making](https://github.com/Sheikh-Nabil/week1_evaluation#Seg%201%20Decision%20Making)|[Working with loops](https://github.com/Sheikh-Nabil/week1_evaluation#Seg%202%20Working%20with%20loops)|Assignments

A little hints below - 

_Seg 1_
[Decision Making](https://techvidvan.com/tutorials/decision-making-in-python/)**:**

There comes a point in our life where we need to decide what steps should be taken and based on that we decide our next decisions. In programming, we often have this similar situation where we need to decide which block of code should be executed based on a condition.Decisions like these are required everywhere in programming and they decide the direction of flow of program execution. Python has the following decision-making statements:

1. if statement
2. else statement 
3. if-elif ladder
4. Nested Statements


![Nested Statements](https://media.geeksforgeeks.org/wp-content/uploads/20200326162237/nested-if1.jpg)


_Seg 2_
[Working with loops](https://www.openbookproject.net/books/bpp4awd/ch04.html) :


Computers are often used to automate repetitive tasks. Repeating identical or similar tasks without making errors is something that computers do well and people do poorly.

Repeated execution of a set of statements is called iteration. Python has two statements for iteration – the [for](https://www.w3schools.com/python/python_for_loops.asp) statement which we met last chapter, 

'''for loop example
    
    fruits = ["apple", "banana", "cherry"]
    for x in fruits:
        print(x)'''

and the [while](https://www.w3schools.com/python/python_while_loops.asp) statement.

'''while loop example

     i = 1
    while i < 6:
        print(i)
        i += 1

_Seg 3_
[Assignments](https://dsft.code-data-ai.com/python-workshops/) : 

First 15 problems were solved in this segments. By doing so we learned mostly about functions and how it workes for different values.  

A simple problem and solution looks like - 
- Write a method that takes an array of consecutive (increasing) letters as input and that returns the missing letter in the array.

  You will always get an valid array. And it will be always exactly one letter be missing. The length of the array will always be at least 2.
The array will always contain letters in only one case.

Solution - 
'''Python
        
        import string
        def find_missing_letter(s):
            alp_lower = list(string.ascii_lowercase)
            alp_upper = list(string.ascii_uppercase)
  
        s1 = ''.join(s)
  
        if s1.isupper():
            x = set(alp_upper[alp_upper.index(s[0]):alp_upper.index(s[-1])+1]) - set(s)
        return x.pop()
        else: 
            x = set(alp_lower[alp_lower.index(s[0]):alp_lower.index(s[-1]) + 1]) - set(s)
        return x.pop()'''


---

**Chapter 4 :**

This chapter we made the evalution of our 15 problems from the assignments. 

We started the next session working with [Functions](https://www.programiz.com/python-programming/function). Functions in python are blocks of code that allows us to re-use these codes again and again without writing the whole block of code again. 

''' A simple function can be written as

    def greet(name):
    
    print("Hello, " + name + ". Good morning!")

    greet('Paul')

We wrote [Scripts](https://linuxhint.com/python_scripts_beginners_guide/) of python for the first time.

This part was really fun, we coded a guessing game where a user has to guess a number and get the result in three chances where the right number will be random every time. The script looks like- 

'''Python
    
    import random
    right = random.randint(1,5)
    print(right)


    name = input('your name ') 
        for i in range(3):
            number = int(input('guess a number '))
    if number == right:
        print('you won')
        break
    else:
        if i < 2:
            print('try again')
    else:
        print('you lost')
'''


--- 

**Chapter 5 :**

Thats the end of week  one for a new beginning for Team Leopard. 



For further details please visit the following links

<!-- Please don't remove this: Grab your social icons from https://github.com/carlsednaoui/gitsocial -->

<!-- display the social media buttons in your README -->

[![alt text][1.1]][1]
[![alt text][2.1]][2]
[![alt text][3.1]][3]


<!-- links to social media icons -->
<!-- no need to change these -->

<!-- icons with padding -->

[1.1]: http://i.imgur.com/P3YfQoD.png (facebook icon with padding)
[2.1]: http://i.imgur.com/yCsTjba.png (google plus icon with padding)
[3.1]: http://i.imgur.com/0o48UoR.png (github icon with padding)

<!-- icons without padding -->

[1.2]: http://i.imgur.com/fep1WsG.png (facebook icon without padding)
[2.2]: http://i.imgur.com/VlgBKQ9.png (google plus icon without padding)
[3.2]: http://i.imgur.com/9I6NRUm.png (github icon without padding)


<!-- links to your social media accounts -->
<!-- update these accordingly -->

[1]: https://www.facebook.com/profile.php?id=100016413525215
[2]: https://myaccount.google.com/profile
[3]: https://github.com/Sheikh-Nabil

<!-- Please don't remove this: Grab your social icons from https://github.com/carlsednaoui/gitsocial -->
