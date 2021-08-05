
# Table of Contents

1.  [Fundamentals](#org30fe457)
    1.  [Orientation](#org8949304)
    2.  [Jupyter commands](#org92e21a7)
    3.  [Data Types and Type Conversion](#org29ea923)
    4.  [Variables and Assignment](#org160af6b)
    5.  [Built-in Functions and Help](#org217dacb)
    6.  [Libraries](#org8503b6b)
    7.  [Lists](#orge384e6a)
    8.  [GOTO Reading Tabular Data into DataFrames (1-day workshop order)](#org252909f)
    9.  [GOTO Pandas DataFrames (1-day workshop order)](#orgd4aae5a)
    10. [GOTO Plotting (1-day workshop order)](#org8f1b8ff)
    11. [For Loops](#org69c3af7)
    12. [Dictionaries (optional)](#org6ce4717)
    13. [Other containers (optional)](#org41ab7f0)
    14. [Homework](#org9fca107)
2.  [Building Programs](#org9c7df69)
    1.  [Conditionals](#org5efa6df)
    2.  [GOTO Looping over data sets (1-day workshop order)](#org7f7668f)
    3.  [Writing Functions](#org16062f4)
    4.  [Variable Scope](#orgd3cd969)
    5.  [Programming Style](#orgf5b189b)
    6.  [Working with unstructured files](#org85eeb25)
    7.  [Exception handling (optional)](#org686f3d3)
    8.  [Reducing memory usage 1: Read a file one line at a time (optional)](#orgb66b64e)
    9.  [Reducing memory usage 2: Use an SQLite database (optional)](#org5eca4d9)
    10. [Other optional topics](#org74672e8)
    11. [Homework](#orgc401687)
3.  [Week 3: Data manipulation with Pandas, stats with Statsmodels, ML with Scikit-Learn](#org56d337d)
    1.  [Explicitly talk about linear algebra with NumPy](#org658698c)
    2.  [draw out matrix/list vs dataframe/dict](#orgead815f)
    3.  [Rewrite as dplyr/SQL-style query/filter/subset lesson](#orgfb076c4)
    4.  [Standard library vs. outside modules](#org6cd4e5c)
    5.  [SciPy project](#orgbe538f4)
    6.  [Downstream libraries](#orgaa94b4d)
    7.  [Reading Tabular Data into DataFrames](#org3806c06)
    8.  [Pandas DataFrames](#org84f026e)
    9.  [Looping Over Data Sets](#orgeb292ba)
    10. [Command-Line Programs](#orgeeaf1c3)
    11. [Statistics](#org66b7aaf)
    12. [Machine learning with Scikit-Learn](#org7d3c393)
4.  [Week 4: Visualization with Matplotlib, Pandas, and Seaborn](#org926635c)
    1.  [What does it mean to be Pythonic?](#org9330b7d)
    2.  [Seaborn 0.11 new features: https://seaborn.pydata.org/whatsnew.html](#orgfba770d)
    3.  [Workshop Objectives](#org722c136)
    4.  [Big 5 graphs](#org5f14255)
    5.  [Matplotlib](#org96b6107)
5.  [Credits](#orgf139107)
6.  [Example Data](#org8c6a833)



<a id="org30fe457"></a>

# Fundamentals


<a id="org8949304"></a>

## Orientation


### What programming language should I use?

1.  Use the language that your friends use (so you can ask them for help)
2.  Use a language that has a community of practice for your desired use case (you can find documentation, bug reports, sample code, etc.)
3.  Use a language that is "best" by some technical definition


### Python is pretty good at lots of things


### Literate programming and notebooks

-   Blend code, documentation, and visualization
-   Good for trying things, demos
-   Bad for massive or long-running processes


<a id="org92e21a7"></a>

## Jupyter commands


### How to start Jupyter Lab


#### Method 1

1.  Open Anaconda Navigator
2.  Run Jupyter Lab


#### Method 2

Open Terminal (MacOS/Linux) or Anaconda Prompt (Windows)

    cd Desktop/data
    jupyter lab


### Execute cell with CTRL-Enter; execute cell and move to new cell with Shift-Enter

    3 + 7


### Navigation

-   Use drag-and-drop interface to move .ipynb file to new location
-   Rename your notebook to something informative


<a id="org29ea923"></a>

## Data Types and Type Conversion


### Every value has a type

Most data is text and numbers:

-   Integers: whole numbers (counting)
-   Floats: real numbers (math)
-   Strings: text
-   &#x2026;and many others


### Numbers


#### Common math operations can combine integers and floats

    1 / 2.0


#### We can display more interesting output with the `print()` function

    print('half is', 1 / 2.0)
    print('three squared is', 3.0 ** 2)


#### Counting operations require integers

    print(10 % 3)                   # "Modulus", or remainder


### Use the built-in function `type()` to find the type of a value

    type(53)

    type(3.12)

    type('Derek')


### Must convert strings to numbers or vice versa when operating on them

    1 + '2'                         # Produces an error

    1 + float('2')

    # You can embed functions inside other functions
    print(str(43))
    print(int('3'))
    print(float('3'))


<a id="org160af6b"></a>

## Variables and Assignment


### Use variables to store values

Variables are names for values.

    first_name = 'Derek'
    age = 42

-   can only contain letters, digits, and underscore \_ (typically used to separate words in long variable names)
-   cannot start with a digit
-   are case sensitive (`age`, `Age` and `AGE` are three different variables)


### Use `print()` to display values

    print(first_name, 'is', age, 'years old')

-   Functions are verbs; recognizable by ()
-   Functions take arguments (i.e. do stuff with the values that you give them)
-   `print()` useful for tracking progress, debugging
-   NB: Jupyter Lab will always echo the **last** value in a cell, so we won't need `print()` a lot of the time


### Variables must be created before they are used

    # Prints an informative error message; more about this later
    print(last_name)


### Variables can be used in calculations

    age = age + 3
    print('Age in three years:', age)


### Variables only change value when something is assigned to them

    first = 1
    second = 5 * first
    first = 2
    print('first is', first, 'and second is', second)


### Use meaningful names!


<a id="org217dacb"></a>

## Built-in Functions and Help


### Online resources

-   <https://libguides.ucmerced.edu/software-carpentry/python/references>
-   Stack Overflow


### Use comments to add documentation to programs

    # This sentence isn't executed by Python.
    adjustment = 0.5   # Neither is this - anything after '#' is ignored.


### A function may take zero or more arguments

    print('before')
    print()
    print('after')


### Commonly-used built-in functions include `max()`, `min()`, and `round()`

    max(1, 2, 3)

    min('a', 'A', '0')       # 0-9, A-Z, a-z; However, notice they are all strings!


### Functions may only work for certain (combinations of) arguments

    max(1, 'a')              # Not a meaningful comparision


### Functions may have default values for some arguments

    # By default, we round to the nearest integer
    round(3.712)

    # You can optionally specify the number of significant digits
    round(3.712, 1)


### Use the built-in function `help()` to get help for a function

    help(round)

-   1 mandatory argument
-   1 optional argument with a default value: `ndigits=None`


### Python reports a syntax error when it can’t understand the source of a program

    name = 'Bob
    age = = 54
    print("Hello world"


### Python reports a runtime error when something goes wrong while a program is executing

We have seen some of these already.


### CHALLENGE: Why not?

Why is it that `max` and `min` do not return `None` when they are called with no arguments?

Solution:

`max` and `min` return TypeErrors in this case because the correct number of parameters was not supplied. If it just returned None, the error would be much harder to trace as it would likely be stored into a variable and used later in the program, only to likely throw a runtime error.


<a id="org8503b6b"></a>

## Libraries


### Most of the power of a programming language is in its libraries

<https://docs.python.org/3/library/index.html>


### A program must `import` a library module before using it

    import math
    
    print('pi is', math.pi)
    print('cos(pi) is', math.cos(math.pi))

-   Refer to things from the module as `module-name.thing-name`
-   Python uses "." to mean "part of" or "belongs to".


### Use `help()` to learn about the contents of a library module

    help(math)                      # user friendly

    dir(math)                       # brief reminder, not user friendly


### Import specific items from a library module to shorten programs.

You want to be careful with this. It's safer to keep the namespace.

    from math import cos, pi
    
    print('cos(pi) is', cos(pi))


### Create an alias for a library module when importing it to shorten programs

    import math as m
    
    print('cos(pi) is', m.cos(m.pi))


### CHALLENGE: Locating the Right Module

You want to select a random character from a string:

    bases = 'ACTTGCTTGAC'

1.  Which standard library module could help you? <https://docs.python.org/3/library/>
2.  Which function would you select from that module? Are there alternatives?
3.  Try to write a program that uses the function.

Solution:

You could try the `random` module.

The string has 11 characters, each having a positional index from 0 to 10. You could use either `random.randrange` or `random.randint` functions to get a random integer between 0 and 10, and then pick out the character at that position:

    from random import randrange
    
    random_index = randrange(len(bases))
    print(bases[random_index])

or more compactly:

    from random import randrange
    
    print(bases[randrange(len(bases))])

Perhaps you found the random.sample function? It allows for slightly less typing:

    from random import sample
    
    print(sample(bases, 1)[0])

Note that this function returns a list of values. We will learn about lists in episode 11.
There’s also other functions you could use, but with more convoluted code as a result.


<a id="orge384e6a"></a>

## Lists


### A list stores many values in a single structure

    pressures = [0.273, 0.275, 0.277, 0.275, 0.276]
    print('pressures:', pressures)
    print('length:', len(pressures))


### Use an item’s index to fetch it from a list

    print('zeroth item of pressures:', pressures[0])
    print('fourth item of pressures:', pressures[4])


### Count backwards from the end with negative integers

    print('last item of pressures:', pressures[-1])


### Use a slice to get a subset of the list

The slicing syntax is `my_list[inclusive_start_position:exclusive_stop_position:optional_step_amount]`

    # Up to, but not including 3
    print('first 3 items of pressures:', pressures[0:3])


### Indexing beyond the end of the collection is an error

    pressures[20]


### Lists’ values can be replaced by assigning to them

    pressures[0] = 0.265
    print('pressures is now:', pressures)


### Appending items to a list lengthens it

    primes = [2, 3, 5]
    print('primes is initially:', primes)
    primes.append(7)
    print('primes has become:', primes)

-   `append()` is a *method* of lists. Methods are like functions, but they are tied to particular objects.
-   Use `object-name.method-name()` to call methods
-   Deliberately resembles the way we refer to things in a library
-   We will meet other methods of lists as we go along; use `help(list)` for a preview.


### Extend is similar to append, but allows you to merge two lists

    teen_primes = [11, 13, 17, 19]
    middle_aged_primes = [37, 41, 43, 47]
    print('primes is currently:', primes)
    primes.extend(teen_primes)
    print('primes has now become:', primes)
    primes.append(middle_aged_primes)
    print('primes has finally become:', primes)


### Use del to remove items from a list entirely

    primes = [2, 3, 5, 7, 9]
    print('primes before removing last item:', primes)
    del primes[4]
    print('primes after removing last item:', primes)


### The empty list contains no values

Helpful for collecting values


### Lists may contain values of different types

    location = ['latitude', 37.28306, 'N', 'longitude', 120.50778, 'W']


### Strings can be indexed like lists


#### Use an index to get a single character from a string

Count from 0

    element = 'carbon'
    element[0]


#### Use a slice to get a substring

    # Up to, but not including 3
    sample = element[0:3]
    print(sample)


#### Counting backwards

    element[-1]


#### Use the built-in function `len()` to find the length of a string

    len('carbon')                   # length is an integer


### But! Character strings are immutable

    element[0] = 'C'


### Python is full of analogies

-   lists and strings
-   lists and files


<a id="org252909f"></a>

## GOTO Reading Tabular Data into DataFrames (1-day workshop order)


<a id="orgd4aae5a"></a>

## GOTO Pandas DataFrames (1-day workshop order)


<a id="org8f1b8ff"></a>

## GOTO Plotting (1-day workshop order)


<a id="org69c3af7"></a>

## For Loops


### A `for` loop executes commands once for each value in a collection

"For each thing in this group, do these operations"

    for number in [2, 3, 5]:
        print(number)

-   A for loop is made up of a collection, a loop variable, and a body
-   The collection, **[2, 3, 5]**, is what the loop is being run on.
-   The body, **print(number)**, specifies what to do for each value in the collection.
-   The loop variable, **number**, is what changes for each iteration of the loop (i.e. the “current thing”)


### The first line of the `for` loop must end with a colon, and the body must be indented

    # This produces an error
    for number in [2, 3, 5]:
    print(number)

    # So does this
    firstName = "Jon"
    lastName = "Smith"


### Loop variables can be called anything

    for kitten in [2, 3, 5]:
        print(kitten)

-   It's just a placeholder


### The body of a loop can contain many statements

    primes = [2, 3, 5]
    for p in primes:
        squared = p ** 2
        cubed = p ** 3
        print(p, squared, cubed)


### Use `range()` to iterate over a sequence of numbers

    for number in range(0, 3):
        print(number)

-   range() produces numbers on demand (a "generator" function)
-   useful for tracking progress


### The Accumulator pattern turns many values into one

    # Sum the first 10 integers.
    total = 0
    for number in range(1, 11):
       total = total + number
    print(total)


<a id="org6ce4717"></a>

## Dictionaries (optional)

-   Dictionaries are sets of key/value pairs
-   Instead of being indexed by position, they are indexed by key

    ages = {'Derek': 42,
            'Bill': 24,
            'Susan': 37}
    
    print(ages['Derek'])

    location = {'latitude': [37.28306, 'N'],
                'longitude': [120.50778, 'W']}
    
    for key, val in location.items():
        print(key, 'is', val[0], val[1])


<a id="org41ab7f0"></a>

## Other containers (optional)

-   Tuples
-   Sets


<a id="org9fca107"></a>

## Homework


### Read the following help files:

    help('')
    help([])


### Try to find 2 ways to capitalize 'carbon'


<a id="org9c7df69"></a>

# Building Programs


<a id="org5efa6df"></a>

## Conditionals


### Use `if` statements to control whether or not a block of code is executed

An `if` statement (more properly called a conditional statement) controls whether some block of code is executed or not.
Structure is similar to a `for` statement:

-   First line opens with `if` and ends with a colon
-   Body containing one or more statements is indented (usually by 4 spaces)

    mass = 3.54
    if mass > 3.0:
        print(mass, 'is large')
    
    mass = 2.07
    if mass > 3.0:
        print (mass, 'is large')


### Conditionals are often used inside loops

Not much point using a conditional when we know the value (as above), but useful when we have a collection to process.

    masses = [3.54, 2.07, 9.22, 1.86, 1.71]
    for m in masses:
        if m > 3.0:
            print(m, 'is large')


### Use else to execute a block of code when an if condition is not true

`else` can be used following an `if`. This allows us to specify an alternative to execute when the if branch isn’t taken.

    masses = [3.54, 2.07, 9.22, 1.86, 1.71]
    for m in masses:
        if m > 3.0:
            print(m, 'is large')
        else:
            print(m, 'is small')


### Use `elif` to specify additional tests

May want to provide several alternative choices, each with its own test; use `elif` (short for “else if”) and a condition to specify these.

    masses = [3.54, 2.07, 9.22, 1.86, 1.71]
    for m in masses:
        if m > 9.0:
            print(m, 'is HUGE')
        elif m > 3.0:
            print(m, 'is large')
        else:
            print(m, 'is small')

-   Always associated with an `if`.
-   Must come before the `else` (which is the “catch all”).


### Conditions are tested once, in order

Python steps through the branches of the conditional in order, testing each in turn.
Order matters! The following is wrong:

    grade = 85
    if grade >= 70:
        print('grade is C')
    elif grade >= 80:
        print('grade is B')
    elif grade >= 90:
        print('grade is A')


### Use conditionals in a loop to “evolve” the values of variables

    velocity = 10.0
    for i in range(5): # execute the loop 5 times
        print(i, ':', velocity)
        if velocity > 20.0:
            print('moving too fast')
            velocity = velocity - 5.0
        else:
            print('moving too slow')
            velocity = velocity + 10.0
    print('final velocity:', velocity)


### Compound Relations Using `and`, `or`, and Parentheses

Often, you want some combination of things to be true. You can combine relations within a conditional using `and` and `or`. Continuing the example above, suppose you have:

    mass     = [ 3.54,  2.07,  9.22,  1.86,  1.71]
    velocity = [10.00, 20.00, 30.00, 25.00, 20.00]
    
    i = 0
    for i in range(5):
        if mass[i] > 5 and velocity[i] > 20:
            print("Fast heavy object.  Duck!")
        elif mass[i] > 2 and mass[i] <= 5 and velocity[i] <= 20:
            print("Normal traffic")
        elif mass[i] <= 2 and velocity[i] <= 20:
            print("Slow light object.  Ignore it")
        else:
            print("Whoa!  Something is up with the data.  Check it")

-   Use () to group subsets of conditions
-   Aside: For a more natural way of working with many lists, look at `zip()`


<a id="org7f7668f"></a>

## GOTO Looping over data sets (1-day workshop order)


<a id="org16062f4"></a>

## Writing Functions


### Break programs down into functions to make them easier to understand

-   Human beings can only keep a few items in working memory at a time.
-   Understand larger/more complicated ideas by understanding and combining pieces
-   Functions serve the same purpose in programs:
    1.  Encapsulate complexity so that we can treat it as a single “thing”
    2.  Removes complexity from remaining code, making it easier to test
    3.  Enables re-use: Write one time, use many times


### Define a function using `def` with a name, parameters, and a block of code

    def print_greeting():
        print('Hello!')

-   Begin the definition of a new function with `def`, followed by the name of the function.
-   Must obey the same rules as variable names.
-   Parameters in parentheses; empty parentheses if the function doesn’t take any inputs.
-   Colon, then an indented block of code


### Defining a function does not run it

-   Like assigning a value to a variable
-   Must call the function to execute the code it contains.

    print_greeting()


### Arguments in call are matched to parameters in definition

-   Specify parameters when defining a function; these become variables when the function is executed
-   By default (if you don’t name the arguments when calling the function) the arguments will be matched to parameters in the order the parameters are defined in the function.

    def print_date(year, month, day):
        joined = '/'.join([year, month, day])
        print(joined)
    
    print_date(1871, 3, 19)

    # If you name the arguments you can specify any order
    print_date(month=3, day=19, year=1871)


### Functions may return a result to their caller using `return`

-   Use `return ...` to give a value back to the caller
-   May occur anywhere in the function, but functions are easier to understand if return occurs:
    -   At the start to handle special cases
    -   At the very end, with a final result
-   `return` ends the function's execution and *returns* you to the code that originally called the function

    def average(values):
        "Return average of values, or None if no values are supplied."
    
        if len(values) == 0:
            return None
        return sum(values) / len(values)

-   Docstring provides function help
-   Use triple quotes if you need the docstring to span multiple lines: `"""Like this"""`
-   Here, the `if` statement "falls through" to the second `return` when `values != 0`
-   For maximum clarity, you could add `else` before the outer `return`

    a = average([1, 3, 4])
    print('average of actual values:', a)

    print('average of empty list:', average([]))

    # Every function returns something
    result = print_date(1871, 3, 19)
    print('result of call is:', result)


### Using functions with conditionals in Pandas (optional)

    # Apply a function to every row of the selected column
    def my_fun(val):
        pass
    
    data = pd.read_csv('data/gapminder_all.csv')
    data['new_col'] = data['lifeExp_1952'].apply(my_fun)


<a id="orgd3cd969"></a>

## TODO Variable Scope


<a id="orgf5b189b"></a>

## TODO Programming Style


<a id="org85eeb25"></a>

## Working with unstructured files


### Open the file with a context handler

    with open('pettigrew_letters_ORIGINAL.txt', 'r') as file_in:
        text = file_in.read()
    
    print(len(text))


### Strings contain formatting marks

Compare the following:

    # This displays the nicely-formatted document
    print(text[:300])

    # This shows the true nature of the string; you can see newlines (/n),
    # tabs (/t), and other hidden characters
    text[:300]


### Many ways of handling a file


#### `.read()` produces the file contents as one string

    type(text)


#### `.readlines()` produces the file contents as a list of lines; each line is a string

    with open('pettigrew_letters_ORIGINAL.txt', 'r') as file_in:
        text = file_in.readlines()
    
    print(len(text))
    print(type(text))


#### Inspect parts of the file using list syntax

    # View the first 10 lines
    text[:10]


### Working with unstructured file data


#### Contents of pettigrew\_letters\_ORIGINAL.txt

1.  Intro material
2.  Manifest of letters
3.  Individual letters


#### Query: Are all the letters in the manifest actually there?

1.  check if all the letters reported in the manifest appear in the actual file
2.  check if all the letters in the file are reported in the manifest
3.  Therefore, construct two variables: (1) A list of every location line from the manifest, and (2) a list of every location line within the file proper


#### Get the manifest by visual inspection

    manifest_list = text[14:159]


#### Use string functions to clean up and inspect text

Demonstrate string tests with manifest\_list:

    # Raw text
    for location in manifest_list[:10]:
        print(location)

    # Remove extra whitespace
    for location in manifest_list[:10]:
        print(location.strip())

    # Test whether the cleaned line starts with 'Box '
    for location in manifest_list[:10]:
        stripped_line = location.strip()
        print(stripped_line.startswith('Box '))

    # Test whether the cleaned line starts with 'box '
    for location in manifest_list[:10]:
        stripped_line = location.strip()
        print(stripped_line.startswith('box '))


#### Gather all the locations in the full document

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

-   Before automate everything, we run the code with lots of `print()` statements so that we can see what's happening


#### Collect the positive results

    letter_locations = []
    
    for line in letters:
        stripped_line = line.strip()
        is_box = stripped_line.startswith("Box ")
        if is_box == True:
            letter_locations.append(stripped_line)


#### Compare the manifest and the letters

    print('Items in manifest:', len(manifest_list))
    print('Letters:', len(letter_locations))


#### Follow-up questions

1.  Which items are in one list but not the other?
2.  Are there other structural regularities you could use to parse the data? (Note that in the letters, sometimes there are multiple letters under a single box header)


<a id="org686f3d3"></a>

## Exception handling (optional)

Explicitly handle common errors, rather than waiting for your code to blow up.

    def average(values):
        "Return average of values, or None if no values are supplied."
    
        if len(values) == 0:
            return None
        return sum(values) / len(values)
    
    print(average([3, 4, 5]))       # Prints expected output
    print(average([]))              # Explicitly handles possible divide-by-zero error
    print(average(4))               # Unhandled exception

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

-   Use judiciously, and be as specific as possible. When in doubt, allow your code to blow up rather than silently commit errors.


<a id="orgb66b64e"></a>

## Reducing memory usage 1: Read a file one line at a time (optional)

    with open('pettigrew_letters_ORIGINAL.txt', 'r') as file_in:
        for line in file_in:
            # Do stuff to current line
            pass


<a id="org5eca4d9"></a>

## Reducing memory usage 2: Use an SQLite database (optional)

    import sqlite3
    
    conn = sqlite3.connect('my_database_name.db')
    with conn:
        c = conn.execute("SELECT column_name FROM table_name WHERE criterion")
        results = c.fetchall()
        c.close
    
    # Do stuff with `results`


<a id="org74672e8"></a>

## Other optional topics

-   Checking performance
-   List comprehensions
-   File writing
-   Variable Scope
-   Programming Style
-   Defensive programming


<a id="orgc401687"></a>

## Homework


### Revisit the `str` documentation with an eye towards using the string processing methods for cleaning up data


### How would you determine which letters and/or manifest items are missing?


<a id="org56d337d"></a>

# Week 3: Data manipulation with Pandas, stats with Statsmodels, ML with Scikit-Learn


<a id="org658698c"></a>

## TODO Explicitly talk about linear algebra with NumPy


<a id="orgead815f"></a>

## TODO draw out matrix/list vs dataframe/dict


<a id="orgfb076c4"></a>

## TODO Rewrite as dplyr/SQL-style query/filter/subset lesson

In general, the lesson spends too much time in the weeds. We want to take a high-level, declarative view of our data, and only invoke fiddly methods as necessary.

-   concat/merge <https://pandas.pydata.org/docs/reference/api/pandas.concat.html>
-   filter/group/subset: <https://pandas.pydata.org/docs/user_guide/groupby.html>


<a id="org6cd4e5c"></a>

## Standard library vs. outside modules

1.  Install with conda package manager
2.  Install with pip


<a id="orgbe538f4"></a>

## SciPy project

1.  NumPy: matrix algebra
2.  Pandas: data filtering and transformation; factors
3.  Matplotlib: graphs
4.  Scipy.stats: probability distributions, basic tests
    <https://docs.scipy.org/doc/scipy/reference/stats.html>


<a id="orgaa94b4d"></a>

## Downstream libraries

1.  Seaborn: Pythonic graphs built on Matplotlib
2.  Statsmodels: Statistical models and formulae built on Scipy.stats
    <https://www.statsmodels.org/stable/index.html>
3.  Scikit-Learn: Machine learning tools built on NumPy, SciPy, and Matplotlib
    <https://scikit-learn.org/stable/>
4.  &#x2026;and many more: <https://www.scipy.org/topical-software.html>


<a id="org3806c06"></a>

## Reading Tabular Data into DataFrames


### Use the Pandas library to do statistics on tabular data

    import pandas as pd
    
    data = pd.read_csv('gapminder_gdp_europe.csv')
    print(data)


### Use `index_col` to specify that a column’s values should be used as row headings

Row headings are indexed by number by default (0, 1, 2,&#x2026;.). For convenience, we want to index by country:

    #data = pd.read_csv('/Users/gilgamesh/Desktop/data/gapminder_gdp_oceania.csv', index_col='country')
    data = pd.read_csv('gapminder_gdp_europe.csv', index_col='country')
    print(data)


### Use `DataFrame.info` to find out more about a dataframe

    data.info()


### The `DataFrame.columns` variable stores information about the dataframe’s columns

Note that this is an attribute, not a method:

    data.columns


### Use `DataFrame.T` to transpose a dataframe

Does not copy or modify the data, just changes caller's view of it:

    data.T

In Jupyter Lab, compare this output to:

    print(data.T)


### Use `DataFrame.describe` to get summary statistics about data

    data.describe()


### Pandas help files are dense; you should prefer the online documentation

<https://pandas.pydata.org/docs/user_guide/index.html>


### CHALLENGE: (all)


### Other useful attributes and methods (optional)

    # rows, columns
    data.shape

    # Returns first 5 items by default
    data.head()

    # Returns last 2 items
    data.tail(2)


### A brief aside about list comprehensions and viewing data structures (optional)

    print(dir(data))

    # Create a new list that filters out internal attributes, functions, and methods
    df_public = [item for item in dir(data) if not item.startswith('_')]
    print(df_public)

    # Pretty-print the new list; extremely optional
    import pprint
    
    pp = pprint.PrettyPrinter(width=100, compact=True, indent=2)
    pp.pprint(df_public)

Objects have attributes (i.e. data, fields, properties) and methods (i.e. procedures). The difference between a method and a function is that methods are attached to objects, whereas functions are free-floating ("first-class citizens").

    # Create two new lists, one with the public methods and one with the public attributes.
    # NB: Because Python allows you to override any method or attribute at runtime,
    # testing with `callable` is not always reliable.
    df_methods = [item for item in dir(data) if not item.startswith('_') and callable(getattr(data, item))]
    df_attr = [item for item in dir(data) if not item.startswith('_') and not callable(getattr(data, item))]
    
    pp.pprint(df_methods)
    pp.pprint(df_attr)


<a id="org84f026e"></a>

## Pandas DataFrames


### Note about Pandas DataFrames/Series

-   A DataFrame is a collection of Series columns
-   Each Series is a dict-like 1-dimensional NumPy array
-   Therefore, each series inherits many of the abilities (linear algebra) and limitations (single data type) of NumPy


### Selecting values

Rows have positions [i, j, ..] and labels. This gives us two ways to access data:

1.  Treat the DataFrame as a matrix and select values using linear algebra operators
2.  Treat the DataFrame as a table and select values using labels


#### Use `DataFrame.iloc[..., ...]` to select values by their (entry) position

The `i` in `iloc` stands for "index".

    data.iloc[0, 0]


#### Use `DataFrame.loc[..., ...]` to select values by their (entry) label

    data.loc["Albania", "gdpPercap_1952"]


#### Use : on its own to mean all columns or all rows

Just like Python’s usual slicing notation. You can treat DataFrames as multi-dimensional lists!

    data.loc["Albania", :]


#### Select multiple columns or rows using `DataFrame.loc` and a named slice

Generalizing the concept of slice to include labeled indexes:

    data.loc['Italy':'Poland', 'gdpPercap_1962':'gdpPercap_1972']


### Result of slicing can be used in further operations

Any operation that you can use on the whole data frame can be used on a slice

    print(data.loc['Italy':'Poland', 'gdpPercap_1962':'gdpPercap_1972'].max())
    print(data.loc['Italy':'Poland', 'gdpPercap_1962':'gdpPercap_1972'].min())

    data.loc['Italy':'Poland', 'gdpPercap_1962':'gdpPercap_1972'].describe()


### Use comparisons to select data based on value

Compares element-by-element and returns a similarly-shaped dataframe of `True` and `False`

    subset = data.loc['Italy':'Poland', 'gdpPercap_1962':'gdpPercap_1972']

    subset

    # Which GDPs are greater than 10,000?
    subset > 10000


### Select values or NaN using a Boolean mask

Mask the matrix values that fail to meet a criterion.

    mask = subset > 10000
    subset[mask]

NaNs are ignored by numerical operations like max, min, average, etc.

    subset[mask].describe()


### Generic comparisons between matrices (optional)

-   Series and DataFrame have the binary comparison methods `eq`, `ne`, `lt`, `gt`, `le`, and `ge`
-   You can apply the reductions: `empty`, `any()`, `all()`, and `bool()` to provide a way to summarize a boolean result
-   You can find many more options for comparison and sub-setting here: <https://pandas.pydata.org/docs/user_guide/basics.html>


### Group By: split-apply-combine

Split data according to criterion, do numeric transformations, then recombine.

    # Get all GDPs greater than the mean
    mask_higher = data > data.mean()
    
    # Count the number of time periods in which each country exceeds the mean
    higher_count = mask_higher.aggregate('sum', axis=1)
    
    # Create a normalized wealth-over-time score
    wealth_score = higher_count / len(data.columns)
    wealth_score


### Add to DataFrame

DataFrames are dictionary-like objects

    # Wealth Score is a series
    type(wealth_score)
    
    data['normalized_wealth'] = wealth_score


### Write new file with ~DataFrame.to\_csv

Capture the results of your filter in a new file, rather than overwriting your original data.

    # Save to a new CSV, preserving your original data
    data.to_csv('gapminder_gdp_europe_normed.csv')


### Relationship between data structures (optional)

<https://pandas.pydata.org/docs/user_guide/dsintro.html#column-selection-addition-deletion>

-   You can convert data between NumPy arrays, Series, and DataFrames
-   You can read data into any of the data structures from files or from standard Python containers
-   NumPy arrays are list-like; Series and DataFrames are dict-like


### Methods for extending DataFrames (optional)

-   Merge, join, concatenate and compare: <https://pandas.pydata.org/docs/user_guide/merging.html>


<a id="orgeb292ba"></a>

## Looping Over Data Sets


### File paths as an example of increasing abstraction in program development

1.  File paths as strings
2.  File paths as string patterns
3.  File paths as abstract Path objects


### Use a `for` loop to process files given a list of their names

    for filename in ['gapminder_gdp_africa.csv', 'gapminder_gdp_asia.csv']:
        data = pd.read_csv(filename, index_col='country')
        print(filename, data.min())


### Use glob.glob to find sets of files whose names match a pattern

In Unix, the term “globbing” means “matching a set of files with a pattern”. The most common patterns are:

-   \`\*\` meaning “match zero or more characters”
-   \`?\` meaning “match exactly one character”

    import glob
    print('all csv files in data directory:', glob.glob('*.csv'))


### Use glob and for to process batches of files

    for filename in glob.glob('gapminder_*.csv'):
        data = pd.read_csv(filename)
        print(filename, data['gdpPercap_1952'].min())


### Use pathlib to write code that works across operating systems

Where are we?

    import os
    os.getcwd()

    from pathlib import Path
    directory_path = Path("/Users/gilgamesh/Desktop/data")
    
    for filename in directory_path.glob('gapminder_*.csv'):
        if filename.is_file():
            data = pd.read_csv(filename)
            print(filename, data['gdpPercap_1952'].min())


### CHALLENGE: Comparing data

Write a program that reads in the regional data sets and plots the average GDP per capita for each region over time in a single chart.

Solution:

    import glob
    import pandas as pd
    import matplotlib.pyplot as plt
    fig, ax = plt.subplots(1,1)
    for filename in glob.glob('data/gapminder_gdp*.csv'):
        dataframe = pd.read_csv(filename)
        # extract <region> from the filename, expected to be in the format 'data/gapminder_gdp_<region>.csv'.
        # we will split the string using the split method and `_` as our separator,
        # retrieve the last string in the list that split returns (`<region>.csv`),
        # and then remove the `.csv` extension from that string.
        region = filename.split('_')[-1][:-4]
        dataframe.mean().plot(ax=ax, label=region)
    plt.legend()
    plt.show()


<a id="orgeeaf1c3"></a>

## Command-Line Programs

Batch processing from command line, .py files, and editors

    python my_program.py


<a id="org66b7aaf"></a>

## Statistics


### Libraries

1.  statistics
    Basic summary statistics. Part of the Python standard library.
2.  scipy.stats
    Descriptive statistics and distributions: <https://docs.scipy.org/doc/scipy/reference/stats.html>
3.  statsmodels
    Statistical models and tests. Incorporates scipy.stats. <https://www.statsmodels.org/stable/index.html>


### Regression example


#### Sample file

Download "surveys.csv" from <https://figshare.com/articles/Portal_Project_Teaching_Database/1314459>
Direct download link: <https://ndownloader.figshare.com/files/10717177>


#### Import data

    data = pd.read_csv('surveys.csv')
    
    # Check for NaN
    print("Valid weights:", data['weight'].count())
    print("NaN weights:", data['weight'].isna().sum())
    print("Valid lengths:", data['hindfoot_length'].count())
    print("NaN lengths:", data['hindfoot_length'].isna().sum())


#### Fit OLS regression model

    from statsmodels.formula.api import ols
    
    model = ols("weight ~ hindfoot_length", data, missing='drop').fit()
    print(model.summary())


#### Generic parameters for all models

    import statsmodels
    
    help(statsmodels.base.model.Model)


<a id="org7d3c393"></a>

## Machine learning with Scikit-Learn

<https://scikit-learn.org/stable/>


### Which estimator?

<https://scikit-learn.org/stable/tutorial/machine_learning_map/index.html>
![img](https://scikit-learn.org/stable/_static/ml_map.png)


### Editorial comments about ML

1.  We already have statistics, so do the reading
2.  Talk to a domain expert
3.  Beware parameter mining
4.  Treat all software as beta software


<a id="org926635c"></a>

# Week 4: Visualization with Matplotlib, Pandas, and Seaborn

1.  Use object-oriented Matplotlib syntax, e.g.: `fig, axes = plt.subplot()`
    <https://matplotlib.org/stable/tutorials/introductory/lifecycle.html>
2.  Pandas > Seaborn > Matplotlib decoration approach
    -   <https://datacarpentry.org/python-socialsci/13-matplotlib/index.html>
    -   <https://ryxcommar.com/2020/04/11/why-you-hate-matplotlib/>


<a id="org9330b7d"></a>

## What does it mean to be Pythonic?

The seamy history of Python plotting


<a id="orgfba770d"></a>

## Seaborn 0.11 new features: <https://seaborn.pydata.org/whatsnew.html>


<a id="org722c136"></a>

## Workshop Objectives

1.  Make a plot with python's base library matplotlib.pyplot
2.  Generate plots from dataframes using pandas and seaborn
3.  Modify graph aesthetics and themes
4.  Save plots to an image file


<a id="org5f14255"></a>

## Big 5 graphs

Fundamentally, graphs communicate two types of information: 1) Relationships/trends among data and 2) the distribution of data.

1.  Line plot
2.  Scatter plot
3.  Bar plot
4.  Histogram
5.  Box plot


<a id="org96b6107"></a>

## Matplotlib


### Basic line plot (time series example)

    import matplotlib.pyplot as plt

    # make up data
    import numpy as np
    
    y = np.random.random(10) # outputs an array of 10 random numbers between 0 and 1
    x = np.arange(1980,1990,1) # generates an ordered array of numbers from 1980 to 1989

    print(x)
    print(y)
    
    #check that x and y contain the same number of values
    len(x) == len(y)

    #turn y into a percentage
    y = y*100
    print(y)

    ## simple line plot example of stock price changes
    
    #3 basic commands to create a basic figure
    plt.figure()
    plt.plot(x,y)
    plt.show()


### Customizing Graph Aesthetics

In principle, nearly every element on a matplotlib figure is independently modifiable.

    #change theme style
    plt.style.available

    plt.style.use('dark_background')  #changes theme of all plots

    ## modify figure size,  axes and fonts
    plt.figure(figsize=(8,6)) #(width, height) inches
    plt.plot(x,y,color='darkorange', linewidth=2, marker='o')
    
    #add title and axes label, adjust font size and style
    
    plt.title("Percent Change in Stock X", fontsize=22, fontweight='bold')
    plt.xlabel(" Years ",fontsize=20, fontweight='bold')
    plt.ylabel(" % change ",fontsize=20, fontweight='bold')
    
    #adjust tick labels
    plt.xticks(fontsize=18)
    plt.yticks(fontsize=18)
    
    #add a grid
    plt.grid(True)
    # save figure
    plt.savefig("mygraph_dark.png",dpi=300, bbox_inches='tight')
    plt.show()

    # Saving datasets with new-style string formatting
    #for i in datasets_list:
    #    plt.savefig(f'{i}.png',....)


### Plotting from dataframes with Gapminder dataset

    import pandas as pd
    
    #load gapminder data
    gapminder = pd.read_csv("gapminder_gdp_europe.csv", index_col='country')


<a id="orgf139107"></a>

# Credits

-   Plotting and Programming in Python (Pandas-oriented): <http://swcarpentry.github.io/python-novice-gapminder/>
-   Programming with Python (NumPy-oriented): <https://swcarpentry.github.io/python-novice-inflammation/index.html>
-   Humanities Python Tour (file and text processing): <https://github.com/elliewix/humanities-python-tour/blob/master/Two-Hour-Beginner-Tour.ipynb>
-   Pandas User Guide: <https://pandas.pydata.org/docs/user_guide/index.html>
-   Statistics in Python: <https://scipy-lectures.org/packages/statistics/>
-   Rhondene Wint: Matplotlib and Seaborn notes


<a id="org8c6a833"></a>

# Example Data

-   Gapminder data: <https://swcarpentry.github.io/python-novice-gapminder/files/python-novice-gapminder-data.zip>
-   Pettigrew letters: <https://raw.githubusercontent.com/devnich/python-programming/master/pettigrew_letters_ORIGINAL.txt>
-   Ecology survey data: <https://ndownloader.figshare.com/files/10717177> (from <https://figshare.com/articles/Portal_Project_Teaching_Database/1314459> )

