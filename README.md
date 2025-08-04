- [<span class="toc-section-number">1</span> Fundamentals (Week 1)](#fundamentals-week-1)
  - [<span class="toc-section-number">1.1</span> Orientation](#orientation)
  - [<span class="toc-section-number">1.2</span> Jupyter commands](#jupyter-commands)
  - [<span class="toc-section-number">1.3</span> Variables and Assignment](#variables-and-assignment)
  - [<span class="toc-section-number">1.4</span> Data Types and Type Conversion](#data-types-and-type-conversion)
  - [<span class="toc-section-number">1.5</span> Built-in Functions and Help](#built-in-functions-and-help)
  - [<span class="toc-section-number">1.6</span> Libraries](#libraries)
  - [<span class="toc-section-number">1.7</span> Lists](#lists)
  - [<span class="toc-section-number">1.8</span> For Loops](#for-loops)
  - [<span class="toc-section-number">1.9</span> Strings and methods](#strings-and-methods)
  - [<span class="toc-section-number">1.10</span> Dictionaries](#dictionaries)
  - [<span class="toc-section-number">1.11</span> (Optional) Other containers](#optional-other-containers)
- [<span class="toc-section-number">2</span> Data manipulation with Pandas (Week 2)](#data-manipulation-with-pandas-week-2)
  - [<span class="toc-section-number">2.1</span> (Optional) Review collections](#optional-review-collections)
  - [<span class="toc-section-number">2.2</span> (Optional) Check Numpy and Pandas versions](#optional-check-numpy-and-pandas-versions)
  - [<span class="toc-section-number">2.3</span> A very brief introduction to NumPy](#a-very-brief-introduction-to-numpy)
  - [<span class="toc-section-number">2.4</span> A very brief introduction to Pandas](#a-very-brief-introduction-to-pandas)
  - [<span class="toc-section-number">2.5</span> (Optional) Where are we?](#optional-where-are-we)
  - [<span class="toc-section-number">2.6</span> Reading tabular data into data frames](#reading-tabular-data-into-data-frames)
  - [<span class="toc-section-number">2.7</span> Data frames are objects that can tell you about their contents](#data-frames-are-objects-that-can-tell-you-about-their-contents)
  - [<span class="toc-section-number">2.8</span> Subsetting Data](#subsetting-data)
  - [<span class="toc-section-number">2.9</span> Filtering (i.e. masking) data on contents](#filtering-i.e.-masking-data-on-contents)
  - [<span class="toc-section-number">2.10</span> Grouping](#grouping)
  - [<span class="toc-section-number">2.11</span> Write output](#write-output)
  - [<span class="toc-section-number">2.12</span> Working with missing data](#working-with-missing-data)
  - [<span class="toc-section-number">2.13</span> Working with multiple tables](#working-with-multiple-tables)
  - [<span class="toc-section-number">2.14</span> (Optional) Text processing in Pandas](#optional-text-processing-in-pandas)
  - [<span class="toc-section-number">2.15</span> (Optional) Adding rows to DataFrames](#optional-adding-rows-to-dataframes)
  - [<span class="toc-section-number">2.16</span> (Optional) Scientific Computing Libraries](#optional-scientific-computing-libraries)
  - [<span class="toc-section-number">2.17</span> (Optional) Things we didn't talk about](#optional-things-we-didnt-talk-about)
  - [<span class="toc-section-number">2.18</span> (Optional) Introspecting on the DataFrame object](#optional-introspecting-on-the-dataframe-object)
- [<span class="toc-section-number">3</span> Building Programs (Week 3)](#building-programs-week-3)
  - [<span class="toc-section-number">3.1</span> Looping Over Data Sets](#looping-over-data-sets)
  - [<span class="toc-section-number">3.2</span> Conditionals](#conditionals)
  - [<span class="toc-section-number">3.3</span> Writing Functions](#writing-functions)
  - [<span class="toc-section-number">3.4</span> Notebooks vs Python scripts](#notebooks-vs-python-scripts)
  - [<span class="toc-section-number">3.5</span> (Optional) Python from the terminal](#optional-python-from-the-terminal)
  - [<span class="toc-section-number">3.6</span> (Optional) Use pathlib to write code that works across operating systems](#optional-use-pathlib-to-write-code-that-works-across-operating-systems)
  - [<span class="toc-section-number">3.7</span> (Optional) Generic file handling](#optional-generic-file-handling)
  - [<span class="toc-section-number">3.8</span> (Optional) Text processing and data cleanup](#optional-text-processing-and-data-cleanup)
- [<span class="toc-section-number">4</span> Visualization with Matplotlib and Seaborn (Week 4)](#visualization-with-matplotlib-and-seaborn-week-4)
  - [<span class="toc-section-number">4.1</span> Orientation](#orientation-1)
  - [<span class="toc-section-number">4.2</span> Plotting with Matplotlib](#plotting-with-matplotlib)
  - [<span class="toc-section-number">4.3</span> Visualization Strategy](#visualization-strategy)
  - [<span class="toc-section-number">4.4</span> Fast visualization and theming with Seaborn](#fast-visualization-and-theming-with-seaborn)
  - [<span class="toc-section-number">4.5</span> (Optional) How Matplotlib works](#optional-how-matplotlib-works)
- [<span class="toc-section-number">5</span> Special Topics](#special-topics)
  - [<span class="toc-section-number">5.1</span> Environments](#environments)
  - [<span class="toc-section-number">5.2</span> Working with unstructured files](#working-with-unstructured-files)
  - [<span class="toc-section-number">5.3</span> Exception handling](#exception-handling)
  - [<span class="toc-section-number">5.4</span> Performance and profiling](#performance-and-profiling)
  - [<span class="toc-section-number">5.5</span> Reducing memory usage](#reducing-memory-usage)
  - [<span class="toc-section-number">5.6</span> Other optional topics](#other-optional-topics)
- [<span class="toc-section-number">6</span> Endnotes](#endnotes)
  - [<span class="toc-section-number">6.1</span> Credits](#credits)
  - [<span class="toc-section-number">6.2</span> References](#references)
  - [<span class="toc-section-number">6.3</span> Data Sources](#data-sources)

# Fundamentals (Week 1)

## Orientation

### What programming language should I use?

1.  Use the language that your friends use (so you can ask them for help)
2.  Use a language that has a community of practice for your desired use case (you can find documentation, bug reports, sample code, etc.)
3.  Use a language that is "best" by some technical definition

### Python is pretty good at lots of things

- "Glue" language intended to replace shell and Perl
- Concise, readable, good for rapid prototyping
- Access to linear algebra libraries in FORTRAN/C → user-friendly numeric computing
- General purpose, not just an academic language; we will spend more time on some of the general purpose aspects.

### Literate programming and notebooks

- Blend code, documentation, and visualization
- Good for trying things, demos
- Bad for massive or long-running processes
- You can export notebooks as .py files when they outgrow the notebook format

## Jupyter commands

### How to start Jupyter Lab

1.  Method 1

    1.  Open Anaconda Navigator
    2.  Run Jupyter Lab

2.  Method 2 Open Terminal (MacOS/Linux) or Anaconda Prompt (Windows)

    ``` bash
    cd Desktop/data
    jupyter lab
    ```

### Navigation

- Navigate to where you want to be before creating new notebook
- Rename your notebook to something informative
- Use drag-and-drop interface to move .ipynb file to new location

### Writing code

1.  Execute cell with CTRL-Enter

    ``` python
    3 + 7
    ```

2.  Execute cell and move to new cell with Shift-Enter

    ``` python
    # This is a comment
    print("hello")
    ```

3.  Cells can be formatted as Code or Markdown

4.  Many keyboard shortcuts are available; see <https://gist.github.com/discdiver/9e00618756d120a8c9fa344ac1c375ac>

5.  (Optional) Jupyter Lab understands (some) terminal commands

    ``` bash
    ls
    ```

6.  (Optional) Jupyter Lab (IPython, actually) has "magic" commands that start with `%` (line) or `%%` (cell)

    ``` python
    # Print current items in memory
    %dirs

    # Get environment variables
    %env

    # Cell magic: Run bash in a subprocess
    %%bash

    # Cell magic: Time cell execution
    %%time
    ```

    - The magic command must be in the **first line** of the cell (no comments)
    - Some commands are not available on Windows (e.g. `%%bash`)

## Variables and Assignment

### Use variables to store values

Variables are names for values.

``` python
first_name = 'Derek'
age = 42
```

### Rules for naming things

1.  Can only contain letters, digits, and underscore
2.  Cannot start with a digit
3.  Are case sensitive: `age`, `Age` and `AGE`

### Use `print()` to display values

``` python
print(first_name, 'is', age, 'years old')
```

- Functions are verbs
- Functions end in `()`
- Functions take arguments (i.e. they do stuff with the values that you give them)
- `print()` useful for tracking progress, debugging

### Jupyter Lab will always echo the last value in a cell

1.  Python will evaluate and echo the last item

    ``` python
    first_name
    age
    ```

2.  If you want to see multiple items, you should explicitly print them

    ``` python
    print(first_name)
    print(age)
    ```

### (Optional) Variables must be created before they are used

``` python
# Prints an informative error message; more about this later
print(last_name)
```

### Variables can be used in calculations

``` python
print(age)
age = age + 3
print(age)
```

### **Challenge:** Variables only change value when something is assigned to them

Order of operations matters!

``` python
first = 1
second = 5 * first
first = 2

# What will this print?
print('first:', first)
print('second:', second)
```

## Data Types and Type Conversion

### Every value has a type

Most data is text and numbers, but there are many other types.

1.  Integers: whole numbers (counting)
2.  Floats: real numbers (math)
3.  Strings: text
4.  Files
5.  Various collections (lists, sets, dictionaries, data frames, arrays)
6.  More abstract stuff (e.g., database connection)

### The type determine what operations you can perform with a given value

1.  Example 1: Subtraction makes sense for some kinds of data but not others

    ``` python
    print(5 - 3)
    print('hello' - 'h')
    ```

2.  Example 2: Some things have length and some don't Note that we can put functions inside other functions!

    ``` python
    print(len('hello'))
    print(len(5))
    ```

### Use the built-in function `type()` to find the type of a value

1.  Variables point to values

    ``` python
    print(type(53), type(age))
    ```

2.  There are many types

    ``` python
    print(type(3.12), type("hello"), type(True), type([]))
    ```

### (Optional) Python is strongly-typed.

1.  It will (mostly) refuse to convert things automatically. You can explicitly convert data to a different type.

2.  Can't do math with text

    ``` python
    1 + '2'
    ```

3.  If you have string data, you can explicitly convert it to numeric data…

    ``` python
    print(1 + float('2'))
    print(1 + int('2'))
    ```

4.  …and vice-versa

    ``` python
    text = str(3)

    print(text)
    print(type(text))
    ```

5.  The exception is mathematical operations with integers and floats.

    ``` python
    int_sum = 3 + 4
    mixed_sum = 3 + 4.0

    print(type(int_sum))
    print(type(mixed_sum))
    ```

6.  What's going on under the hood?

    1.  `int`, `float`, and `str` are types. More precisely, they are *classes*.
    2.  `int()`, `float()`, and `str()` are functions that create new *instances* of their respective classes. The argument to the creation function (e.g., `'2'`) is the raw material for creating the new instance.

7.  This can work for more complex data types as well, e.g. Pandas data frames and Numpy arrays.

### **Challenge**: Explain what each operator does

``` python
# Floor
print('5 // 3:', 5 // 3)

# Floating point
print('5 / 3:', 5 / 3)

# Modulus (remainder)
print('5 % 3:', 5 % 3)
```

## Built-in Functions and Help

### A function may take zero or more arguments

``` python
print('before')
print()
print('after')
```

### Functions can have optional arguments

``` python
# By default, we round to the nearest integer
round(3.712)
```

``` python
# You can optionally specify the number of significant digits
round(3.712, 1)
```

### Use the built-in function `help()` to get help for a function

1.  View the documentation for `round()`

    ``` python
    help(round)
    ```

    - 1 mandatory argument
    - 1 optional argument with a default value: `ndigits=None`

2.  You can proved arguments implicitly by order, or explicitly in any order

    ``` python
    # You can optionally specify the number of significant digits
    round(4.712823, ndigits=2)
    ```

3.  Getting more help

    - Python.org tutorial
    - Standard library reference (we will discuss libraries in the next section)
    - References section of this document
    - Stack Overflow

4.  Use comments to add documentation to your own programs

    ``` python
    # This line isn't executed by Python
    print("This cell has many comments")   # The rest of this line isn't executed either
    ```

### Every function returns something

1.  Collect the results of a function in a new variable. This is one of the ways we build complex programs.

    ``` python
    # You can optionally specify the number of significant digits
    rounded_num = round(4.712823, ndigits=2)
    print(rounded_num)
    ```

    ``` python
    result = len("hello")
    print(result)
    ```

2.  (Optional) Some function only have "side effects"; they return `None`

    ``` python
    result = print("hello")
    print(result)
    # print(type(result))
    ```

### (Optional) Functions will typically generalize in sensible ways

1.  `max()` and `min()` do the intuitively correct thing with numerical and text data

    ``` python
    print(max(1, 2, 3))
    print(min('a', 'A', '0'))       # sort order is 0-9, A-Z, a-z
    ```

2.  Mixed numbers and text aren't meaningfully comparable

    ``` python
    max(1, 'a')
    ```

### (Optional) Python produces informative error messages

1.  Python reports a syntax error when it can’t understand the source of a program

    ``` python
    name = 'Bob
    age = = 54
    print("Hello world"
    ```

2.  Python reports a runtime error when something goes wrong while a program is executing

### **(Optional) Beginner Challenge**: What happens when?

Explain in simple terms the order of operations in the following program: when does the addition happen, when does the subtraction happen, when is each function called, etc. Extra credit: What is the final value of radiance?

``` python
radiance = 1.0
radiance = max(2.1, 2.0 + min(radiance, 1.1 * radiance - 0.5))
```

## Libraries

### Most of the power of a programming language is in its libraries

<https://docs.python.org/3/library/index.html>

### A program must `import` a library module before using it

``` python
import math

print(math.pi)
print(math.cos(math.pi))
```

- Refer to things from the module as `module-name.thing-name`
- Python uses "." to mean "part of" or "belongs to".

### Use `help()` to learn about the contents of a library module

``` python
help(math)                      # user friendly
```

``` python
dir(math)                       # brief reminder, not user friendly
```

### (Optional) Import shortcuts

1.  Import specific items from a library module. You want to be careful with this. It's safer to keep the namespace.

    ``` python
    from math import cos, pi

    cos(pi)
    ```

2.  Create an alias for a library module when importing it

    ``` python
    import math as m

    print(m.cos(m.pi))
    ```

### Python has opinions about how to write your programs

``` python
import this
```

## Lists

Lists are the central data structure in Python; we will explain many things by making analogies to lists.

### A list stores many values in a single structure

``` python
fruits = ["apple", "banana", "cherry", "date", "elderberry", "fig"]
print(fruits)
print(len(fruits))
```

### Lists are indexed by position, counting from 0

``` python
# First item
print(fruits[0])

# Fifth item
print(fruits[4])
```

### You can get a subset of the list by slicing it

1.  You slice a list from the start position up to, but not including, the stop position

    ``` python
    print(fruits[0:3])
    print(fruits[2:5])
    ```

2.  You can omit the start position if you're starting at the beginning…

    ``` python
    # Two ways to get the first 5 items
    print(fruits[0:5])
    print(fruits[:5])
    ```

3.  …and you *must* omit the end position if you're going to the end (otherwise it's up to, but not including, the end!). This is useful if you don't know how long the list is:

    ``` python
    # Everything but the first 3 items
    print(fruits[3:])
    ```

4.  You can add an optional step interval (every 2nd item, every 3rd item, etc.)

    ``` python
    # First 5 items, every other item
    print(fruits[0:5:2])

    # Every third item
    print(fruits[::3])
    ```

### (Optional) Why are lists indexed from 0?

cf. <https://stackoverflow.com/a/11364711>

1.  Slice endpoints are compliments In both cases, the number you see represents what you want to do.

    ``` python
    # Get the first two items
    print(fruits[:2])

    # Get everything except the first two items
    print(fruits[2:])
    ```

2.  For non-negative indices, the length of a slice is the difference of the indices

    ``` python
    len(fruits[1:3]) == 2
    ```

### **Challenge**: Some other properties of indexes

Try these statements. What are they doing? Can you explain the differences in their behavior?

``` python
fruits[-1]
fruits[20]
fruits[-3:]
```

#### Solution

1.  You can count backwards from the end with negative integers
2.  Indexing beyond the end of the collection is an error

### Lists are mutable

1.  You can replace a value at a specific index location

    ``` python
    fruits[0] = "apricot"
    print(fruits)
    ```

2.  Add an item to list with `append()`. This is a *method* of the list (more on this later!).

    ``` python
    fruits.append("grape")
    print(fruits)
    ```

3.  Add the items from one list to another with `extend()`

    ``` python
    more_fruits = ["honeydew", "imbe", "jackfruit"]

    # Add all of the elements of more_fruits to fruits
    fruits.extend(more_fruits)
    print(fruits)
    ```

### (Optional) Many functions take collections as arguments

``` python
# Assessing the overall productivity of our wide receivers
receiving_yards = [450, 370, 870, 150]
mean_yards = sum(receiving_yards)/len(receiving_yards)
print(mean_yards)
```

### (Optional) Removing items from a list

1.  Use `del` to remove an item at an index location

    ``` python
    print(more_fruits)
    del more_fruits[1]
    print(more_fruits)
    ```

2.  Use `pop()` to remove the last item and assign it to a variable. This is useful for destructive iteration.

    ``` python
    f = fruits.pop()

    print('Last fruit in list:', f)
    print(fruits)
    ```

### Lists can contain anything

1.  You can put anything in a list

    ``` python
    ages = ['Derek', 42, 'Bill', 24, 'Susan', 37]
    ```

2.  (Optional) You *could* use this to manage complex data, but you shouldn't

    ``` python
    # Get first pair
    print(ages[0:2])

    # Get all the names
    print(ages[::2])

    # Get all the ages
    print(ages[1::2])
    ```

3.  You can put lists inside other lists

    ``` python
    ages.append(more_fruits)

    # List in our list
    print(ages)

    # The last item is a list
    print(ages[-1])

    # Get an item from that list
    print(ages[-1][0])
    ```

### **(Optional) Challenge**: Reversing a list

Create a new list that contains all of the items from `fruits` in the reverse order.

#### Solution

``` python
rev_fruits = fruits[len(fruits)-1::-1]
print(rev_fruits)
```

## For Loops

Usually you don't need to find list items by index. What you actually want to do is go through each item in the list and use it for something.

### A `for` loop executes commands once for each value in a collection

"For each thing in this group, do these operations"

``` python
for fruit in fruits:
    print(fruit)
```

- A for loop is made up of a collection, a loop variable, and a body
- The collection, **fruits**, is what the loop is being run on.
- The loop variable, **fruit**, is what changes for each iteration of the loop (i.e. the “current thing”)
- The body, **print(fruit)**, specifies what to do for each value in the collection.

### Whitespace is syntactically meaningful in Python!

``` python
for fruit in fruits:
print(fruit)
```

### Loop variables can be called anything

``` python
for bob in fruits:
    print(bob)
```

### The body of a loop can contain many statements

``` python
primes = [2, 3, 5]
for p in primes:
    squared = p ** 2
    cubed = p ** 3
    print(p, squared, cubed)
```

### Create a new collection from an existing collection

We will learn how to vectorize this when we get to Numpy and Pandas

``` python
prime_exponents = []
for p in primes:
   prime_exponents.append(p**2)

print(prime_exponents)
```

### **Challenge**: Accumulation

Get the total length of all the words in the `fruits` list.

#### Solution 1

``` python
total = 0
for f in fruits:
    total = total + len(f)

print(total)
```

#### Solution 2

``` python
lengths = []
for f in fruits:
    lengths.append(len(f))

print(sum(lengths))
```

#### Solution 3

``` python
sum(len(f) for f in fruits)
```

#### Solution 4

``` python
len("".join(fruits))
```

### (Optional) Helpful tools for iteration

1.  Use `range()` to iterate over a sequence of numbers

    ``` python
    for number in range(0, 3):
        print(number)
    ```

    - range() produces numbers on demand (a "generator" function)
    - useful for tracking progress

2.  Use `enumerate()` to iterate over a sequence of items and their positions

    ``` python
    for number, fruit in enumerate(fruits):
        print(number, ":", fruit)
    ```

3.  Use functional programming idioms

    - Comprehensions: generator, list, dictionary
    - itertools library

4.  Test to see if an object is iterable

    ``` python
    # Lists, dictionaries, and strings are iterable
    hasattr(location, "__iter__")

    #Integers are not iterable
    hasattr(5, "__iter__")
    ```

## Strings and methods

### Strings are (kind of) like lists

1.  Strings are indexed like lists

    ``` python
    # Use an index to get a single character from a string
    fruit = "gooseberry"
    print(fruit[0])
    print(fruit[0:3])
    ```

2.  Strings have length

    ``` python
    len(fruit)
    ```

### But! Strings are immutable

1.  Can't change a string in place

    ``` python
    fruit[0] = 'G'
    ```

2.  Solution: String methods create a new string

    ``` python
    fruit_title = fruit.capitalize()
    print(fruit_title)
    ```

### Use the built-in string methods to clean up data

``` python
bad_str1 = "  Hello world!   "
bad_str2 = "|...goodbye cruel world|"

good_str1 = bad_str1.strip()
good_str2 = bad_str2.strip("|")

print(good_str1, "\n", good_str2)
```

### (Optional) Methods are functions that belong to objects

1.  You can view an object's attributes (i.e. methods and fields) using `help()` or `dir()`. Some attributes are "private"; you're not supposed to use these directly.

    ``` python
    # More verbose help
    help(str)
    ```

    ``` python
    # The short, short version
    dir(my_string)
    ```

2.  An object packages data together with functions that operate on that data. This is a very common organizational strategy in Python.

    ``` python
    sentence = "Hello world!"

    # Call the swapcase method on the my_string object
    print(sentence.swapcase())
    ```

3.  You can chain methods into processing pipelines

    ``` python
    print(sentence.isupper())          # Check whether all letters are uppercase
    print(sentence.upper())            # Capitalize all the letters
    ```

    ``` python
    # The output of upper() is as string; you can use more string methods on it
    sentence.upper().isupper()
    ```

### **Challenge**: Putting it all together

You want to iterate through the `fruits` list in a random order. For each randomly-selected fruit, capitalize the fruit and print it.

1.  Which standard library module could help you? <https://docs.python.org/3/library/>
2.  Which function would you select from that module? Are there alternatives?
3.  Try to write a program that uses the function.

#### Solution 1 (shuffle)

``` python
import random

random.shuffle(fruits)

for f in fruits:
    print(f.title())
```

#### Solution 2 (sample)

``` python
random_fruits = random.sample(fruits, len(fruits))

for f in random_fruits:
    print(f.title())
```

### **(Optional) Beginner Challenge**: From Strings to Lists and Back

1.  Given this Python code…

    ``` python
    print('string to list:', list('tin'))
    print('list to string:', ''.join(['g', 'o', 'l', 'd']))
    ```

2.  What does `list('some string')` do?

3.  What does `'-'.join(['x', 'y', 'z'])` generate?

## Dictionaries

### Dictionaries are sets of key/value pairs. Instead of being indexed by position, they are indexed by key.

``` python
ages = {'Derek': 42,
        'Bill': 24,
        'Susan': 37}

ages["Derek"]
```

### Update dictionaries by assigning a key/value pair

1.  Update a pre-existing key with a new value

    ``` python
    ages["Derek"] = 44

    print(ages)
    ```

2.  Add a new key/value pair

    ``` python
    ages["Beth"] = 19
    print(ages)
    ```

### Check whether the dictionary contains an item

1.  Does a key already exist?

    ``` python
    "Derek" in ages
    ```

2.  (Optional) Does a value already exist (you generally don't want to do this; keys are unique but values are not)?

    ``` python
    24 in ages.values()
    ```

### (Optional) Delete an item using `del` or `pop()`

``` python
print("Original dictionary", ages)
del ages["Derek"]
print("1st deletion", ages)

susan_age = ages.pop("Susan")
print("2nd deletion", ages)
print("Returned value", susan_age)
```

### Dictionaries are the natural way to store tree-structured data

As with lists, you can put anything in a dictionary.

``` python
location = {'latitude': [37.28306, 'N'],
            'longitude': [-120.50778, 'W']}

print(location['longitude'][0])
```

### Dictionary iteration

1.  Iterate over key: value pairs

    ``` python
    for key, val in ages.items():
        print(key, ":", val)
    ```

2.  (Optional) You can iterate over keys and values separately

    ``` python
    # Iterate over keys; you can also explicitly call .keys()
    for key in ages:
        print(key)

    # Iterate over values
    for val in ages.values():
        print(val)
    ```

3.  (Optional) Iteration can be useful for unpacking complex dictionaries

    ``` python
    for key, val in location.items():
        print(key, 'is', val[0], val[1])
    ```

### **Challenge: Generate a dictionary**

1.  You have the following key/value pairs:

    ``` python
    'Derek' 42
    'Bill' 24
    'Susan' 37
    ```

2.  Create a dictionary that contains all of them. You may find the following useful:

    ``` python
    help(dict)
    help(zip)
    ```

#### Solution 1 of many

``` python
names = ["Derek", "Bill", "Susan"]
ages = [42, 24, 37]

ages_dict = dict(zip(names, ages))
```

### **(Optional) Advanced Challenge**: Convert a list to a dictionary

How can you convert our list of names and ages into a dictionary? Hint: You will need to populate the dictionary with a list of keys and a list of values.

``` python
# Starting data
ages = ['Derek', 42, 'Bill', 24, 'Susan', 37]

# Get dictionary help
help({})
```

#### Solution

``` python
ages_dict = dict(zip(ages[::2], ages[1::2]))
```

## (Optional) Other containers

1.  Tuples
2.  Sets

# Data manipulation with Pandas (Week 2)

## (Optional) Review collections

### Lists and dictionaries

1.  Reference item by index/key
2.  Insert item by index/key
3.  Indices/keys must be unique

### Strings

1.  Similar to lists: Reference item by index, have length
2.  Immutable, so need to use string **methods**
3.  `'/'.join()` is a very useful method

## (Optional) Check Numpy and Pandas versions

``` python
import numpy
import pandas
from importlib.metadata import version
print(version("pandas"))
print(version("numpy"))
```

## A very brief introduction to NumPy

### NumPy arrays

Introductory documentation: <https://numpy.org/doc/stable/user/quickstart.html>

1.  NumPy is the linear algebra library for Python

    ``` python
    import numpy as np

    # Create an array of random numbers
    m_rand = np.random.rand(3, 4)
    print(m_rand)
    ```

2.  Arrays are indexed like lists

    ``` python
    print(m_rand[0,0])
    ```

3.  Arrays have attributes

    ``` python
    print(m_rand.shape)
    print(m_rand.size)
    print(m_rand.ndim)
    print(m_rand.T)
    ```

4.  Arrays are fast but inflexible - the entire array must be of a single type.

### Linear algebra with NumPy

Don't use `for` loops with DataFrames or Numpy matrices. There is almost always a faster vectorized function that does what you want.

``` python
x = np.arange(9)
y = np.arange(9)

print(x)
print(y)
```

1.  Operations are element-wise by default

    ``` python
    print(x * y)
    ```

2.  Matrix-wise operations (e.g. dot product) use NumPy functions

    ``` python
    # Use a special operator if it exists
    print(x @ y)

    # Otherwise, use a numpy function
    print(np.dot(x, y))
    ```

3.  You can rearrange the same array into different configurations

    ``` python
    # Use method chaining to link actions together
    x1 = x.reshape(3,3)
    x2 = x.reshape(9,1)

    print(x1)
    print(x2)
    ```

4.  (Optional) Matlab gotcha: 1-D arrays have no transpose

    ``` python
    print(x)
    print(x.T)
    print(x.reshape(-1,1))
    ```

### **Challenge**: Matrix operations

1.  Create a 3x3 matrix containing the numbers 0-8. Hint: Consult the NumPy Quickstart documentation here: <https://numpy.org/doc/stable/user/quickstart.html>
2.  Multiply the matrix by itself (element-wise).
3.  Multiply the matrix by its transpose.
4.  Divide the matrix by itself. What happens?

#### Solutions

``` python
# Use method chaining to link actions together
x = np.arange(9).reshape(3,3)

print(x * x)
print(x * x.T)
print(x / x)
```

## A very brief introduction to Pandas

1.  Pandas is a library for working with spreadsheet-like data ("DataFrames")
2.  A DataFrame is a collection (dict) of Series columns
3.  Each Series is a 1-dimensional NumPy array with optional row labels (dict-like, similar to R vectors)
4.  Therefore, each series inherits many of the abilities (linear algebra) and limitations (single data type) of NumPy

## (Optional) Where are we?

### Python provides functions for working with the file system.

``` python
import os

# print current directory
print("Current working directory:", os.getcwd())
# print all of the files and directories
print("Working directory contents:", os.listdir())
```

### These provide a rich Python alternative to shell functions

``` python
# Get 1 level of subdirectories
print("Just print the sub-directories:", sorted(next(os.walk('.'))[1]))

# Move down one directory
os.chdir("data")
print(os.getcwd())

# Move up one directory
os.chdir("..")
print(os.getcwd())
```

## Reading tabular data into data frames

### Import tabular data using the Pandas library

``` python
import pandas as pd

data = pd.read_csv('data/gapminder_gdp_oceania.csv')
print(data)
```

``` python
# Jupyter Lab will give you nice formatting if you echo
data
```

- File and directory names are strings
- You can use relative or absolute file paths

### Use `index_col` to use a column’s values as row indices

Rows are indexed by number by default (0, 1, 2,….). For convenience, we want to index by country:

``` python
data = pd.read_csv('data/gapminder_gdp_oceania.csv', index_col='country')
print(data)
```

- By default, rows are indexed by position, like lists.
- Setting the `index_col` parameter lets us index rows by label, like dictionaries. For this to work, the index column needs to have unique values for every row.
- You can verify the contents of the CSV by double-clicking on the file in Jupyter Lab

### Pandas help files are dense; you should prefer the online documentation

1.  Main documentation link: <https://pandas.pydata.org/docs/user_guide/index.html>
2.  Pandas can read many different data formats: <https://pandas.pydata.org/docs/user_guide/io.html>

## Data frames are objects that can tell you about their contents

### Data frames have methods (i.e. functions) that perform operations using the data frame's contents as input

1.  Use `.info()` to find out more about a data frame

    ``` python
    data.info()
    ```

2.  Use `.describe()` to get summary statistics about data

    ``` python
    data.describe()
    ```

3.  (Optional) Look at the first few rows

    ``` python
    data.head(1)
    ```

### Data frames have fields (i.e. variables) that hold additional information

A "field" is a variable that belongs to an object.

1.  The `.index` field stores the row Index (list of row labels)

    ``` python
    print(data.index)
    ```

2.  The `.columns` field stores the column Index (list of column labels)

    ``` python
    print(data.columns)
    ```

3.  The `.shape` variable stores the matrix shape

    ``` python
    print(data.shape)
    ```

4.  Use `DataFrame.T` to transpose a DataFrame. This doesn't copy or modify the data, it just changes the caller's view of it.

    ``` python
    print(data.T)
    print(data.T.shape)
    ```

### (Optional) Pandas introduces some new types

``` python
# DataFrame type
type(data)
type(data.T)

# Series type
type(data['gdpPercap_1952'])

# Index type
type(data.columns)
```

- You can convert data between NumPy arrays, Series, and DataFrames
- You can read data into any of the data structures from files or from standard Python containers

## Subsetting Data

### Treat the data frame as a matrix and select values by position

Use `DataFrame.iloc[..., ...]` to select values by their (entry) position. The `i` in `iloc` stands for "index".

``` python
#import pandas as pd
data = pd.read_csv('data/gapminder_gdp_europe.csv', index_col='country')

data.iloc[0,0]
```

### Treat the data frame as a table and select values by label

This is most common way to get data

1.  Use `DataFrame.loc[..., ...]` to select values by their label

    ``` python
    # This returns a value
    data.loc["Albania", "gdpPercap_1952"]
    ```

### Shorten the column names using vectorized string methods

1.  (Optional review) Standard Python has string methods

    ``` python
    big_hello = "hello".title()
    print(big_hello)

    help("hello".title)
    print(dir("hello"))
    ```

2.  Pandas data frames are complex objects

    ``` python
    print(data.columns)
    print(dir(data.columns.str))
    ```

3.  Use built-in methods to transform the entire data frame

    ``` python
    # The columns index can update all of its values in a single operation
    data.columns = data.columns.str.strip("gdpPercap_")
    print(data.columns)
    ```

### Use list slicing notation to get subsets of the data frame

1.  Select multiple columns or rows using `.loc` and a named slice. This generalizes the concept of a slice to include labeled indexes.

    ``` python
    # This returns a DataFrame
    data.loc['Italy':'Poland', '1962':'1972']
    ```

2.  Use `:` on its own to mean all columns or all rows. This is Python’s usual slicing notation, which allows you to treat data frames as multi-dimensional lists.

    ``` python
    # This returns a DataFrame
    data.loc['Italy':'Poland', :]
    ```

3.  If you want specific rows or columns, pass in a list

    ``` python
    data.loc[['Italy','Poland'], :]
    ```

4.  (Optional) `.iloc` follows list index conventions ("up to, but not including)", but `.loc` does the intuitive right thing ("A through B")

    ``` python
    index_subset = data.iloc[0:2, 0:2]
    label_subset = data.loc["Albania":"Belgium", "1952":"1962"]

    print(index_subset)
    print(label_subset)
    ```

5.  Result of slicing can be used in further operations

    ``` python
    subset = data.loc['Italy':'Poland', '1962':'1972']

    print(subset.describe())
    print(subset.max())
    ```

6.  (Optional) Insert new values using `.at` (for label indexing) or `.iat` (for numerical indexing)

    ``` python
    subset.at["Italy", "1962"] = 2000
    print(subset)
    ```

### **Challenge**: Collection types

1.  Calculate `subset.max()` and assign the result to a variable. What kind of thing is it? What are its properties?
2.  What is the maximum value of the new variable? Can you determine this without creating an intermediate variable?

#### Solution

1.  Pandas always drills down to the most parsimonious representation. On one hand, this is convenient; on the other, it violates the Pythonic expectation for strong types.

    | Shape of data selection | Pandas return type |
    |-------------------------|--------------------|
    | 2D                      | DataFrame          |
    | 1D                      | Series             |
    | 0D                      | single value       |

2.  Use method chaining

    ``` python
    print(subset.max().max())

    # Alternatively
    print(subset.max(axis=None))
    ```

### (Optional) Filter on label properties

1.  `.filter()` always returns the same type as the original item, whereas `.loc` and `.iloc` might return a data frame or a series.

    ``` python
    italy = data.filter(items=["Italy"], axis="index")
    print(italy)
    print(type(italy))
    ```

2.  `.filter()` is a general-purpose, flexible method

    ``` python
    help(data.filter)
    data.filter(like="200", axis="columns")
    data.filter(like="200", axis="columns").filter(items=["Italy"], axis="index")
    ```

## Filtering (i.e. masking) data on contents

### Use comparisons to select data based on value

1.  Show which data frame elements match a criterion.

    ``` python
    # Which GDPs are greater than 10,000?
    subset > 10000
    ```

2.  Use the criterion match to filter the data frame's contents. This uses index notation:

    ``` python
    df = subset[subset > 10000]
    print(df)
    ```

    1.  `subset > 10000` returns a data frame of True/False values
    2.  `subset[subset > 10000]` filters its contents based on that True/False data frame. All `True` values are returned, element-wise.
    3.  This section is more properly called "Masking Data," because it involves operations for overlaying a data frame's values without changing the data frame's shape. We don't drop anything from the data frame, we just replace it with `NaN`.

3.  (Optional) Use `.where()` method to find elements that match the criterion:

    ``` python
    df = subset.where(subset > 10000)
    print(df)
    ```

### You can filter using any method that returns a data frame

For example, get the GDP for all countries greater than the median.

``` python
# Get the overall median
subset.median()          # Returns Series
subset.median(axis=None) # Returns single value

# Which data points are above the median
subset > subset.median(axis=None)

# Return the masked data set
subset[subset > subset.median(axis=None)]
```

### **Challenge**: Ranking countries

1.  Get the mean GDP per capita for each country in `subset` (Hint: consult the Pandas documentation to figure out how to get the mean of the rows).
2.  Extra credit: Sort the countries by their mean GDP per capita.
3.  Extra credit 2x: Assign a numerical rank to each country based on its GDP per capita

#### Solution

``` python
# Get the means
subset.mean(axis=1)

# Sort the means. We are illustrating method chaining.
subset.mean(axis=1).sort_values()

# Sort in descending and ranky
subset.mean(axis=1).sort_values(ascending=False).rank()
```

## Grouping

### Motivating example: Group countries by GDP

``` python
# Calculate mean GDP per cap for each country
mean_gdp = data.mean(axis=1)

# Calculate the median score
median_score = mean_gdp.median()

# Classify countries as high or low GDP
high_gdp = mean_gdp > median_score

print(mean_gdp)
print(high_gdp)
```

### Append new columns to the data frame containing our summary statistics

Data frames are dictionaries of Series:

``` python
data["mean_gdp"] = mean_gdp
data["wealthy"] = high_gdp
```

### Sort and group by new columns

1.  Group data by category and get group stats

    ``` python
    # Get descriptive statistics for the group
    data.groupby("wealthy").mean()
    data.groupby("wealthy").describe()
    ```

2.  (Optional) Sort data by new column

    ``` python
    data.sort_values(by="mean_gdp")
    ```

## Write output

Capture the results of your filter in a new file, rather than overwriting your original data.

1.  Create a new subdirectory called "processed" using the editor's file interface.

2.  Save your data as a CSV in the subdirectory

    ``` python
    # Save to a new CSV, preserving your original data
    data.to_csv('gapminder_gdp_europe_grouped.csv')

    # If you don't want to preserve row names:
    data.to_csv('gapminder_gdp_europe_grouped.csv', index=False)
    ```

## Working with missing data

### By default, most numerical operations ignore missing data

Examples include min, max, mean, std, etc.

1.  Missing values ignored by default

    ``` python
    print("Column means")
    print(df.mean())

    print("Row means")
    print(df.mean(axis=1))
    ```

2.  Force inclusions with the `skipna` argument

    ``` python
    print("Column means")
    print(df.mean(skipna=False))

    print("Row means")
    print(df.mean(axis=1, skipna=False))
    ```

### Check for missing values

1.  Show which items are missing. "NA" includes `NaN` and `None`. It doesn't include empty strings or `numpy.inf`.

    ``` python
    # Show which items are NA
    df.isna()
    ```

2.  Count missing values

    ``` python
    # Missing by row
    print(df.isna().sum())

    # Missing by column
    print(df.isna().sum(axis=1))

    # Aggregate sum
    df.isna().sum().sum()
    ```

3.  Are any values missing?

    ``` python
    df.isna().any(axis=None)
    ```

4.  (Optional) Are all of the values missing?

    ``` python
    df.isna().all(axis=None)
    ```

### Drop missing values

Drop all rows with missing values

``` python
df_drop = df.dropna()
```

### (Optional) Replace missing values

1.  Replace with a fixed value

    ``` python
    df_fixed = df.fillna(99)
    print(df_fixed)
    ```

2.  Replace specific values with `replace()`

3.  Replace values that don't meet a criterion with an alternate value

    ``` python
    subset_fixed = subset.where(subset > 10000, 99)
    print(subset_fixed)
    ```

4.  Impute missing values. Read the docs, this may or may not be sufficient for your needs.

    ``` python
    df_imputed = df.interpolate()
    ```

5.  Recode specific values as missing when importing data (e.g., using `read_csv()`) by passing in the \`na_values\` parameter.

### **(Optional) Challenge**: Filter and trim with a boolean vector

A DataFrame is a dictionary of Series columns. With this in mind, experiment with the following code and try to explain what each line is doing. What operation is it performing, and what is being returned?

Feel free to use `print()`, `help()`, `type()`, etc as you investigate.

``` python
df["1962"]
df["1962"].notna()
df[df["1962"].notna()]
```

#### Solution

1.  Line 1 returns the column as a Series vector
2.  Line 2 returns a boolean Series vector (True/False)
3.  Line 3 performs *boolean indexing* on the DataFrame using the Series vector. It only returns the rows that are True (i.e. it performs true filtering).

## Working with multiple tables

### Concatenating data frames

``` python
surveys = pd.read_csv('data/surveys.csv', index_col="record_id")
print(surveys.shape)
```

``` python
df1 = surveys.head(10)
df2 = surveys.tail(10)

df3 = pd.concat([df1, df2])
print(df3.shape)
```

### (Optional) Joining data frames (in an SQL-like manner)

1.  Import species data

    ``` python
    species = pd.read_csv('data/species.csv', index_col="species_id")
    print(species.shape)
    ```

2.  Join tables on common column. The "left" join is a strategy for augmenting the first table (surveys) with information from the second table (species).

    ``` python
    df_join = surveys.merge(species, on="species_id", how="left")
    print(df_join.shape)
    print(df_join.head())
    ```

3.  The resulting table loses its index because `surveys.record_id` is not being used in the join. To keep `record_id` as the index for the final table, we need to retain it as an explicit column.

    ``` python
    # Don't set record_id as index during initial import
    surveys = pd.read_csv('data/surveys.csv')
    df_join = surveys.merge(species, on="species_id", how="left").set_index("record_id")

    df_join.head()
    ```

4.  Get the subset of species that match a criterion, and join on that subset. The "inner" join only includes rows where both tables match on the key column; it's a strategy for filtering the first table by the second table.

    ``` python
    # Get the taxa column, masking the rows based on which values match "Bird"
    birds = species[species["taxa"] == "Bird"]

    df_inner = surveys.merge(birds, on="species_id", how="inner").set_index("record_id")

    print("Inner join")
    print(df_inner.shape)
    print(df_inner.head())
    ```

5.  Compare with the results of the left join

    ``` python
    df_surveys_left = surveys.merge(birds, on="species_id", how="left").set_index("record_id")

    print("Surveys left join")
    print(df_surveys_left.shape)
    print(df_surveys_left.head())
    ```

## (Optional) Text processing in Pandas

cf. <https://pandas.pydata.org/docs/user_guide/text.html>

1.  Import tabular data that contains strings

    ``` python
    species = pd.read_csv('data/species.csv', index_col='species_id')

    # You can explicitly set all of the columns to type string
    # species = pd.read_csv('data/species.csv', index_col='species_id', dtype='string')

    # ...or specify the type of individual columns
    # species = pd.read_csv('data/species.csv', index_col='species_id',
    #                       dtype = {"genus": "string",
    #                                "species": "string",
    #                                "taxa": "string"})

    print(species.head())
    print(species.info())
    print(species.describe())
    ```

2.  A Pandas Series has string methods that operate on the entire Series at once

    ``` python
    # Two ways of getting an individual column
    print(type(species.genus))
    print(type(species["genus"]))

    # Inspect the available string methods
    print(dir(species["genus"].str))
    ```

3.  Use string methods for filtering

    ``` python
    # Which species are in the taxa "Bird"?
    print(species["taxa"].str.startswith("Bird"))

    # Filter the dataset to only look at Birds
    print(species[species["taxa"].str.startswith("Bird")])
    ```

4.  Use string methods to transform and combine data

    ``` python
    binomial_name = species["genus"].str.cat(species["species"].str.title(), " ")
    species["binomial"] = binomial_name

    print(species.head())
    ```

## (Optional) Adding rows to DataFrames

A row is a view onto the *nth* item of each of the column Series. Appending rows is a performance bottleneck because it requires a separate append operation for each Series. You should concatenate data frames instead.

1.  Create a single row as a data frame and concatenate it.

    ``` python
    row = pd.DataFrame({"1962": 5000, "1967": 5000, "1972": 5000}, index=["Latveria"])
    pd.concat([subset, row])
    ```

2.  If you have individual rows as Series, `pd.concat()` will produce a data frame.

    ``` python
    # Get each row as a Series
    italy = data.loc["Italy", :]
    poland = data.loc["Poland", :]

    # Omitting axis argument (or axis=0) concatenates the 2 series end-to-end
    # axis=1 creates a 2D data frame
    # Transpose recovers original orientation
    # Column labels come from Series index
    # Row labels come from Series name
    pd.concat([italy, poland], axis=1).T
    ```

## (Optional) Scientific Computing Libraries

### Libraries

1.  SciPy projects
    1.  Numpy: Linear algebra
    2.  Pandas
    3.  Scipy.stats: Probability distributions and basic tests
2.  Statsmodels: Statistical models and formulae built on Scipy.stats
3.  Scikit-Learn: Machine learning tools built on NumPy
4.  Tensorflow/PyTorch: Deep learning and other voodoo

### The basics of Scikit-Learn

Scikit-Learn documentation: <https://scikit-learn.org/stable/>

1.  Motivating example: Ordinary least squares regression

    ``` python
    from sklearn import linear_model

    # Create some random data
    x_train = np.random.rand(20)
    y = np.random.rand(20)

    # Fit a linear model
    reg = linear_model.LinearRegression()
    reg.fit(x_train.reshape(-1,1), y)
    print("Regression slope:", reg.coef_)
    ```

2.  Estimate model fit

    ``` python
    from sklearn.metrics import r2_score

    # Test model fit with new data
    x_test = np.random.rand(20)
    y_prediction = reg.predict(x_test.reshape(-1,1))

    # Get model stats
    mse = mean_squared_error(y, y_prediction)
    r2 = r2_score(y, y_prediction)

    print("R squared:", "{:.3f}".format(r2))
    ```

3.  (Optional) Inspect our prediction

    ``` python
    import matplotlib.pyplot as plt

    fig, ax = plt.subplots()
    ax.scatter(x_train, y, color="black")
    ax.plot(x_test, y_prediction, color="blue")

    # `fig` in Jupyter Lab
    fig.show()
    ```

4.  (Optional) Compare with Statsmodels

    ``` python
    # Load modules and data
    import statsmodels.api as sm

    # Fit and summarize OLS model (center data to get accurate model fit
    mod = sm.OLS(y - y.mean(), x_train - x_train.mean())
    res = mod.fit()

    print(res.summary())
    ```

### (Optional) Statsmodels regression example with applied data

1.  Import data

    ``` python
    data = pd.read_csv('surveys.csv')

    # Check for NaN
    print("Valid weights:", data['weight'].count())
    print("NaN weights:", data['weight'].isna().sum())
    print("Valid lengths:", data['hindfoot_length'].count())
    print("NaN lengths:", data['hindfoot_length'].isna().sum())
    ```

2.  Fit OLS regression model

    ``` python
    from statsmodels.formula.api import ols

    model = ols("weight ~ hindfoot_length", data, missing='drop').fit()
    print(model.summary())
    ```

3.  Generic parameters for all models

    ``` python
    import statsmodels

    help(statsmodels.base.model.Model)
    ```

## (Optional) Things we didn't talk about

1.  pipe
2.  map/applymap/apply (in general you should prefer vectorized functions)

## (Optional) Introspecting on the DataFrame object

1.  DataFrames have a huge number of fields and methods, so dir() is not very useful

    ``` python
    print(dir(data))
    ```

2.  Create a new list that filters out internal attributes

    ``` python
    df_joinpublic = [item for item in dir(data) if not item.startswith('_')]
    print(df_public)
    ```

3.  (Optional) Pretty-print the new list

    ``` python
    importort pprint

    pp = pprint.PrettyPrinter(width=100, compact=True, indent=2)
    pp.pprint(df_public)
    ```

4.  Objects have fields (i.e. data/variables) and methods (i.e. functions/procedures). The difference between a method and a function is that methods are attached to objects, whereas functions are free-floating ("first-class citizens"). Methods and functions are "callable":

    ``` python
    # GeneratorExitenerate a list of public methods and a list of public fields. We do this
    # by testing each attribute to determine whether it is "callable".
    # NB: Because Python allows you to override any attribute at runtime,
    # testing with `callable` is not always reliable.

    # List of methods (callable attributes)
    df_methods = [item for item in dir(data) if not item.startswith('_')
                  and callable(getattr(data, item))]
    # List of fields (non-callable attributes)
    df_attr = [item for item in dir(data) if not item.startswith('_')
               and not callable(getattr(data, item))]

    pp.pprint(df_methods)
    pp.pprint(df_attr)
    ```

# Building Programs (Week 3)

## Looping Over Data Sets

### File paths as an example of increasing abstraction in program development

1.  File paths as literal strings
2.  File paths as string patterns
3.  File paths as abstract Path objects

### Use a `for` loop to process files given a list of their names

``` python
import pandas as pd

file_list = ['data/gapminder_gdp_africa.csv', 'data/gapminder_gdp_asia.csv']
for filename in file_list:
    data = pd.read_csv(filename, index_col='country')
    print(filename)
    print(data.head(1))
```

### Use glob.glob to find sets of files whose names match a pattern

1.  Get a list of all the CSV files

    ``` python
    import glob
    glob.glob('data/*.csv')
    ```

2.  In Unix, the term “globbing” means “matching a set of files with a pattern”. It uses shell expansion rules, **not** regular expressions, so there's an upper limit to how flexible it can be. The most common patterns are:

    - \`\*\` meaning “match zero or more characters”
    - \`?\` meaning “match exactly one character”

3.  (Optional) Get a list of all CSV or TSV files

    ``` python
    glob.glob('data/*.?sv')
    ```

4.  Get a list of all the Gapminder CSV files

    ``` python
    glob.glob('data/gapminder_gdp_*.csv')
    ```

5.  (Optional) Exclude the "all" CSV file

    ``` python
    glob.glob('data/gapminder_[!all]*.csv')
    ```

### Use glob and a `for` loop to process batches of files

``` python
data_frames = []
for filename in glob.glob('data/gapminder_gdp_*.csv'):
    print(filename)
    data = pd.read_csv(filename)
    data_frames.append(data)

# Concatenate all columns, adding missing data for columns that aren't shared
all_data = pd.concat(data_frames)
print(all_data.shape)
print(all_data.columns)

# Concatenate only matching columns
common_data = pd.concat(data_frames, join="inner")
print(common_data.shape)
print(common_data.columns)
```

## Conditionals

### Evaluating the truth of a statement

1.  Value of a variable

    ``` python
    mass = 3

    print(mass == 3)
    print(mass > 5)
    print(mass < 4)
    ```

2.  Does a file end in `"long.csv"`?

    ``` python
    for filename in glob.glob('data/gapminder*.csv'):
       print("Current file:", filename)
       print(filename.endswith("long.csv")
    ```

3.  Membership in a collection

    ``` python
    primes = [2, 3, 5]

    print(2 in primes)
    print(7 in primes)
    ```

4.  Missing values

    ``` python
    surveys = pd.read_csv('data/surveys.csv', index_col="record_id")

    # Are any values missing?
    surveys.isna().any(axis=None)

    # Investigate missing values
    surveys.isna().sum()
    ```

5.  (Optional) Truth of a collection Note that `any()` and `all()` evaluate each item using `.__bool__()` or `.__len()__`, which tells you whether an item is "truthy" or "falsey" (i.e. interpreted as being true or false).

    ``` python
    my_list = [2.75, "green", 0]

    print(any(my_list))
    print(all(my_list))
    ```

6.  (Optional) Understanding "truthy" and "falsey" values in Python (cf. <https://stackoverflow.com/a/53198991>) Every value in Python, regardless of type, is interpreted as being `True` except for the following values (which are interpreted as `False`). "Truthy" values satisfy `if` or `while` statements; "Falsey" values do not.

    1.  Constants defined to be false: `None` and `False`.
    2.  Zero of any numeric type: `0`, `0.0`, `0j`, `Decimal(0)`, `Fraction(0, 1)`
    3.  Empty sequences and collections: `''`, `()`, `[]`, `{}`, `set()`, `range(0)`

### Use `if` statements to control whether or not a block of code is executed

1.  An `if` statement (more properly called a conditional statement) controls whether some block of code is executed or not.

    ``` python
    mass = 3.5
    if mass > 3.0:
        print(mass, 'is large')
    ```

    ``` python
    mass = 2.0
    if mass > 3.0:
        print (mass, 'is large')
    ```

2.  Structure is similar to a `for` statement:

    - First line opens with `if` and ends with a colon
    - Body containing one or more statements is indented (usually by 4 spaces)

3.  Use conditionals to decide which files to process

    ``` python
    for filename in glob.glob('data/gapminder*.csv'):
        if not filename.endswith("long.csv"):
            print("Passes test:", filename)
    ```

### Use else to execute a block of code when an if condition is not true

1.  `else` can be used following an `if`. This allows us to specify an alternative to execute when the if branch isn’t taken.

    ``` python
    if m > 3.0:
        print(m, 'is large')
    else:
        print(m, 'is small')
    ```

2.  This lets you explicitly handle the base case

    ``` python
    for filename in glob.glob('data/gapminder*.csv'):
        if filename.endswith("long.csv"):
            print("I don't want any of that")
        else:
            print("Passes test:", filename)
    ```

3.  Expand your reach with compound relations (and, or)

    ``` python
    for filename in glob.glob('data/gapminder*.csv'):
        if filename.endswith("long.csv") or filename.endswith("wide.csv"):
            print("I don't want any of that")
        else:
            print("Passes test:", filename)
    ```

### **Challenge:** Checking for missing data

Iterate through all of the CSV files in the data directory. Determine whether the data set has missing data. If it has missing data, print the file name and the missing data counts for each variable.

#### Solution

``` python
for filename in glob.glob('data/*.csv'):
    df = pd.read_csv(filename)

    if df.isna().any(axis=None):
        print(filename)
        print(df.isna().sum())
```

### Use `elif` to specify additional tests

May want to provide several alternative choices, each with its own test; use `elif` (short for “else if”) and a condition to specify these.

``` python
if m > 9.0:
    print(m, 'is huge')
elif m > 3.0:
    print(m, 'is large')
else:
    print(m, 'is small')
```

- Always associated with an `if`.
- Must come before the `else` (which is the “catch all”).

### **(Optional) Challenge:** Conditions are tested once, in order

What does this code do? Is it correct? Why or why not?

``` python
grade = 85
if grade >= 70:
    print('grade is C')
elif grade >= 80:
    print('grade is B')
elif grade >= 90:
    print('grade is A')
```

#### Solution

Python steps through the branches of the conditional in order, testing each in turn. Order matters!

### Compound Relations Using `and`, `or`, and Parentheses

Often, you want some combination of things to be true. You can combine relations within a conditional using `and` and `or`.

``` python
mass = [1, 2, 3, 4, 5]
velocity = [5, 4, 3, 2, 5]

for m, v in zip(mass, velocity):
    if m <= 3 and v <= 3:
        print("Small and slow")
    elif m <= 3 and v > 3:
        print("Small and fast")
    elif m > 3 and v <= 3:
        print("Large and slow")
    else:
        print("Check data")
```

- Use () to group subsets of conditions
- Aside: For a more natural way of working with many lists, look at `zip()`

### (Optional) Use the modulus to print occasional status messages

``` python
for count, filename in enumerate(glob.glob('data/gapminder_*.csv')):
    # Print every other filename
    if count % 2 == 0:
        print(count, filename)
```

## Writing Functions

### Break programs down into functions to make them easier to understand

- Human beings can only keep a few items in working memory at a time.
- Understand larger/more complicated ideas by understanding and combining pieces
- Functions serve the same purpose in programs:
  1.  Encapsulate complexity so that we can treat it as a single “thing”
  2.  Removes complexity from remaining code, making it easier to test
  3.  Enables re-use: Write one time, use many times

### Define a function using `def` with a name, parameters, and a block of code

``` python
def print_greeting():
    print('Hello!')
```

- Begin the definition of a new function with `def`, followed by the name of the function.
- Must obey the same rules as variable names.
- Parameters in parentheses; empty parentheses if the function doesn’t take any inputs.
- Indent function body

### Defining a function does not run it

``` python
print_greeting()
```

- Like assigning a value to a variable
- Must call the function to execute the code it contains.

### Arguments in call are matched to parameters in definition

1.  Positional arguments

    ``` python
    def print_date(year, month, day):
        """Print the formatted date. This works with strings or integers."""

        formatted_date = f"{year}/{month}/{day}"
        print(formatted_date)

    print_date(1871, 3, 19)
    ```

2.  (Optional) Keyword arguments

    ``` python
    print_date(month=3, day=19, year=1871)
    ```

### Functions may return a result to their caller using `return`

1.  Use `return ...` to give a value back to the caller. `return` ends the function's execution and *returns* you to the code that originally called the function.

    ``` python
    def average(values):
        """Return average of values."""

        return sum(values) / len(values)
    ```

    ``` python
    a = average([1, 3, 4])
    print(a)
    ```

2.  You should explicitly handle common problems:

    ``` python
    print(average([]))
    ```

    ``` python
    def average(values):
        """Return average of values, or None if no values are supplied."""

        if len(values) == 0:
            return None
        else:
            return sum(values) / len(values)
    ```

3.  Notes:

    1.  `return` can occur anywhere in the function, but functions are easier to understand if return occurs:
        1.  At the start to handle special cases
        2.  At the very end, with a final result
    2.  Docstring provides function help. Use triple quotes if you need the docstring to span multiple lines.

### **(Optional) challenge**: Encapsulate text processing in a function

Write a function that takes `line` as an input and returns the information required by `writer.writerow()`.

### **Challenge:** Encapsulate GDP calculations in a function

Write a function that calculates the mean GDP per capita for a Gapminder dataset. It should do the following:

1.  Read a CSV file into a data frame
2.  Calculate the mean GDP per capita for each country
3.  Append the mean GDP scores as a new column
4.  Return the data frame

#### Solution

NB: Test on "Americas" data to show the need for dropping the continent column.

``` python
def calc_mean_gdp(filename):
    """Add a mean GDP column to a data frame."""

    df = pd.read_csv(filename, index_col = "country")

    # If you need to drop the continent column
    if "continent" in df.columns:
        df.drop("continent", axis=1)

    # Get the mean GDP score for each country
    mean_gdp = data.mean(axis=1)
    df["mean_gdp"] = mean_gdp

    return df

df = calc_mean_gdp("data/gapminder_gdp_europe.csv")
```

### **(Optional) Challenge:** Use the function to process all files

Process all of the continent files using your new function. Concatenate the files into a new data frame and save that data frame in a new CSV file.

#### Solution

``` python
data_frames = []

for filename in glob.glob('data/gapminder_*.csv'):
    # Print a status message
    print("Current file:", filename)

    df = calc_mean_gdp(filename)
    data_frames.append(df)

all_data = pd.concat(data_frames)
all_data.to_csv("gapminder_mean_all.csv", index=False)
```

### (Optional) A worked example: The Lorenz attractor

<https://matplotlib.org/stable/gallery/mplot3d/lorenz_attractor.html>

## Notebooks vs Python scripts

### Differences between .ipynb and .py

1.  Export notebook to .py file
2.  Move .py file into data directory
3.  Compare files in TextEdit/Notepad

### Workflow differences between notebooks and scripts

Broadly, a trade-off between managing big code bases and making it easy to experiment. See: <https://github.com/elliewix/Ways-Of-Installing-Python/blob/master/ways-of-installing.md#why-do-you-need-a-specific-tool>

1.  Interactive testing and debugging
2.  Graphics integration
3.  Version control
4.  Remote scripts

## (Optional) Python from the terminal

1.  Python is an interactive interpreter (REPL)

    ``` bash
    python
    ```

2.  Python is a command line program

    ``` python
    # hello.py
    print("Hello!")
    ```

    ``` bash
    python hello.py
    ```

3.  (Optional) Python programs can accept command line arguments as inputs

    1.  List of command line inputs: `sys.argv` (<https://docs.python.org/3/library/sys.html#sys.argv>)
    2.  Utility for working with arguments: `argparse` (<https://docs.python.org/3/library/argparse.html>)

## (Optional) Use pathlib to write code that works across operating systems

1.  Pathlib provides cross-platform path objects

    ``` python
    from pathlib import Path

    # Create Path objects
    raw_path = Path("data")
    processed_path = Path("data/processed")

    print("Relative path:", processed_path)
    print("Absolute path:", processed_path.absolute())
    ```

2.  The file objects have methods that provide much better information about files and directories.

    ``` python
    #Note the careful testing at each level of the code.
    data_frames = []

    if raw_path.exists():
        for filename in raw_path.glob('gapminder_gdp_*.csv'):
            if filename.is_file():
                data = pd.read_csv(filename)
                print(filename)
                data_frames.append(data)

    all_data = pd.concat(data_frames)

    # Check for destination folder and create if it doesn't exist
    if not processed_path.exists():
        processed_path.mkdir()

    all_data.to_csv(processed_path.joinpath("combined_data.csv"))
    ```

## (Optional) Generic file handling

Pandas understands specific file types, but what if you need to work with a generic file?

### Open the file with a context manager

``` python
with open("data/bouldercreek_09_2013.txt", "r") as infile:
    lines = infile.readlines()
```

- The context manager closes the file when you're done reading it
- `"bouldercreek_09_2013.txt"` is the name of the file
- `infile` is a variable that refers to the file on disk

### A file is a collection of lines

`.readlines()` produces the file contents as a list of lines; each line is a string.

``` python
print(len(text))
print(type(text))

# View the first 10 lines
print(text[:10])
```

### Strings contain formatting marks

Compare the following:

``` python
# This displays the nicely-formatted document
print(lines[0])
```

``` python
# This shows the true nature of the string; you can see newlines (/n),
# tabs (/t), and other hidden characters
lines[0]
```

## (Optional) Text processing and data cleanup

### Use string methods to determine which lines to keep

1.  The file contains front matter that we can discard

    ``` python
    tabular_lines = []
    for line in lines:
        if not line.startswith("#"):
            tabular_lines.append(line)
    ```

2.  Now the first line is tab-separated data. Note that the print statement *prints* the tabs instead of showing us the `\t` character.

    ``` python
    tabular_lines[0]
    ```

### Open an output file for writing

``` python
outfile_name = "data/tabular_data.txt"

with open(outfile_name, "w") as outfile:
    outfile.writelines(tabular_lines)
```

### Format output as a comma-delimited text file

1.  Strip trailing whitespace

    ``` python
    stripped_line = tabular_lines[0].strip()
    stripped_line
    ```

2.  Split each line into a list based using the tabs.

    ``` python
    split_line = stripped_line.split("\t")
    split_line
    ```

3.  Use a special-purpose library to create a correctly-formatted CSV file

    ``` python
    import csv

    outfile_name = "data/csv_data.csv"
    with open(outfile_name, "w") as outfile:
        writer = csv.writer(outfile)
        for line in tabular_lines:
            csv_line = line.strip().split("\t")
            writer.writerow(csv_line)
    ```

4.  You can initialize `csv.reader` and `csv.writer` with different "dialects" or with custom delimiters and quotechars; see <https://docs.python.org/3/library/csv.html>

### (Optional) Avoid memory limitations by processing the input file one line at a time

``` python
infile_name = "data/bouldercreek_09_2013.txt"
outfile_name = "data/csv_data.csv"

with open(infile_name, "r") as infile, open(outfile_name, "w") as outfile:
    writer = csv.writer(outfile)
    for line in infile:
        if not line.startswith("#"):
            writer.writerow(line.strip().split("\t"))
```

### (Optional) Notes

1.  Pandas has utilities for reading fixed-width files: <https://pandas.pydata.org/docs/reference/api/pandas.read_fwf.html>

2.  Saving datasets with new-style string formatting

    ``` python
    for i in datasets_list:
       do_something(f'{i}.png'
    ```

# Visualization with Matplotlib and Seaborn (Week 4)

## Orientation

### Briefly revisit week 1

1.  Python orientation
2.  Jupyter orientation

### A brief history of plotting in Matplotlib

1.  Multiple interfaces
2.  Local graphs and global settings
3.  Matplotlib is the substrate for higher-level libraries
4.  Drawing things is verbose in any language

## Plotting with Matplotlib

### The basic plot

``` python
import matplotlib.pyplot as plt
fig, ax = plt.subplots()

time = [0, 1, 2, 3]
position = [0, 100, 200, 300]

ax.plot(time, position)
```

### Two kinds of plotting objects

``` python
type(fig)
```

``` python
print(type(fig))
print(type(ax))
```

- Figure objects handle display, printing, saving, etc.
- Axes objects contain graph information

### (Optional) Three ways of showing a figure

1.  Show figure inline (Jupyter Lab default)

    ``` python
    fig
    ```

2.  Show figure in a separate window (command line default)

    ``` python
    fig.show()
    ```

3.  Show figure in a separate window from Jupyter Lab. You may need to specify a different "backend" parameter for `matplotlib.use()` depending on your exact setup: <https://matplotlib.org/stable/tutorials/introductory/usage.html#the-builtin-backends>

    ``` python
    import matplotlib

    matplotlib.use('TkAgg')

    fig.show()
    ```

### The lifecycle of a custom plot

1.  Create mock data

    ``` python
    import numpy as np

    y = np.random.random(10) # outputs an array of 10 random numbers between 0 and 1
    x = np.arange(1980,1990,1) # generates an ordered array of numbers from 1980 to 1989

    # Check that x and y contain the same number of values
    assert len(x) == len(y)
    ```

2.  Inspect our data

    ``` python
    print("x:", x)
    print("y:", y)
    ```

3.  Create the basic plot

    ``` python
    # Convert y axis into a percentage
    y = y * 100

    # Draw plot
    fig, ax = plt.subplots()
    ax.plot(x, y)
    ```

4.  Show available styles

    ``` python
    # What are the global styles?
    plt.style.available
    ```

    ``` python
    # Set a global figure style
    plt.style.use("dark_background")

    # The style is only applied to new figures, not pre-existing figures
    fig
    ```

    ``` python
    # Re-creating the figure applies the new style
    fig, ax = plt.subplots()
    ax.plot(x, y)
    ```

5.  Customize the graph In principle, nearly every element on a Matplotlib figure is independently modifiable.

    ``` python
    # Set figure size
    fig, ax = plt.subplots(figsize=(8,6))

    # Set line attributes
    ax.plot(x, y, color='darkorange', linewidth=2, marker='o')

    # Add title and labels
    ax.set_title("Percent Change in Stock X", fontsize=22, fontweight='bold')
    ax.set_xlabel(" Years ", fontsize=20, fontweight='bold')
    ax.set_ylabel(" % change ", fontsize=20, fontweight='bold')

    # Adjust the tick labels
    ax.tick_params(axis='both', which='major', labelsize=18)

    # Add a grid
    ax.grid(True)
    ```

6.  Save your figure

    ``` python
    fig.savefig("mygraph_dark.png", dpi=300)
    ```

### (Optional) Plotting multiple data sets

In this example, plot GDP over time for multiple countries.

1.  Import data

    ``` python
    import pandas as pd
    data = pd.read_csv('data/gapminder_gdp_europe.csv', index_col='country')
    ```

    ``` python
    # Inspect our data
    data.head(3)
    ```

2.  Transform column headers into an ordinal scale

    1.  (Optional) Original column names are object (i.e. string) data

        ``` python
        data.columns
        ```

    2.  Strip off non-numeric portion of each column title

        ``` python
        years = data.columns.str.strip('gdpPercap_')
        years
        ```

    3.  Convert years strings into integers and replace original data frame column headers

        ``` python
        data.columns = years.astype(int)
        ```

3.  Extract rows from the DataFrame

    ``` python
    x_years = data.columns
    y_austria = data.loc['Austria']
    y_bulgaria = data.loc['Bulgaria']
    ```

4.  Create the plot object

    ``` python
    # Change global background back to default
    plt.style.use("default")

    # Create GDP figure
    fig, ax = plt.subplots(figsize=(8,6))

    # Create GDP plot
    ax.plot(x_years, y_austria, label='Austria', color='darkgreen', linewidth=2, marker='x')
    ax.plot(x_years, y_bulgaria, label='Bulgaria', color='maroon', linewidth=2, marker='o')

    # Decorate the plot
    ax.legend(fontsize=16, loc='upper center') #automatically uses labels
    ax.set_title("GDP of Austria vs Bulgaria", fontsize=22, fontweight='bold')
    ax.set_xlabel("Years", fontsize=20, fontweight='bold')
    ax.set_ylabel("GDP", fontsize=20, fontweight='bold')

    # Fix the display of years in scientific notation
    ax.xaxis.get_major_formatter().set_useOffset(False)
    ```

### (Optional) Plot directly from Pandas

Don't do this.

1.  The basic plot syntax

    ``` python
    ax = data.loc['Austria'].plot()
    fig = ax.get_figure()
    fig
    ```

2.  Decorate your Pandas plot

    ``` python
    ax = data.loc['Austria'].plot(figsize=(8,6), color='darkgreen', linewidth=2, marker='*')
    ax.set_title("GDP of Austria", fontsize=22, fontweight='bold')
    ax.set_xlabel("Years",fontsize=20, fontweight='bold' )
    ax.set_ylabel("GDP",fontsize=20, fontweight='bold' )

    fig = ax.get_figure()
    fig
    ```

3.  Overlaying multiple plots on the same figure with Pandas. This is super unintuitive.

    ``` python
    # Create an Axes object with the Austria data
    ax = data.loc['Austria'].plot(figsize=(8,6), color='darkgreen', linewidth=2, marker='*')
    print("Austria graph", id(ax))

    # Overlay the Bulgaria data on the same Axes object
    ax = data.loc['Bulgaria'].plot(color='maroon', linewidth=2, marker='o')
    print("Bulgaria graph", id(ax))
    ```

4.  The equivalent Matplotlib plot (optional)

    ``` python
    # extract the x and y values from dataframe
    x_years = data.columns
    y_gdp = data.loc['Austria']

    # Create the plot
    fig, ax = plt.subplots(figsize=(8,6))
    ax.plot(x_years, y_gdp, color='darkgreen', linewidth=2, marker='x')
    # etc.
    ```

## Visualization Strategy

### Read the docs

1.  Matplotlib gallery: <https://matplotlib.org/stable/gallery/index.html>
    1.  "Plotting categorical variables" example of multiple subplots
    2.  Download code examples
    3.  .py vs .ipynb
2.  Matplotlib tutorials: <https://matplotlib.org/stable/tutorials/index.html>
3.  Seaborn gallery: <https://seaborn.pydata.org/examples/index.html>
4.  Seaborn tutorials: <https://seaborn.pydata.org/tutorial.html>

### Workflow strategy

1.  Get in the ball park
2.  Look at lots of data
3.  Try lots of presets
4.  Customize judiciously
5.  Build collection of interactive and publication code snippets

### (Optional) There are many kinds of plots

``` python
## Visualize the same data using a scatterplot
plt.style.use('ggplot')

# Create a scatter plot
fig, ax = plt.subplots(figsize=(8,6))
ax.scatter(y_austria, y_bulgaria, color='blue', linewidth=2, marker='o')

# Decorate the plot
ax.set_title("GDP of Austria vs Bulgaria", fontsize=22, fontweight='bold')
ax.set_xlabel("GDP of Austria",fontsize=20, fontweight='bold' )
ax.set_ylabel("GDP of Bulgaria",fontsize=20, fontweight='bold' )
```

## Fast visualization and theming with Seaborn

Seaborn is a set of high-level pre-sets for Matplotlib.

### (Optional) Seaborn is a nice way to look at your data

``` python
# Import the Seaborn library
import seaborn as sns

ax = sns.lineplot(data=data.T, legend=False, dashes=False)
```

- Doing more with this data set requires transforming the data from wide form to long form; see <https://seaborn.pydata.org/tutorial/data_structure.html>

### Seaborn makes it easy to use preset styles

Let's make a poster!

1.  Import Iris data set <https://gist.githubusercontent.com/curran/a08a1080b88344b0c8a7/raw/0e7a9b0a5d22642a06d3d5b9bcbad9890c8ee534/iris.csv>

    ``` python
    iris = pd.read_csv("../data/iris.csv")
    iris.head()
    ```

2.  Create a basic scatter plot

    ``` python
    ax = sns.scatterplot(data=iris, x='sepal_length',y='petal_length')
    ```

3.  Change plotting theme

    ``` python
    # plt.style.use("dark_background")

    # Fix grid if necessary
    #plt.rcParams["axes.grid"] = False

    # Make everything visible at a distance
    sns.set_context('poster')

    # Color by species
    ax = sns.scatterplot(data=iris, x='sepal_length', y='petal_length', hue='species',
                         palette='colorblind', size='petal_width')

    # Place legend
    ax.legend(bbox_to_anchor=(2,1))
    ```

    - Read more about `loc` vs. `bbox_to_anchor` in the legend documentation: <https://matplotlib.org/stable/api/legend_api.html>

4.  The Seaborn plot uses Matplotlib under the hood

    ``` python
    # Set the figure size
    fig = ax.get_figure()
    fig.set_size_inches(8,6)

    fig
    ```

### Box Plots and Swarm Plots

1.  Box plot

    ``` python
    plt.style.use("default")
    ax = sns.boxplot(data=iris, x='species', y='petal_length')
    ```

2.  Swarm plot

    ``` python
    ax = sns.swarmplot(data=iris,x='species', y='petal_length', hue='species', palette='Set1')
    ax.legend(loc='upper left', fontsize=16)
    ax.tick_params(axis='x', labelrotation = 45)
    ```

    This gives us a format warning.

3.  Strip plot

    ``` python
    ax = sns.stripplot(data=iris,x='species', y='petal_length', hue='species', palette='Set1')
    ax.legend(loc='upper left', fontsize=16)
    ax.tick_params(axis='x', labelrotation = 45)
    ```

4.  Overlapping plots

    ``` python
    ax = sns.boxplot(data=iris, x='species', y='petal_length')
    sns.stripplot(data=iris, x='species', y='petal_length', ax=ax, palette='Set1', hue='species')
    ```

### Palmer Archipeligo Penguin Data

``` python
penguins = sns.load_dataset("penguins")
penguin
```

### Grouped bar plot

``` python
# Clear previous chart settings
#plt.clf()

sns.set_theme(style="whitegrid")

# Draw a nested barplot by species and sex
fig2 = sns.catplot(
    data=penguins, kind="bar",
    x="species", y="body_mass_g", hue="sex",
    palette="dark", alpha=.6, height=6,
    errorbar='sd'
    #ci='sd'  # This is deprecated in newer versions of Seaborn
)

fig2.despine(left=True)
fig2.set_axis_labels("", "Body mass (g)")
fig2.legend.set_title("")

# Re-display:
#fig2.figure
```

### (Optional) Scatterplot with categorical variables

``` python
plt.clf()
sns.set_theme(style="whitegrid", palette="muted")

# Draw a categorical scatterplot to show each observation
fig3 = sns.swarmplot(data=penguins, x="body_mass_g", y="sex", hue="species")
fig3.set(ylabel="")

#fig3.figure
```

### Multiple linear regression

``` python
plt.clf()
sns.set_theme()

# Plot bill length and bill depth by species
fig4 = sns.lmplot(
    data=penguins,
    x="bill_length_mm", y="bill_depth_mm", hue="species",
    height=5
)

# Use more informative axis labels than are provided by default
fig4.set_axis_labels("Snoot length (mm)", "Snoot depth (mm)")

#fig4.figure
```

### Scatterplot Matrix

``` python
plt.clf()
sns.set_theme(style="ticks")

fig5 = sns.pairplot(penguins, hue="species")

#fig5.figure

# Save our figure
fig5.savefig("scatterplot_matrix.png", dpi=300)
```

### Histograms showing variation within each species

``` python
plt.clf()
sns.set_theme(style="darkgrid")

fig6 = sns.displot(
    penguins, x="bill_length_mm", col="species",
    binwidth=3, height=3, facet_kws=dict(margin_titles=True),
)

#fig6.figure
```

### Joint kernel density estimate

``` python
#
# (i.e. smoothed histograms)
plt.clf()
sns.set_theme(style="ticks")

# Show the joint distribution using kernel density estimation
fig7 = sns.jointplot(
    data=penguins,
    x="bill_length_mm", y="bill_depth_mm", hue="species",
    kind="kde",
)

#fig7.figure
```

### Paired density and scatterplot matrix

``` python
plt.clf()
sns.set_theme(style="white")


fig8 = sns.PairGrid(penguins, diag_sharey=False)
fig8.map_upper(sns.scatterplot, s=15)
fig8.map_lower(sns.kdeplot)
fig8.map_diag(sns.kdeplot, lw=2)

#fig8.figure
```

### (Optional) There are many styling options

1.  Add styling to individual points

    ``` python
    ax = sns.scatterplot(data=iris, x='sepal_length', y='petal_length', hue='species', palette='colorblind', style='species')
    ```

2.  Prettify column names

    ``` python
    words = [' '.join(i) for i in iris.columns.str.split('_')]
    iris.columns = words
    ```

3.  Make a regression plot

    ``` python
    # Color by species, size by petal width
    ax = sns.regplot(data=iris, x='sepal_length', y='petal_length', scatter=True,
                     scatter_kws={'color':'white'})
    ```

### (Optional) Bar Charts

1.  Bar Plot

    ``` python
    ax = sns.barplot(data=iris, x='species', y='sepal_width', palette='colorblind')
    ```

    - Default summary statistic is mean, and default error bars are 95% confidence interval.

2.  Add custom parameters

    ``` python
    # Error bars show standard deviation
    ax = sns.barplot(data=iris, x='species', y='sepal_width', ci='sd', edgecolor='black')
    ```

3.  (Optional) count plot counts the records in each category

    ``` python
    ax = sns.countplot(data=iris, x='species', palette='colorblind')
    ```

### (Optional) Histograms

1.  Histogram of overall data set

    ``` python
    ax = sns.histplot(data=iris, x='petal_length', kde=True)
    ```

    - KDE: If True, compute a kernel density estimate to smooth the distribution and show on the plot as (one or more) line(s).
    - There seems a bimodal distribution of petal length. What factors underly this distribution?

2.  Histogram of data decomposed by category

    ``` python
    ax = sns.histplot(data=iris, x='petal_length', hue='species', palette='Set2')
    ```

3.  Create multiple subplots to compare binning strategies

    ``` python
    # This generates 3 subplots (ncols=3) on the same figure
    fig, axes = plt.subplots(figsize=(12,4), nrows=1, ncols=3)

    # Note that we can use Seaborn to draw on our Matplotlib figure
    sns.histplot(data=iris,x='petal_length', bins=5, ax=axes[0], color='#f5a142')
    sns.histplot(data=iris,x='petal_length', bins=10, ax=axes[1], color='maroon')
    sns.histplot(data=iris,x='petal_length', bins=15, ax=axes[2], color='darkmagenta')
    ```

## (Optional) How Matplotlib works

### Understanding Matplotlib

1.  Everything is an Artist (object)
2.  Multiple levels of specificity
    - `plt` vs `axes`
    - rcParams vs temporary stylings
3.  Simplified high-level interfaces, aka "syntactic sugar"
    - `legend()` vs get legend handles and patches

### Matplotlib object syntax

- The `object.set_field(value)` usage is taken from Java, which was popular in 2003 when Matplotlib was developing its object-oriented syntax
- You get values back out with `object.get_field(value)`
- The Pythonic way to set a value would be `object.field = value`. However, the Matplotlib getters and setters do a lot of internal bookkeeping, so if you try to set field values directly you will get errors. For example, compare `ax.get_ylabel()` with `ax.yaxis.label`.
- Read "The Lifecycle of a Plot": <https://matplotlib.org/stable/tutorials/introductory/lifecycle.html>
- Read "Why you hate Matplotlib": <https://ryxcommar.com/2020/04/11/why-you-hate-matplotlib/>

# Special Topics

## Environments

## Working with unstructured files

### Open the file with a context handler

``` python
with open('pettigrew_letters_ORIGINAL.txt', 'r') as file_in:
    text = file_in.read()

print(len(text))
```

### Strings contain formatting marks

Compare the following:

``` python
# This displays the nicely-formatted document
print(text[:300])
```

``` python
# This shows the true nature of the string; you can see newlines (/n),
# tabs (/t), and other hidden characters
text[:300]
```

### Many ways of handling a file

#### `.read()` produces the file contents as one string

``` python
type(text)
```

#### `.readlines()` produces the file contents as a list of lines; each line is a string

``` python
with open('pettigrew_letters_ORIGINAL.txt', 'r') as file_in:
    text = file_in.readlines()

print(len(text))
print(type(text))
```

#### Inspect parts of the file using list syntax

``` python
# View the first 10 lines
text[:10]
```

### Working with unstructured file data

#### Contents of pettigrew_letters_ORIGINAL.txt

1.  Intro material
2.  Manifest of letters
3.  Individual letters

#### Query: Are all the letters in the manifest actually there?

1.  check if all the letters reported in the manifest appear in the actual file
2.  check if all the letters in the file are reported in the manifest
3.  Therefore, construct two variables: (1) A list of every location line from the manifest, and (2) a list of every location line within the file proper

#### Get the manifest by visual inspection

``` python
manifest_list = text[14:159]
```

#### Use string functions to clean up and inspect text

Demonstrate string tests with manifest_list:

``` python
# Raw text
for location in manifest_list[:10]:
    print(location)
```

``` python
# Remove extra whitespace
for location in manifest_list[:10]:
    print(location.strip())
```

``` python
# Test whether the cleaned line starts with 'Box '
for location in manifest_list[:10]:
    stripped_line = location.strip()
    print(stripped_line.startswith('Box '))
```

``` python
# Test whether the cleaned line starts with 'box '
for location in manifest_list[:10]:
    stripped_line = location.strip()
    print(stripped_line.startswith('box '))
```

#### Gather all the locations in the full document

``` python
letters = text[162:]

for line in letters[:25]:
    # Create a variables to hold current line and truth value of is_box
    stripped_line = line.strip()
    is_box = stripped_line.startswith('Box ')
    if is_box == True:
        print(stripped_line)
    # If the line is empty, don't print anything
    elif stripped_line == '\n':
        continue
    # Indent non-Box lines
    else:
        print('---', stripped_line)
```

- Before automate everything, we run the code with lots of `print()` statements so that we can see what's happening

#### Collect the positive results

``` python
letter_locations = []

for line in letters:
    stripped_line = line.strip()
    is_box = stripped_line.startswith("Box ")
    if is_box == True:
        letter_locations.append(stripped_line)
```

#### Compare the manifest and the letters

``` python
print('Items in manifest:', len(manifest_list))
print('Letters:', len(letter_locations))
```

#### Follow-up questions

1.  Which items are in one list but not the other?
2.  Are there other structural regularities you could use to parse the data? (Note that in the letters, sometimes there are multiple letters under a single box header)

## Exception handling

Explicitly handle common errors, rather than waiting for your code to blow up.

``` python
def average(values):
    "Return average of values, or None if no values are supplied."

    if len(values) == 0:
        return None
    return sum(values) / len(values)

print(average([3, 4, 5]))       # Prints expected output
print(average([]))              # Explicitly handles possible divide-by-zero error
print(average(4))               # Unhandled exception
```

``` python
def average(values):
    "Return average of values, or an informative error if bad values are supplied."

    try:
        return sum(values) / len(values)
    except ZeroDivisionError as err:
        return err
    except TypeError as err:
        return err

print(average([3, 4, 5]))
print(average(4))
print(average([]))
```

- Use judiciously, and be as specific as possible. When in doubt, allow your code to blow up rather than silently commit errors.

## Performance and profiling

``` python
from timeit import time
import cProfile
import pstats

def my_fun(val):
    # Get 1st timestamp
    t1 = time.time()

    # do work

    # Get 2nd timestamp
    t2 = time.time()
    print(round(t2 - t1, 3))

# Run the function with the profiler and collect stats
cProfile.run('my_fun(val)', 'dumpstats')
s = pstats.Stats('dumpstats')
```

## Reducing memory usage

### Read a file one line at a time

``` python
with open('pettigrew_letters_ORIGINAL.txt', 'r') as file_in:
    for line in file_in:
        # Do stuff to current line
        pass
```

### Use a SQLite database

``` python
import sqlite3

conn = sqlite3.connect('my_database_name.db')
with conn:
    c = conn.execute("SELECT column_name FROM table_name WHERE criterion")
    results = c.fetchall()
    c.close

# Do stuff with `results`
```

## Other optional topics

- Checking performance
- List comprehensions
- Defensive programming
- Debugging and Testing

# Endnotes

## Credits

- Plotting and Programming in Python (Pandas-oriented): <http://swcarpentry.github.io/python-novice-gapminder/>
- Programming with Python (NumPy-oriented): <https://swcarpentry.github.io/python-novice-inflammation/index.html>
- Python for Ecology: <https://datacarpentry.org/python-ecology-lesson/>
- Humanities Python Tour (file and text processing): <https://github.com/elliewix/humanities-python-tour/blob/master/Two-Hour-Beginner-Tour.ipynb>
- Introduction to Cultural Analytics & Python: <https://melaniewalsh.github.io/Intro-Cultural-Analytics/welcome.html>
- Rhondene Wint: Matplotlib and Seaborn notes
- Fruit Alphabet: <https://en.wikibooks.org/wiki/Wikijunior:Fruit_Alphabet>

## References

### Standard Python

- Python tutorial: <https://docs.python.org/3/tutorial/index.html>
- Python standard library: <https://docs.python.org/3/library/>
- String formatting: <https://pyformat.info/>
- True and False in Python: <https://docs.python.org/3/library/stdtypes.html#truth-value-testing>

### Scientific Computing Libraries

- NumPy documentation: <https://numpy.org/doc/stable/user/index.html>
- Pandas documentation: <https://pandas.pydata.org/pandas-docs/stable/>
- Pandas user guide: <https://pandas.pydata.org/docs/user_guide/index.html>
- SciPy user guide: <https://docs.scipy.org/doc/scipy/tutorial/index.html>
- Statsmodels library: <https://www.statsmodels.org/stable/index.html>
- Scikit-Learn documentation: <https://scikit-learn.org/stable/>
- Statistics in Python tutorial: <https://scipy-lectures.org/packages/statistics/>

### Data Visualization Libraries

- Matplotlib gallery of examples: <https://matplotlib.org/gallery/index.html>
- Matplotlib tutorials: <https://matplotlib.org/stable/tutorials/index.html>
- Seaborn gallery of examples: <https://seaborn.pydata.org/examples/index.html>
- Seaborn tutorials: <https://seaborn.pydata.org/tutorial.html>

### Marginalia

- How to choose a code editor: <https://github.com/elliewix/Ways-Of-Installing-Python/blob/master/ways-of-installing.md#why-do-you-need-a-specific-tool>
- IPython magic commands: <https://ipython.readthedocs.io/en/stable/interactive/magics.html>
- Writing documentation in Markdown: <https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax>

## Data Sources

1.  Gapminder data: <http://swcarpentry.github.io/python-novice-gapminder/files/python-novice-gapminder-data.zip>
2.  Ecology data (field surveys): <https://datacarpentry.org/python-ecology-lesson/data/portal-teachingdb-master.zip>
3.  Social Science data (SAFI): <https://datacarpentry.org/socialsci-workshop/data/>
4.  Humanities data (Pettigrew letters): <http://dx.doi.org/10.5334/data.1335350291>
