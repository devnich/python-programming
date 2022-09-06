-   [**WEEK 1: Fundamentals**](#week-1-fundamentals)
-   [Orientation](#orientation)
    -   [What programming language should I
        use?](#what-programming-language-should-i-use)
    -   [Python is pretty good at lots of
        things](#python-is-pretty-good-at-lots-of-things)
    -   [Literate programming and
        notebooks](#literate-programming-and-notebooks)
-   [Jupyter commands](#jupyter-commands)
    -   [How to start Jupyter Lab](#how-to-start-jupyter-lab)
    -   [Execute cell with CTRL-Enter; execute cell and move to new cell
        with
        Shift-Enter](#execute-cell-with-ctrl-enter-execute-cell-and-move-to-new-cell-with-shift-enter)
    -   [Navigation](#navigation)
-   [Variables and Assignment](#variables-and-assignment)
    -   [Use variables to store values](#use-variables-to-store-values)
    -   [Use `print()` to display values](#use-print-to-display-values)
    -   [Variables must be created before they are
        used](#variables-must-be-created-before-they-are-used)
    -   [Variables can be used in
        calculations](#variables-can-be-used-in-calculations)
    -   [Variables only change value when something is assigned to
        them](#variables-only-change-value-when-something-is-assigned-to-them)
    -   [Use meaningful names!](#use-meaningful-names)
-   [Data Types and Type Conversion](#data-types-and-type-conversion)
    -   [Every value has a type](#every-value-has-a-type)
    -   [Use the built-in function `type()` to find the type of a
        value](#use-the-built-in-function-type-to-find-the-type-of-a-value)
    -   [Types control what operations can be performed on a given
        value](#types-control-what-operations-can-be-performed-on-a-given-value)
    -   [Must convert strings to numbers or vice versa when operating on
        them](#must-convert-strings-to-numbers-or-vice-versa-when-operating-on-them)
    -   [Can mix integers and floats freely in
        operations](#can-mix-integers-and-floats-freely-in-operations)
    -   [CHALLENGE: Explain what each operator
        does](#challenge-explain-what-each-operator-does)
-   [Built-in Functions and Help](#built-in-functions-and-help)
    -   [Online resources](#online-resources)
    -   [Use comments to add documentation to
        programs](#use-comments-to-add-documentation-to-programs)
    -   [A function may take zero or more
        arguments](#a-function-may-take-zero-or-more-arguments)
    -   [Every function returns
        *something*](#every-function-returns-something)
    -   [Commonly-used built-in functions include `max()`, `min()`, and
        `round()`](#commonly-used-built-in-functions-include-max-min-and-round)
    -   [Functions may only work for certain (combinations of)
        arguments](#functions-may-only-work-for-certain-combinations-of-arguments)
    -   [Functions may have default values for some
        arguments](#functions-may-have-default-values-for-some-arguments)
    -   [Use the built-in function `help()` to get help for a
        function](#use-the-built-in-function-help-to-get-help-for-a-function)
    -   [Functions attached to objects are called
        methods](#functions-attached-to-objects-are-called-methods)
    -   [Python reports a syntax error when it can't understand the
        source of a
        program](#python-reports-a-syntax-error-when-it-cant-understand-the-source-of-a-program)
    -   [Python reports a runtime error when something goes wrong while
        a program is
        executing](#python-reports-a-runtime-error-when-something-goes-wrong-while-a-program-is-executing)
    -   [CHALLENGE: What happens when?
        (optional)](#challenge-what-happens-when-optional)
-   [Libraries](#libraries)
    -   [Most of the power of a programming language is in its
        libraries](#most-of-the-power-of-a-programming-language-is-in-its-libraries)
    -   [A program must `import` a library module before using
        it](#a-program-must-import-a-library-module-before-using-it)
    -   [Use `help()` to learn about the contents of a library
        module](#use-help-to-learn-about-the-contents-of-a-library-module)
    -   [Import specific items from a library module to shorten
        programs.](#import-specific-items-from-a-library-module-to-shorten-programs.)
    -   [Create an alias for a library module when importing it to
        shorten
        programs](#create-an-alias-for-a-library-module-when-importing-it-to-shorten-programs)
    -   [Python has opinions about how to write your
        programs](#python-has-opinions-about-how-to-write-your-programs)
    -   [CHALLENGE: Locating the Right Module
        (optional)](#challenge-locating-the-right-module-optional)
-   [Lists](#lists)
    -   [A list stores many values in a single
        structure](#a-list-stores-many-values-in-a-single-structure)
    -   [Use an item's index to fetch it from a
        list](#use-an-items-index-to-fetch-it-from-a-list)
    -   [Indexing beyond the end of the collection is an
        error](#indexing-beyond-the-end-of-the-collection-is-an-error)
    -   [Count backwards from the end with negative
        integers](#count-backwards-from-the-end-with-negative-integers)
    -   [Use a slice to get a subset of the
        list](#use-a-slice-to-get-a-subset-of-the-list)
    -   [Lists' values can be replaced by assigning to
        them](#lists-values-can-be-replaced-by-assigning-to-them)
    -   [Appending items to a list lengthens
        it](#appending-items-to-a-list-lengthens-it)
    -   [Extend is similar to append, but allows you to merge two
        lists](#extend-is-similar-to-append-but-allows-you-to-merge-two-lists)
    -   [Use del to remove items from a list
        entirely](#use-del-to-remove-items-from-a-list-entirely)
    -   [Use pop() to remove the last item and assign it to a
        variable](#use-pop-to-remove-the-last-item-and-assign-it-to-a-variable)
    -   [The empty list contains no
        values](#the-empty-list-contains-no-values)
    -   [Lists may contain values of different
        types](#lists-may-contain-values-of-different-types)
    -   [Strings can be indexed like
        lists](#strings-can-be-indexed-like-lists)
    -   [But! Character strings are
        immutable](#but-character-strings-are-immutable)
    -   [Python is full of analogies](#python-is-full-of-analogies)
    -   [CHALLENGE: From Strings to Lists and
        Back](#challenge-from-strings-to-lists-and-back)
-   [Dictionaries](#dictionaries)
    -   [Dictionaries are sets of key/value pairs. Instead of being
        indexed by position, they are indexed by
        key.](#dictionaries-are-sets-of-keyvalue-pairs.-instead-of-being-indexed-by-position-they-are-indexed-by-key.)
    -   [Update dictionaries by assigning a new key/value
        pair](#update-dictionaries-by-assigning-a-new-keyvalue-pair)
    -   [Delete an item using del or
        pop()](#delete-an-item-using-del-or-pop)
    -   [Dictionaries are the natural way to store tree-structured
        data](#dictionaries-are-the-natural-way-to-store-tree-structured-data)
    -   [CHALLENGE: Convert lists to dictionary
        (group)](#challenge-convert-lists-to-dictionary-group)
-   [Other containers (optional)](#other-containers-optional)
-   [**WEEK 2: Data manipulation with
    Pandas**](#week-2-data-manipulation-with-pandas)
-   [(Optional) Review lists and
    dictionaries](#optional-review-lists-and-dictionaries)
-   [(Optional) Review strings](#optional-review-strings)
-   [Where are we?](#where-are-we)
    -   [Python provides functions for working with the file
        system.](#python-provides-functions-for-working-with-the-file-system.)
    -   [(Optional) These provide a rich Python alternative to shell
        functions](#optional-these-provide-a-rich-python-alternative-to-shell-functions)
-   [Reading Tabular Data into
    DataFrames](#reading-tabular-data-into-dataframes)
    -   [Use the Pandas library to work on tabular
        data](#use-the-pandas-library-to-work-on-tabular-data)
    -   [Use `index_col` to specify that a column's values should be
        used as row
        headings](#use-index_col-to-specify-that-a-columns-values-should-be-used-as-row-headings)
    -   [Data frames have methods (i.e. functions) that perform
        operations using the data frame\'s contents as
        input](#data-frames-have-methods-i.e.-functions-that-perform-operations-using-the-data-frames-contents-as-input)
    -   [Data frames have fields (i.e. variables) that hold additional
        information](#data-frames-have-fields-i.e.-variables-that-hold-additional-information)
    -   [Pandas help files are dense; you should prefer the online
        documentation](#pandas-help-files-are-dense-you-should-prefer-the-online-documentation)
    -   [Challenge](#challenge)
    -   [(Optional) Introspecting on the DataFrame
        object](#optional-introspecting-on-the-dataframe-object)
-   [Pandas DataFrames](#pandas-dataframes)
    -   [Notes about Pandas
        DataFrames/Series](#notes-about-pandas-dataframesseries)
    -   [(Optional) Pandas introduces some new
        types](#optional-pandas-introduces-some-new-types)
    -   [Selecting values](#selecting-values)
    -   [Result of slicing can be used in further
        operations](#result-of-slicing-can-be-used-in-further-operations)
    -   [Use comparisons to select data based on
        value](#use-comparisons-to-select-data-based-on-value)
    -   [Use method chaining to create final output without creating
        intermediate
        variables](#use-method-chaining-to-create-final-output-without-creating-intermediate-variables)
    -   [(Optional) DataFrame methods have sensible defaults that you
        can
        change](#optional-dataframe-methods-have-sensible-defaults-that-you-can-change)
    -   [(Optional) Truth value of whole data
        frames](#optional-truth-value-of-whole-data-frames)
    -   [(Carpentries version) Group By:
        split-apply-combine](#carpentries-version-group-by-split-apply-combine)
    -   [Group By: split-apply-combine](#group-by-split-apply-combine)
    -   [(Optional) Adding rows to
        DataFrames](#optional-adding-rows-to-dataframes)
    -   [(Carpentries) Challenge](#carpentries-challenge)
-   [**WEEK 3: Visualization with Matplotlib and
    Seaborn**](#week-3-visualization-with-matplotlib-and-seaborn)
-   [Graphs](#graphs)
    -   [Big 5 graphs](#big-5-graphs)
-   [Plotting with Matplotlib](#plotting-with-matplotlib)
    -   [Create a basic plot](#create-a-basic-plot)
    -   [Two kinds of plotting objects](#two-kinds-of-plotting-objects)
    -   [Three ways of showing a figure
        (optional)](#three-ways-of-showing-a-figure-optional)
    -   [Line Plots](#line-plots)
    -   [Explore your data with Pandas](#explore-your-data-with-pandas)
    -   [Plot directly from Pandas
        (optional)](#plot-directly-from-pandas-optional)
    -   [Plotting multiple data sets](#plotting-multiple-data-sets)
-   [Seaborn: Pythonic, high-level pre-sets for
    Matplotlib](#seaborn-pythonic-high-level-pre-sets-for-matplotlib)
    -   [A simple plot](#a-simple-plot)
    -   [Import the Iris data set](#import-the-iris-data-set)
    -   [Scatter Plot](#scatter-plot)
    -   [Bar Charts](#bar-charts)
    -   [Histograms](#histograms)
    -   [Box Plots and Swarm Plots](#box-plots-and-swarm-plots)
    -   [Heat Map](#heat-map)
-   [Seaborn 0.11 new features:
    https://seaborn.pydata.org/whatsnew.html](#seaborn-0.11-new-features-httpsseaborn.pydata.orgwhatsnew.html)
-   [Looping through datasets](#looping-through-datasets)
-   [**WEEK 4: Building Programs**](#week-4-building-programs)
-   [For Loops](#for-loops)
    -   [A `for` loop executes commands once for each value in a
        collection](#a-for-loop-executes-commands-once-for-each-value-in-a-collection)
    -   [The first line of the `for` loop must end with a colon, and the
        body must be
        indented](#the-first-line-of-the-for-loop-must-end-with-a-colon-and-the-body-must-be-indented)
    -   [Loop variables can be called
        anything](#loop-variables-can-be-called-anything)
    -   [The body of a loop can contain many
        statements](#the-body-of-a-loop-can-contain-many-statements)
    -   [Use `range()` to iterate over a sequence of
        numbers](#use-range-to-iterate-over-a-sequence-of-numbers)
    -   [Use `enumerate()` to iterate over a sequence of items and their
        positions](#use-enumerate-to-iterate-over-a-sequence-of-items-and-their-positions)
    -   [The Accumulator pattern turns many values into
        one](#the-accumulator-pattern-turns-many-values-into-one)
    -   [Dictionary iteration](#dictionary-iteration)
    -   [How do you know if an object is iterable?
        (optional)](#how-do-you-know-if-an-object-is-iterable-optional)
    -   [Don\'t use `for` loops with DataFrames or Numpy
        matrices](#dont-use-for-loops-with-dataframes-or-numpy-matrices)
-   [Conditionals](#conditionals)
    -   [Use `if` statements to control whether or not a block of code
        is
        executed](#use-if-statements-to-control-whether-or-not-a-block-of-code-is-executed)
    -   [Conditionals are often used inside
        loops](#conditionals-are-often-used-inside-loops)
    -   [Use else to execute a block of code when an if condition is not
        true](#use-else-to-execute-a-block-of-code-when-an-if-condition-is-not-true)
    -   [Use `elif` to specify additional
        tests](#use-elif-to-specify-additional-tests)
    -   [Conditions are tested once, in
        order](#conditions-are-tested-once-in-order)
    -   [Use conditionals in a loop to "evolve" the values of
        variables](#use-conditionals-in-a-loop-to-evolve-the-values-of-variables)
    -   [Compound Relations Using `and`, `or`, and Parentheses
        (optional)](#compound-relations-using-and-or-and-parentheses-optional)
-   [Looping Over Data Sets](#looping-over-data-sets)
    -   [File paths as an example of increasing abstraction in program
        development](#file-paths-as-an-example-of-increasing-abstraction-in-program-development)
    -   [Use a `for` loop to process files given a list of their
        names](#use-a-for-loop-to-process-files-given-a-list-of-their-names)
    -   [Use glob.glob to find sets of files whose names match a
        pattern](#use-glob.glob-to-find-sets-of-files-whose-names-match-a-pattern)
    -   [Use glob and for to process batches of
        files](#use-glob-and-for-to-process-batches-of-files)
    -   [Use pathlib to write code that works across operating systems
        (optional)](#use-pathlib-to-write-code-that-works-across-operating-systems-optional)
    -   [CHALLENGE: Comparing data (optional)
        (rewrite)](#challenge-comparing-data-optional-rewrite)
-   [Writing Functions](#writing-functions)
    -   [Break programs down into functions to make them easier to
        understand](#break-programs-down-into-functions-to-make-them-easier-to-understand)
    -   [Define a function using `def` with a name, parameters, and a
        block of
        code](#define-a-function-using-def-with-a-name-parameters-and-a-block-of-code)
    -   [Defining a function does not run
        it](#defining-a-function-does-not-run-it)
    -   [Arguments in call are matched to parameters in
        definition](#arguments-in-call-are-matched-to-parameters-in-definition)
    -   [Functions may return a result to their caller using
        `return`](#functions-may-return-a-result-to-their-caller-using-return)
    -   [A worked example: The Lorenz
        attractor](#a-worked-example-the-lorenz-attractor)
    -   [Use functions to encapsulate large code blocks
        (optional)](#use-functions-to-encapsulate-large-code-blocks-optional)
    -   [Using functions with conditionals in Pandas
        (optional)](#using-functions-with-conditionals-in-pandas-optional)
-   [Software Logistics](#software-logistics)
    -   [Python files vs. Notebook
        files](#python-files-vs.-notebook-files)
    -   [Python from the command line](#python-from-the-command-line)
    -   [Updating your Python
        installation](#updating-your-python-installation)
    -   [Version control](#version-control)
-   [Variable Scope (optional)](#variable-scope-optional)
-   [Programming Style (optional)](#programming-style-optional)
-   [Working with unstructured files
    (optional)](#working-with-unstructured-files-optional)
    -   [Open the file with a context
        handler](#open-the-file-with-a-context-handler)
    -   [Strings contain formatting
        marks](#strings-contain-formatting-marks)
    -   [Many ways of handling a file](#many-ways-of-handling-a-file)
    -   [Working with unstructured file
        data](#working-with-unstructured-file-data)
-   [Exception handling (optional)](#exception-handling-optional)
-   [Performance and profiling
    (optional)](#performance-and-profiling-optional)
-   [Reducing memory usage 1: Read a file one line at a time
    (optional)](#reducing-memory-usage-1-read-a-file-one-line-at-a-time-optional)
-   [Reducing memory usage 2: Use an SQLite database
    (optional)](#reducing-memory-usage-2-use-an-sqlite-database-optional)
-   [Other optional topics](#other-optional-topics)
-   [Scientific Computing Libraries](#scientific-computing-libraries)
    -   [Downstream libraries](#downstream-libraries)
    -   [Standard library vs. outside
        modules](#standard-library-vs.-outside-modules)
    -   [SciPy project](#scipy-project)
    -   [Statistics](#statistics)
    -   [Machine learning with
        Scikit-Learn](#machine-learning-with-scikit-learn)
    -   [Command-Line Programs](#command-line-programs)
-   [Credits](#credits)
-   [References](#references)
-   [Data Sources](#data-sources)
    -   [Additional data files](#additional-data-files)

# **WEEK 1: Fundamentals**

# Orientation

## What programming language should I use?

1.  Use the language that your friends use (so you can ask them for
    help)
2.  Use a language that has a community of practice for your desired use
    case (you can find documentation, bug reports, sample code, etc.)
3.  Use a language that is \"best\" by some technical definition

## Python is pretty good at lots of things

-   \"Glue\" language intended to replace shell and Perl
-   Concise, readable, good for rapid prototyping
-   Access to linear algebra libraries in FORTRAN/C → user-friendly
    numeric computing

## Literate programming and notebooks

-   Blend code, documentation, and visualization
-   Good for trying things, demos
-   Bad for massive or long-running processes

# Jupyter commands

## How to start Jupyter Lab

### Method 1

1.  Open Anaconda Navigator
2.  Run Jupyter Lab

### Method 2

Open Terminal (MacOS/Linux) or Anaconda Prompt (Windows)

``` bash
cd Desktop/data
jupyter lab
```

## Execute cell with CTRL-Enter; execute cell and move to new cell with Shift-Enter

``` python
3 + 7
```

## Navigation

-   Use drag-and-drop interface to move .ipynb file to new location
-   Rename your notebook to something informative

# Variables and Assignment

## Use variables to store values

Variables are names for values.

``` python
first_name = 'Derek'
age = 42
```

-   can only contain letters, digits, and underscore \_ (typically used
    to separate words in long variable names)
-   cannot start with a digit
-   are case sensitive (`age`, `Age` and `AGE` are three different
    variables)

## Use `print()` to display values

``` python
print(first_name, 'is', age, 'years old')
```

-   Functions are verbs; recognizable by ()
-   Functions take arguments (i.e. do stuff with the values that you
    give them)
-   `print()` useful for tracking progress, debugging
-   NB: Jupyter Lab will always echo the **last** value in a cell, so we
    won\'t need `print()` a lot of the time

## Variables must be created before they are used

``` python
# Prints an informative error message; more about this later
print(last_name)
```

## Variables can be used in calculations

``` python
age = age + 3
print('Age in three years:', age)
```

## Variables only change value when something is assigned to them

``` python
first = 1
second = 5 * first
first = 2
print('first is', first, 'and second is', second)
```

## Use meaningful names!

# Data Types and Type Conversion

## Every value has a type

Most data is text and numbers:

-   Integers: whole numbers (counting)
-   Floats: real numbers (math)
-   Strings: text
-   ...and many others

## Use the built-in function `type()` to find the type of a value

``` python
type(53)
```

``` python
type(3.12)
```

``` python
fitness = 'average'
type(fitness)
```

## Types control what operations can be performed on a given value

``` python
print(5 - 3)
```

``` python
# This will produce an error
print('hello' - 'h')
```

``` python
len('hello')
```

``` python
# This will produce an error
len(5)
```

## Must convert strings to numbers or vice versa when operating on them

Types have different properties; more about this later.

``` python
1 + '2'                         # Produces an error
```

``` python
1 + float('2')
```

## Can mix integers and floats freely in operations

``` python
# This will "do the right thing" and convert everything to floats
1 / 2.0
```

## CHALLENGE: Explain what each operator does

``` python
# Floor
print('5 // 3:', 5 // 3)
# Floating point
print('5 / 3:', 5 / 3)
# Modulus (remainder)
print('5 % 3:', 5 % 3)
```

# Built-in Functions and Help

## Online resources

-   <https://libguides.ucmerced.edu/software-carpentry/python/references>
-   Stack Overflow

## Use comments to add documentation to programs

``` python
# This sentence isn't executed by Python.
adjustment = 0.5   # Neither is this - anything after '#' is ignored.
```

## A function may take zero or more arguments

``` python
print('before')
print()
print('after')
```

## Every function returns *something*

``` python
result = len("hello")
print(result)
```

``` python
# printing to the screen is a "side effect" that doesn't produce a useable result
  result = print("hello")
  print(result)
```

## Commonly-used built-in functions include `max()`, `min()`, and `round()`

``` python
max(1, 2, 3)
```

``` python
min('a', 'A', '0')       # 0-9, A-Z, a-z; However, notice they are all strings!
```

## Functions may only work for certain (combinations of) arguments

``` python
max(1, 'a')              # Not a meaningful comparision
```

## Functions may have default values for some arguments

``` python
# By default, we round to the nearest integer
round(3.712)
```

``` python
# You can optionally specify the number of significant digits
round(3.712, 1)
```

## Use the built-in function `help()` to get help for a function

``` python
help(round)
```

-   1 mandatory argument
-   1 optional argument with a default value: `ndigits=None`

## Functions attached to objects are called methods

``` python
my_string = 'Hello world!'

# calling the swapcase method on the my_string object
print(my_string.swapcase())
```

### Methods can be chained together

``` python
print(my_string.isupper())          # Not all the letters are uppercase
print(my_string.upper())            # This capitalizes all the letters

print(my_string.upper().isupper())  # Now all the letters are uppercase
```

### You can view an object\'s attributes (i.e. methods and fields) using `help()` or `dir()`

Some attributes are \"private\"; you\'re not supposed to use these
directly.

``` python
# The short, short version
dir(my_string)

# More verbose help
help(str)
```

## Python reports a syntax error when it can't understand the source of a program

``` python
name = 'Bob
age = = 54
print("Hello world"
```

## Python reports a runtime error when something goes wrong while a program is executing

We have seen some of these already.

## CHALLENGE: What happens when? (optional)

Explain in simple terms the order of operations in the following
program: when does the addition happen, when does the subtraction
happen, when is each function called, etc. What is the final value of
radiance?

``` python
radiance = 1.0
radiance = max(2.1, 2.0 + min(radiance, 1.1 * radiance - 0.5))
```

# Libraries

## Most of the power of a programming language is in its libraries

<https://docs.python.org/3/library/index.html>

## A program must `import` a library module before using it

``` python
import math

print('pi is', math.pi)
print('cos(pi) is', math.cos(math.pi))
```

-   Refer to things from the module as `module-name.thing-name`
-   Python uses \".\" to mean \"part of\" or \"belongs to\".

## Use `help()` to learn about the contents of a library module

``` python
help(math)                      # user friendly
```

``` python
dir(math)                       # brief reminder, not user friendly
```

## Import specific items from a library module to shorten programs.

You want to be careful with this. It\'s safer to keep the namespace.

``` python
from math import cos, pi

print('cos(pi) is', cos(pi))
```

## Create an alias for a library module when importing it to shorten programs

``` python
import math as m

print('cos(pi) is', m.cos(m.pi))
```

## Python has opinions about how to write your programs

``` python
import this
```

## CHALLENGE: Locating the Right Module (optional)

You want to select a random character from a string:

``` python
bases = 'ACTTGCTTGAC'
```

1.  Which standard library module could help you?
    <https://docs.python.org/3/library/>
2.  Which function would you select from that module? Are there
    alternatives?
3.  Try to write a program that uses the function.

### Solution:

You could try the `random` module.

The string has 11 characters, each having a positional index from 0 to
10. You could use either `random.randrange` or `random.randint`
functions to get a random integer between 0 and 10, and then pick out
the character at that position:

``` python
from random import randrange

random_index = randrange(len(bases))
print(bases[random_index])
```

or more compactly:

``` python
from random import randrange

print(bases[randrange(len(bases))])
```

Perhaps you found the random.sample function? It allows for slightly
less typing:

``` python
from random import sample

print(sample(bases, 1)[0])
```

Note that this function returns a list of values. We will learn about
lists in episode 11. There's also other functions you could use, but
with more convoluted code as a result.

# Lists

## A list stores many values in a single structure

``` python
pressures = [0.273, 0.275, 0.277, 0.275, 0.276]
print('pressures:', pressures)
print('length:', len(pressures))
```

## Use an item's index to fetch it from a list

``` python
print('zeroth item of pressures:', pressures[0])
print('fourth item of pressures:', pressures[4])
```

## Indexing beyond the end of the collection is an error

``` python
pressures[20]
```

## Count backwards from the end with negative integers

``` python
# Get the last item in the list
print('last item of pressures:', pressures[-1])
```

## Use a slice to get a subset of the list

The slicing syntax is
`my_list[inclusive_start_position:exclusive_stop_position:optional_step_amount]`

``` python
# Up to, but not including index 3
print('first 3 items of pressures:', pressures[0:3])
```

## Lists' values can be replaced by assigning to them

``` python
pressures[0] = 0.265
print('pressures is now:', pressures)
```

## Appending items to a list lengthens it

``` python
primes = [2, 3, 5]
print('primes is initially:', primes)
primes.append(7)
print('primes has become:', primes)
```

-   `append()` is a *method* of lists. Methods are like functions, but
    they are tied to particular objects.
-   Use `object-name.method-name()` to call methods
-   Deliberately resembles the way we refer to things in a library
-   We will meet other methods of lists as we go along; use `help(list)`
    for a preview.

## Extend is similar to append, but allows you to merge two lists

``` python
teen_primes = [11, 13, 17, 19]
middle_aged_primes = [37, 41, 43, 47]
print('primes is currently:', primes)

primes.extend(teen_primes)
print('primes has now become:', primes)

primes.append(middle_aged_primes)
print('primes has finally become:', primes)
```

## Use del to remove items from a list entirely

``` python
primes = [2, 3, 5, 7, 9]
print('primes before removing last item:', primes)
del primes[4]
print('primes after removing last item:', primes)
```

## Use pop() to remove the last item and assign it to a variable

``` python
p = primes.pop()

print('Last prime in list', p)
print('primes after removing last item:', primes)
```

## The empty list contains no values

Helpful for collecting values

## Lists may contain values of different types

``` python
ages = ['Derek', 42, 'Bill', 24, 'Susan', 37]
print('First name/age pair', ages[0:2])
print("All the ages", ages[0::2])
```

## Strings can be indexed like lists

### Use an index to get a single character from a string

Count from 0

``` python
element = 'carbon'
element[0]
```

### Use a slice to get a substring

``` python
# Up to, but not including 3
element[0:3]
```

### Counting backwards

``` python
element[-1]
```

### Use the built-in function `len()` to find the length of a string

``` python
len('carbon')                   # length is an integer
```

## But! Character strings are immutable

``` python
element[0] = 'C'
```

## Python is full of analogies

-   lists and strings
-   lists and files

## CHALLENGE: From Strings to Lists and Back

Given this Python code:

``` python
print('string to list:', list('tin'))
print('list to string:', ''.join(['g', 'o', 'l', 'd']))
```

And this output:

``` example
string to list: ['t', 'i', 'n']
list to string: gold
```

1.  What does `list('some string')` do?
2.  What does `'-'.join(['x', 'y', 'z'])` generate?
3.  How can you change \"carbon\" to \"Carbon\"?

### Solution

``` python
# Strings are immutable, so you have to create a new string.
# Use the .join() method to join a list of strings into a new string.
new_element = ''.join(['C', element[1:]])

# or
new_element = element.capitalize()
```

# Dictionaries

## Dictionaries are sets of key/value pairs. Instead of being indexed by position, they are indexed by key.

``` python
ages = {'Derek': 42,
        'Bill': 24,
        'Susan': 37}

print(ages['Derek'])
```

## Update dictionaries by assigning a new key/value pair

``` python
ages['Sam'] = 12

print(ages)
```

## Delete an item using del or pop()

``` python
print("Original dictionary", ages)
del ages['Derek']
print("Dictionary after 1st deletion", ages)

derek_age = ages.pop('Derek')
print("Dictionary after 2nd deletion", ages)
print("Returned value", derek_age)

print(ages)
```

## Dictionaries are the natural way to store tree-structured data

``` python
location = {'latitude': [37.28306, 'N'],
            'longitude': [-120.50778, 'W']}

print(location['longitude'][0])
```

## CHALLENGE: Convert lists to dictionary (group)

How can you convert our list of names and ages into a dictionary? Hint:
You will need to populate the dictionary with a list of keys and a list
of values.

``` python
# Starting data
ages = ['Derek', 42, 'Bill', 24, 'Susan', 37]

# Get dictionary help
help({})
```

### Solution

``` python
names_list = ages[0::2]
ages_list = ages[1::2]

ages_dict = dict(zip(names_list, ages_list))
```

# Other containers (optional)

-   Tuples
-   Sets

# **WEEK 2: Data manipulation with Pandas**

# (Optional) Review lists and dictionaries

1.  Reference item by index/key
2.  Insert item by index/key
3.  Indices/keys must be unique

# (Optional) Review strings

1.  Similar to lists: Reference item by index, have length
2.  Immutable, so need to use string **methods**
3.  `'/'.join()` is a very useful method

# Where are we?

## Python provides functions for working with the file system.

``` python
import os

# print current directory
print("Current working directory:", os.getcwd())
# print all of the files and directories
print("Working directory contents:", os.listdir())
```

## (Optional) These provide a rich Python alternative to shell functions

``` python
# Just print the directories
print("Just print the sub-directories:", sorted(next(os.walk('.'))[1]))
```

# Reading Tabular Data into DataFrames

## Use the Pandas library to work on tabular data

``` python
import pandas as pd

data = pd.read_csv('data/gapminder_gdp_oceania.csv')
print(data)
```

``` python
# Jupyter Lab will give you nice formatting if you echo
data
```

-   File and directory names are strings
-   You can use relative or absolute file paths

## Use `index_col` to specify that a column's values should be used as row headings

Rows are indexed by number by default (0, 1, 2,....). For convenience,
we want to index by country:

``` python
data = pd.read_csv('data/gapminder_gdp_oceania.csv', index_col='country')
print(data)
```

-   By default, rows are indexed by position, like lists.
-   Setting the `index_col` parameter lets us index rows by label, like
    dictionaries. For this to work, the index column needs to have
    unique values for every row.
-   You can verify the contents of the CSV by double-clicking on the
    file in Jupyter Lab

## Data frames have methods (i.e. functions) that perform operations using the data frame\'s contents as input

1.  Use `DataFrame.info()` to find out more about a data frame

    ``` python
    data.info()
    ```

2.  Use `DataFrame.describe()` to get summary statistics about data

    ``` python
    data.describe()
    ```

## Data frames have fields (i.e. variables) that hold additional information

A \"field\" is a variable that belongs to an object.

1.  The `DataFrame.columns` field stores information about the
    DataFrame's columns

    ``` python
    data.columns
    ```

2.  The `DataFrame.shape` variable stores the matrix shape

    ``` python
    data.shape
    ```

3.  Use `DataFrame.T` to transpose a DataFrame Does not copy or modify
    the data, just changes the caller\'s view of it.

    ``` python
    data.T
    ```

## Pandas help files are dense; you should prefer the online documentation

<https://pandas.pydata.org/docs/user_guide/index.html>

## Challenge

1.  Read the data in `gapminder_gdp_americas.csv` into a variable called
    `americas` and display its summary statistics.
2.  After reading the data for the Americas, use `help(americas.head)`
    and `help(americas.tail)` to find out what `DataFrame.head` and
    `DataFrame.tail` do.
    1.  How can you display the first three rows of this data?
    2.  How can you display the last three columns of this data? (Hint:
        You may need to change your view of the data).
3.  As well as the `read_csv` function for reading data from a file,
    Pandas provides a `to_csv` function to write DataFrames to files.
    Applying what you've learned about reading from files, write one of
    your DataFrames to a file called `processed.csv`. You can use `help`
    to get information on how to use `to_csv`.

### Solution 1

``` python
americas = pd.read_csv('data/gapminder_gdp_americas.csv', index_col='country')
americas.describe()
```

### Solution 2.1

``` python
americas.head(3)
```

### Solution 2.2

``` python
americas.T.tail(3)
```

### Solution 4

``` python
americas.to_csv('processed.csv')
```

## (Optional) Introspecting on the DataFrame object

``` python
# DataFrames have a huge number of fields and methods, so dir() is not very useful
print(dir(data))
```

``` python
# Create a new list that filters out internal attributes
df_public = [item for item in dir(data) if not item.startswith('_')]
print(df_public)
```

``` python
# Pretty-print the new list; extremely optional
import pprint

pp = pprint.PrettyPrinter(width=100, compact=True, indent=2)
pp.pprint(df_public)
```

Objects have fields (i.e. data/variables) and methods (i.e.
functions/procedures). The difference between a method and a function is
that methods are attached to objects, whereas functions are
free-floating (\"first-class citizens\"). Methods and functions are
\"callable\":

``` python
# Generate a list of public methods and a list of public fields. We do this
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

# Pandas DataFrames

## Notes about Pandas DataFrames/Series

1.  Pandas is a library for working with spreadsheet-like data
    (\"DataFrames\")
2.  A DataFrame is a collection (dict) of Series columns
3.  Each Series is a 1-dimensional NumPy array with optional row labels
    (dict-like, similar to R vectors)
4.  Therefore, each series inherits many of the abilities (linear
    algebra) and limitations (single data type) of NumPy

## (Optional) Pandas introduces some new types

``` python
# DataFrame type
type(data)
type(data.T)

# Index type
type(data.columns)

# Series type
type(data['gdpPercap_1952'])
```

-   You can convert data between NumPy arrays, Series, and DataFrames
-   You can read data into any of the data structures from files or from
    standard Python containers

## Selecting values

1.  Rows have positions \[i, j, ..\] and labels. This gives us two ways
    to access data:

    1.  Treat the DataFrame as a matrix and select values using linear
        algebra operators
    2.  Treat the DataFrame as a table and select values using labels

2.  Use `DataFrame.iloc[..., ...]` to select values by their (entry)
    position. The `i` in `iloc` stands for \"index\".

    ``` python
    import pandas as pd
    data = pd.read_csv('data/gapminder_gdp_europe.csv', index_col='country')

    data.iloc[0,0]
    ```

3.  Use `DataFrame.loc[..., ...]` to select values by their label

    ``` python
    data.loc["Albania", "gdpPercap_1952"]
    ```

4.  Use `:` on its own to mean all columns or all rows. This is Python's
    usual slicing notation, which allows you to treat DataFrames as
    multi-dimensional lists (unlike R, Python requires you to explicitly
    ask for all rows or columns).

    ``` python
    data.loc["Albania", :]
    ```

5.  Select multiple columns or rows using `DataFrame.loc` and a named
    slice. This generalizes the concept of a slice to include labeled
    indexes:

    ``` python
    data.loc['Italy':'Poland', 'gdpPercap_1962':'gdpPercap_1972']
    ```

6.  `DataFrame.iloc` follows list index conventions (\"up to, but not
    including)\", but `DataFrame.loc` does the intuitive right thing
    (\"A through B\"):

    1.  List index is up to, but not including, the 2nd position:

        ``` python
        data.iloc[0:2, 0:2]
        ```

    2.  Label index includes the 2nd position:

        ``` python
        data.loc["Albania":"Belgium", "gdpPercap_1952":"gdpPercap_1962"]
        ```

7.  A DataFrame is a spreadsheet, but it is also a dictionary of
    columns.

    ``` python
    data['gdpPercap_1962']
    ```

## Result of slicing can be used in further operations

Any operation that you can use on the whole data frame can be used on a
slice (because a slice is also a data frame):

``` python
print(data.loc['Italy':'Poland', 'gdpPercap_1962':'gdpPercap_1972'].max())

print(data.loc['Italy':'Poland', 'gdpPercap_1962':'gdpPercap_1972'].min())

data.loc['Italy':'Poland', 'gdpPercap_1962':'gdpPercap_1972'].describe()
```

## Use comparisons to select data based on value

``` python
subset = data.loc['Italy':'Poland', 'gdpPercap_1962':'gdpPercap_1972']
```

1.  Show which data frame elements match a criterion

    ``` python
    # Which GDPs are greater than 10,000?
    subset > 10000
    ```

2.  Use the criterion match to filter the data frame\'s contents. This
    uses index notation:

    ``` python
    subset[subset > 10000]
    ```

3.  Alternatively, use the data frame\'s `where()` method to find
    elements that match the criterion:

    ``` python
    subset.where(subset > 10000)
    ```

## Use method chaining to create final output without creating intermediate variables

1.  Verbose code with intermediate variables

    ``` python
    filtered_subset = subset.where(subset > 10000)
    filtered_subset.describe()
    ```

2.  Method chaining is the idiomatic Python equivalent of R Tidyverse
    pipes

    ``` python
    subset.where(subset > 10000).describe()
    ```

3.  (Optional) An example of a longer processing pipeline

    ``` python
    # The rank() method turns numerical scores into ranks, e.g.:
    subset.rank()

    # Are ranks correlated across time?
    data.rank().corr("kendall")

    # Are ranks correlated across time for higher-income countries?
    data.where(data > data.median()).rank().corr("kendall")
    ```

## (Optional) DataFrame methods have sensible defaults that you can change

``` python
help(subset.min)
```

The \"See Also\" section has some helpful suggestions for related
methods

1.  Operations run on columns (Series) by default

    ``` python
    subset.min()
    subset.min(axis=0)
    ```

2.  To evaluate across rows, set axis=1

    ``` python
    subset.min(axis=1)
    ```

3.  NaNs are ignored by numerical operations like max, min, average,
    etc.

    ``` python
    # Column means
    subset.where(subset > 10000).mean()

    # Row means
    subset.where(subset > 10000).mean(1)

    # Row means, if no missing data
    subset.where(subset > 10000).mean(1, skipna=False)
    ```

## (Optional) Truth value of whole data frames

``` python
fs = subset.where(subset > 10000)

# Show which items are NaN
fs.isna()

# Inspect each column: Are any values True?
fs.isna().any()

# Inspect each column: Are all of the values True?
fs.isna().all()
```

-   Series and DataFrame have the binary comparison methods `eq`, `ne`,
    `lt`, `gt`, `le`, and `ge`
-   You can apply the reductions: `empty`, `any()`, `all()`, and
    `bool()` to provide a way to summarize a boolean result

## (Carpentries version) Group By: split-apply-combine

1.  Split data according to criterion, do numeric transformations, then
    recombine.

    ``` python
    # Get all GDPs greater than the mean
    mask_higher = data > data.mean()

    # Count the number of time periods in which each country exceeds the mean
    higher_count = mask_higher.aggregate('sum', axis=1)

    # Create a normalized wealth-over-time score
    wealth_score = higher_count / len(data.columns)
    wealth_score
    ```

2.  Add column to data frame

    ``` python
    # Warningealth Score is a series
    type(wealth_score)

    data['normalized_wealth'] = wealth_score
    ```

## Group By: split-apply-combine

-   By "group by" we are referring to a process involving one or more of
    the following steps:
    1.  Splitting the data into groups based on some criteria
    2.  Applying a function to each group independently
    3.  Combining the results into a data structure
-   Examples include:
    1.  Aggregation (e.g., group counts)
    2.  Transformation (e.g., Z scores)
    3.  Filtration (e.g., discard outliers)

### Z score example

``` python
# Calculate z scores for all elements
z = (data - data.mean())/data.std()

# Get the mean z score for each country
mean_z = z.mean(axis=1)

# Group countries into "wealthy" (z > 0) and "not wealthy" (z <= 0)
z_bool = mean_z > 0

# Append new columns to DataFrame
data["mean_z"] = mean_z
data["wealthy"] = z_bool

# Get descriptive statistics for the group
data.groupby("wealthy").mean()
```

### Write new file with `to_csv()`

Capture the results of your filter in a new file, rather than
overwriting your original data.

``` python
# Save to a new CSV, preserving your original data
data.to_csv('gapminder_gdp_europe_normed.csv')
```

## (Optional) Adding rows to DataFrames

A row is a view onto the *nth* item of each of the column Series.
Appending rows is a performance bottleneck because it requires a
separate append operation for each Series. Where possible, concatenate
DataFrames instead.( cf.
<https://twitter.com/ryxcommar/status/1339752918648545281>)

``` python
# Concatenate multiple DataFrames vertically
pd.concat([df1, df2, df3])

# Generic append requires labels to get data into correct rows
df.append({'a': 3, 'b': 4}, ignore_index=True)
```

## (Carpentries) Challenge

1.  Calculate Z score for each data point
2.  Calculate the mean Z score for each country
3.  Add it as a new column

# **WEEK 3: Visualization with Matplotlib and Seaborn**

# Graphs

Fundamentally, graphs communicate two types of information:

1.  Relationships or trends among data
2.  The distribution of data

## Big 5 graphs

1.  Line plot
2.  Scatter plot
3.  Bar plot
4.  Histogram
5.  Box plot

# Plotting with Matplotlib

## Create a basic plot

``` python
import matplotlib.pyplot as plt
fig, ax = plt.subplots()

time = [0, 1, 2, 3]
position = [0, 100, 200, 300]

ax.plot(time, postion)

fig
```

## Two kinds of plotting objects

``` python
print(type(fig))
print(type(ax))
```

-   Figure objects handle display, printing, saving, etc.
-   Axes objects contain graph information

## Three ways of showing a figure (optional)

1.  Show figure inline (Jupyter Lab default)

    ``` python
    fig
    ```

2.  Show figure in a separate window (command line default)

    ``` python
    fig.show()
    ```

3.  Show figure in a separate window from Jupyter Lab. You may need to
    specify a different \"backend\" parameter for `matplotlib.use()`
    depending on your exact setup:
    <https://matplotlib.org/stable/tutorials/introductory/usage.html#the-builtin-backends>

    ``` python
    import matplotlib

    matplotlib.use('TkAgg')

    fig.show()
    ```

## Line Plots

1.  Create mock data

    ``` python
    import numpy as np

    y = np.random.random(10) # outputs an array of 10 random numbers between 0 and 1
    x = np.arange(1980,1990,1) # generates an ordered array of numbers from 1980 to 1989

    # Check that x and y contain the same number of values
    assert len(x) == len(y)

    # Turn y into a percentage
    y = y*100
    ```

2.  Create the basic plot

    ``` python
    fig, ax = plt.subplots()
    ax.plot(x, y)
    ```

3.  Show available styles (What is the local equivalent of this global
    command?)

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

4.  Add figure information In principle, nearly every element on a
    Matplotlib figure is independently modifiable.

    ``` python
    # modify figure size, axes and fonts
    fig, ax = plt.subplots(figsize=(8,6)) #(width, height) inches
    ax.plot(x, y, color='darkorange', linewidth=2, marker='o')

    # add title and axes label, adjust font size and style

    ax.set_title("Percent Change in Stock X", fontsize=22, fontweight='bold')
    ax.set_xlabel(" Years ", fontsize=20, fontweight='bold')
    ax.set_ylabel(" % change ", fontsize=20, fontweight='bold')

    # adjust tick labels
    ax.tick_params(axis='both', which='major', labelsize=18)

    # add a grid
    ax.grid(True)
    ```

5.  What is an object? Objects encapsulate behaviors

    -   Lists, dictionaries, and DataFrames are collections of data
    -   Objects are collections of data and functions

6.  Matplotlib object syntax

    -   The `object.set_field(value)` usage is taken from Java, which
        was popular in 2003 when Matplotlib was developing its
        object-oriented syntax
    -   You get values back out with `object.get_field(value)`
    -   The Pythonic way to set a value would be `object.field = value`.
        However, the Matplotlib getters and setters do a lot of internal
        bookkeeping, so if you try to set field values directly you will
        get errors. For example, compare `ax.get_ylabel()` with
        `ax.yaxis.label`.
    -   Read \"The Lifecycle of a Plot\":
        <https://matplotlib.org/stable/tutorials/introductory/lifecycle.html>
    -   Read \"Why you hate Matplotlib\":
        <https://ryxcommar.com/2020/04/11/why-you-hate-matplotlib/>

7.  Save your figure

    ``` python
    fig.savefig("mygraph_dark.png", dpi=300, bbox_inches='tight')
    ```

## Explore your data with Pandas

1.  Import data

    ``` python
    import pandas as pd

    data = pd.read_csv('data/gapminder_gdp_europe.csv', index_col='country')
    ```

2.  Transform column headers into an ordinal scale

    1.  Original column names are object (i.e. string) data

        ``` python
        data.columns
        ```

    2.  Pull out integer portion of strings

        ``` python
        years = data.columns.str.strip('gdpPercap_')
        years
        ```

    3.  Convert the years columns into integer years and replace
        DataFrame column headers

        ``` python
        data.columns = years.astype(int)
        data.columns
        ```

3.  Plot directly with Pandas

    ``` python
    data.loc['Austria'].plot()
    ```

## Plot directly from Pandas (optional)

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

3.  The equivalent Matplotlib plot (optional)

    ``` python
    # extract the x and y values from dataframe
    x_years = data.columns
    y_gdp = data.loc['Austria']

    # Create the plot
    fig, ax = plt.subplots(figsize=(8,6))
    ax.plot(x_years, y_gdp, color='darkgreen', linewidth=2, marker='x')
    # etc.
    ```

## Plotting multiple data sets

### Extract values from the DataFrame

``` python
x_years = data.columns
y_austria = data.loc['Austria']
y_bulgaria = data.loc['Bulgaria']
```

### Create the plot object

``` python
# Create the plot
fig, ax = plt.subplots(figsize=(8,6))
ax.plot(x_years, y_austria, label='Austria', color='darkgreen', linewidth=2, marker='x')
ax.plot(x_years, y_bulgaria, label='Bulgaria', color='maroon', linewidth=2, marker='o')

# Decorate the plot
ax.legend(fontsize=16, loc='upper center') # Uses labels
ax.set_title("GDP of Austria vs Bulgaria", fontsize=22, fontweight='bold')
ax.set_xlabel("Years",fontsize=20, fontweight='bold' )
ax.set_ylabel("GDP",fontsize=20, fontweight='bold' )
```

### There are many kinds of plots

``` python
plt.style.use('ggplot')

# Create a scatter plot
fig, ax = plt.subplots(figsize=(8,6))
ax.scatter(y_austria, y_bulgaria, color='blue', linewidth=2, marker='o')

# Decorate the plot
ax.set_title("GDP of Austria vs Bulgaria", fontsize=22, fontweight='bold')
ax.set_xlabel("GDP of Austria",fontsize=20, fontweight='bold' )
ax.set_ylabel("GDP of Bulgaria",fontsize=20, fontweight='bold' )
```

### Overlaying multiple plots on the same figure with Pandas (optional)

This is super unintuitive.

``` python
# Create an Axes object with the Austria data
ax = data.loc['Austria'].plot(figsize=(8,6), color='darkgreen', linewidth=2, marker='*')
print("Austria graph", id(ax))

# Overlay the Bulgaria data on the same Axes object
ax = data.loc['Bulgaria'].plot(color='maroon', linewidth=2, marker='o')
print("Bulgaria graph", id(ax))
```

# Seaborn: Pythonic, high-level pre-sets for Matplotlib

## A simple plot

``` python
# Import the Seaborn library
import seaborn as sns
ax = sns.lineplot(data=data.T, legend=False)
```

-   Doing more with this data set requires transforming the data from
    wide form to long form; see
    <https://seaborn.pydata.org/tutorial/data_structure.html>

## Import the Iris data set

<https://gist.githubusercontent.com/curran/a08a1080b88344b0c8a7/raw/0e7a9b0a5d22642a06d3d5b9bcbad9890c8ee534/iris.csv>

``` python
iris = pd.read_csv("data/iris.csv")
iris.head()
```

## Scatter Plot

``` python
# Reset the style
plt.style.use("dark_background")
plt.rcParams["axes.grid"] = False

# Create the plot
ax = sns.scatterplot(data=iris, x='sepal_length',y='petal_length')
```

### Change plotting theme

``` python
# Make everything visible at a distance
sns.set_context('poster')

# Color by species
ax = sns.scatterplot(data=iris, x='sepal_length', y='petal_length', hue='species', palette='colorblind')

# Set the figure size
fig = ax.get_figure()
fig.set_size_inches(8,6)
```

### Add styling to data points

``` python
# Color by species
ax = sns.scatterplot(data=iris, x='sepal_length', y='petal_length', hue='species', palette='colorblind', style='species')

# Set the figure size
fig = ax.get_figure()
fig.set_size_inches(8,6)
```

### Prettify column names (optional)

``` python
words = [' '.join(i) for i in iris.columns.str.split('_')]
iris.columns = words
```

### Bubble Plot

``` python
# Color by species, size by petal width
ax = sns.scatterplot(data=iris, x='sepal_length', y='petal_length',
                     hue='species', palette='colorblind', size='petal_width')

# (horizontal direction, vertical alignment) of legend
ax.legend(bbox_to_anchor=(1, 1))

# Set the figure size
fig = ax.get_figure()
fig.set_size_inches(8,6)
```

### Regression Plot (optional)

``` python
# Color by species, size by petal width
ax = sns.regplot(data=iris, x='sepal_length', y='petal_length', scatter=True,
                 scatter_kws={'color':'white'})
```

## Bar Charts

### Count Plot counts the records in each category

``` python
ax = sns.countplot(data=iris, x='species', palette='colorblind')
```

### Bar Plot

Default summary statistic is mean, and default error bars are 95%
confidence interval.

``` python
ax = sns.barplot(data=iris, x='species', y='sepal_width', palette='colorblind')
```

### Bar Plot with custom parameters

``` python
# Error bars show standard deviation
ax = sns.barplot(data=iris, x='species', y='sepal_width', ci='sd', edgecolor='black')
```

``` python
# Estimator shows category sum
ax = sns.barplot(data=iris, x='species', y='sepal_width', ci='sd', estimator=np.sum, edgecolor='black')
```

## Histograms

### Histogram of overall data set

``` python
ax = sns.histplot(data=iris, x='petal_length', kde=True)
```

-   KDE: If True, compute a kernel density estimate to smooth the
    distribution and show on the plot as (one or more) line(s).
-   There seems a bimodal distribution of petal length. What factors
    underly this distribution?

### Histogram of data decomposed by category

``` python
ax = sns.histplot(data=iris, x='petal_length', hue='species', palette='Set2')
```

### Selecting number of bins

``` python
# This generates 3 subplots (ncols=3) on the same figure
fig, axes = plt.subplots(figsize=(12,4), nrows=1, ncols=3)
sns.histplot(data=iris,x='petal_length', bins=5, ax=axes[0], color='#f5a142') #  #f5a142 is a hex color
sns.histplot(data=iris,x='petal_length', bins=10, ax=axes[1], color='maroon')
sns.histplot(data=iris,x='petal_length', bins=15, ax=axes[2], color='darkmagenta')
```

## Box Plots and Swarm Plots

### Basic box plot

``` python
ax = sns.boxplot(data=iris, x='species', y='petal_length')
```

### Overlap swarm plot

``` python
ax = sns.boxplot(data=iris, x='species', y='petal_length')
sns.swarmplot(data=iris, x='species', y='petal_length', ax=ax, color='black')
```

### Swarm plot only

``` python
ax = sns.swarmplot(data=iris,x='species', y='petal_length', hue='species', palette='Set1')
ax.legend(loc='upper left', fontsize=16)
ax.tick_params(axis='x', labelrotation = 45)
```

## Heat Map

# Seaborn 0.11 new features: <https://seaborn.pydata.org/whatsnew.html>

# Looping through datasets

``` python
# Saving datasets with new-style string formatting
for i in datasets_list:
   plt.savefig(f'{i}.png',....)
```

# **WEEK 4: Building Programs**

# For Loops

## A `for` loop executes commands once for each value in a collection

\"For each thing in this group, do these operations\"

``` python
for number in [2, 3, 5]:
    print(number)
```

-   A for loop is made up of a collection, a loop variable, and a body
-   The collection, **\[2, 3, 5\]**, is what the loop is being run on.
-   The body, **print(number)**, specifies what to do for each value in
    the collection.
-   The loop variable, **number**, is what changes for each iteration of
    the loop (i.e. the "current thing")

## The first line of the `for` loop must end with a colon, and the body must be indented

1.  This produces an error

    ``` python
    for number in [2, 3, 5]:
    print(number)
    ```

2.  So does this

    ``` python
    firstName = "Jon"
        lastName = "Smith"
    ```

## Loop variables can be called anything

``` python
for kitten in [2, 3, 5]:
    print(kitten)
```

-   It\'s just a placeholder

## The body of a loop can contain many statements

``` python
primes = [2, 3, 5]
for p in primes:
    squared = p ** 2
    cubed = p ** 3
    print(p, squared, cubed)
```

## Use `range()` to iterate over a sequence of numbers

``` python
for number in range(0, 3):
    print(number)
```

-   range() produces numbers on demand (a \"generator\" function)
-   useful for tracking progress

## Use `enumerate()` to iterate over a sequence of items and their positions

``` python
for number, p in enumerate(primes):
    print("Item number:", number)
    print("Prime:", p)
```

## The Accumulator pattern turns many values into one

1.  General approach

    1.  Initialize an accumulator variable to zero, the empty string, or
        the empty list.
    2.  Update the variable with values from a collection.

2.  Reduce a collection to single value

    ``` python
    # Sum the first 10 integers.
    total = 0
    for number in range(1, 11):
       total = total + number
    print(total)
    ```

3.  Create a new collection from an existing collection

    ``` python
    # Sum the first 10 integers.
    prime_exponents = []
    for p in primes:
       prime_exponents.append(p**2)
    print(prime_exponents)
    ```

## Dictionary iteration

``` python
ages = {'Derek': 42,
        'Bill': 24,
        'Susan': 37}

# Iterate over key: value pairs
for key, val in ages.items():
    print(key, val)

# Iterate over keys; you can also explicitly call keys()
for key in ages:
    print(key)

# Iterate over values
for val in ages.values():
    print(val)
```

``` python
location = {'latitude': [37.28306, 'N'],
            'longitude': [-120.50778, 'W']}

for key, val in location.items():
    print(key, 'is', val[0], val[1])
```

## How do you know if an object is iterable? (optional)

1.  Lists, dictionaries, and strings are iterable

    ``` python
    hasattr(location, "__iter__")
    ```

2.  Integers are not iterable

    ``` python
    hasattr(5, "__iter__")
    ```

## Don\'t use `for` loops with DataFrames or Numpy matrices

There is almost always a faster, more idiomatic one-line function that
does what you want

# Conditionals

## Use `if` statements to control whether or not a block of code is executed

An `if` statement (more properly called a conditional statement)
controls whether some block of code is executed or not.

``` python
mass = 3.54
if mass > 3.0:
    print(mass, 'is large')

mass = 2.07
if mass > 3.0:
    print (mass, 'is large')
```

Structure is similar to a `for` statement:

-   First line opens with `if` and ends with a colon
-   Body containing one or more statements is indented (usually by 4
    spaces)

## Conditionals are often used inside loops

Not much point using a conditional when we know the value (as above),
but useful when we have a collection to process.

``` python
masses = [3.54, 2.07, 9.22, 1.86, 1.71]
for m in masses:
    if m > 3.0:
        print(m, 'is large')
```

## Use else to execute a block of code when an if condition is not true

`else` can be used following an `if`. This allows us to specify an
alternative to execute when the if branch isn't taken.

``` python
masses = [3.54, 2.07, 9.22, 1.86, 1.71]
for m in masses:
    if m > 3.0:
        print(m, 'is large')
    else:
        print(m, 'is small')
```

## Use `elif` to specify additional tests

May want to provide several alternative choices, each with its own test;
use `elif` (short for "else if") and a condition to specify these.

``` python
masses = [3.54, 2.07, 9.22, 1.86, 1.71]
for m in masses:
    if m > 9.0:
        print(m, 'is HUGE')
    elif m > 3.0:
        print(m, 'is large')
    else:
        print(m, 'is small')
```

-   Always associated with an `if`.
-   Must come before the `else` (which is the "catch all").

## Conditions are tested once, in order

Python steps through the branches of the conditional in order, testing
each in turn. Order matters! The following is wrong:

``` python
grade = 85
if grade >= 70:
    print('grade is C')
elif grade >= 80:
    print('grade is B')
elif grade >= 90:
    print('grade is A')
```

## Use conditionals in a loop to "evolve" the values of variables

``` python
velocity = 10.0
for i in range(5): # execute the loop 5 times
    print(i, ':', velocity)
    if velocity > 20.0:
        velocity = velocity - 5.0
    else:
        velocity = velocity + 10.0
print('final velocity:', velocity)
```

-   This is how dynamical systems simulations work

## Compound Relations Using `and`, `or`, and Parentheses (optional)

Often, you want some combination of things to be true. You can combine
relations within a conditional using `and` and `or`. Continuing the
example above, suppose you have:

``` python
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
```

-   Use () to group subsets of conditions
-   Aside: For a more natural way of working with many lists, look at
    `zip()`

# Looping Over Data Sets

## File paths as an example of increasing abstraction in program development

1.  File paths as literal strings
2.  File paths as string patterns
3.  File paths as abstract Path objects

## Use a `for` loop to process files given a list of their names

``` python
file_list = ['data/gapminder_gdp_africa.csv', 'data/gapminder_gdp_asia.csv']
for filename in file_list:
    data = pd.read_csv(filename, index_col='country')
    print(filename, data.min())
```

## Use glob.glob to find sets of files whose names match a pattern

``` python
import glob
print('all csv files in data directory:', glob.glob('data/*.csv'))
```

In Unix, the term "globbing" means "matching a set of files with a
pattern". The most common patterns are:

-   \`\*\` meaning "match zero or more characters"
-   \`?\` meaning "match exactly one character"

## Use glob and for to process batches of files

``` python
for filename in glob.glob('data/gapminder_*.csv'):
    data = pd.read_csv(filename)
    print(filename, data['gdpPercap_1952'].min())
```

## Use pathlib to write code that works across operating systems (optional)

``` python
from pathlib import Path

relative_path = Path("data")
print("Absolute path:", relative_path.absolute()) # This is autogenerated, even if "data" doesn't exist

if relative_path.exists():
    for filename in relative_path.glob('gapminder_*.csv'):
        if filename.is_file():
            data = pd.read_csv(filename)
            print(filename, data['gdpPercap_1952'].min())
```

-   Note the careful testing at each level of the code

## CHALLENGE: Comparing data (optional) (rewrite)

Write a program that reads in the regional data sets and plots the
average GDP per capita for each region over time in a single chart.

Solution:

``` python
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
```

# Writing Functions

## Break programs down into functions to make them easier to understand

-   Human beings can only keep a few items in working memory at a time.
-   Understand larger/more complicated ideas by understanding and
    combining pieces
-   Functions serve the same purpose in programs:
    1.  Encapsulate complexity so that we can treat it as a single
        "thing"
    2.  Removes complexity from remaining code, making it easier to test
    3.  Enables re-use: Write one time, use many times

## Define a function using `def` with a name, parameters, and a block of code

``` python
def print_greeting():
    print('Hello!')
```

-   Begin the definition of a new function with `def`, followed by the
    name of the function.
-   Must obey the same rules as variable names.
-   Parameters in parentheses; empty parentheses if the function doesn't
    take any inputs.
-   Indent function body

## Defining a function does not run it

``` python
print_greeting()
```

-   Like assigning a value to a variable
-   Must call the function to execute the code it contains.

## Arguments in call are matched to parameters in definition

1.  Positional arguments

    ``` python
    def print_date(year, month, day):
        joined = '/'.join([year, month, day])
        print(joined)

    print_date(1871, 3, 19)
    ```

2.  Keyword arguments

    ``` python
    print_date(month=3, day=19, year=1871)
    ```

## Functions may return a result to their caller using `return`

1.  Use `return ...` to give a value back to the caller. `return` ends
    the function\'s execution and *returns* you to the code that
    originally called the function.

    ``` python
    def average(values):
        """Return average of values, or None if no values are supplied."""

        if len(values) == 0:
            return None

        # The if statement "falls through" to the second return when values != 0.
        # For maximum clarity, you could add else before the outer return.
        return sum(values) / len(values)
    ```

    ``` python
    a = average([1, 3, 4])
    print('average of actual values:', a)
    ```

2.  You should explicitly handle common problems:

    ``` python
    print('average of empty list:', average([]))
    ```

3.  Every function returns something:

    ``` python
    result = print_date(1871, 3, 19)
    print('result of call is:', result)
    ```

4.  Notes:

    1.  `return` can occur anywhere in the function, but functions are
        easier to understand if return occurs:
        1.  At the start to handle special cases
        2.  At the very end, with a final result
    2.  Docstring provides function help. Use triple quotes if you need
        the docstring to span multiple lines.

## A worked example: The Lorenz attractor

<https://matplotlib.org/stable/gallery/mplot3d/lorenz_attractor.html>

## Use functions to encapsulate large code blocks (optional)

``` python
import pandas as pd
import glob

def norm_data(data):
    """Add a Z score column to each data set."""

    # Calculate z scores for all elements
    z = (data - data.mean())/data.std()

    # Get the mean z score for each country
    mean_z = z.mean(axis=1)

    # Group countries into "wealthy" (z > 0) and "not wealthy" (z <= 0)
    z_bool = mean_z > 0

    # Append to DataFrame
    data["mean_z"] = mean_z
    data["wealthy"] = z_bool

for filename in glob.glob('data/gapminder_*.csv'):
    # Print a status message
    print("Current file:", filename)

    # Read the data into a DataFrame and modify it
    data = pd.read_csv(filename)
    norm_data(data)

    # Generate an output file name
    parts = filename.split(".csv")
    newfile = ''.join([parts[0], "_normed.csv"])
    data.to_csv(newfile)
```

## Using functions with conditionals in Pandas (optional)

``` python
# Apply a function to every row of the selected column
def my_fun(val):
    pass

data = pd.read_csv('data/gapminder_all.csv')
data['new_col'] = data['lifeExp_1952'].apply(my_fun)
```

# Software Logistics

## Python files vs. Notebook files

## Python from the command line

## Updating your Python installation

## Version control

# Variable Scope (optional)

# Programming Style (optional)

# Working with unstructured files (optional)

## Open the file with a context handler

``` python
with open('pettigrew_letters_ORIGINAL.txt', 'r') as file_in:
    text = file_in.read()

print(len(text))
```

## Strings contain formatting marks

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

## Many ways of handling a file

### `.read()` produces the file contents as one string

``` python
type(text)
```

### `.readlines()` produces the file contents as a list of lines; each line is a string

``` python
with open('pettigrew_letters_ORIGINAL.txt', 'r') as file_in:
    text = file_in.readlines()

print(len(text))
print(type(text))
```

### Inspect parts of the file using list syntax

``` python
# View the first 10 lines
text[:10]
```

## Working with unstructured file data

### Contents of pettigrew_letters_ORIGINAL.txt

1.  Intro material
2.  Manifest of letters
3.  Individual letters

### Query: Are all the letters in the manifest actually there?

1.  check if all the letters reported in the manifest appear in the
    actual file
2.  check if all the letters in the file are reported in the manifest
3.  Therefore, construct two variables: (1) A list of every location
    line from the manifest, and (2) a list of every location line within
    the file proper

### Get the manifest by visual inspection

``` python
manifest_list = text[14:159]
```

### Use string functions to clean up and inspect text

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

### Gather all the locations in the full document

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

-   Before automate everything, we run the code with lots of `print()`
    statements so that we can see what\'s happening

### Collect the positive results

``` python
letter_locations = []

for line in letters:
    stripped_line = line.strip()
    is_box = stripped_line.startswith("Box ")
    if is_box == True:
        letter_locations.append(stripped_line)
```

### Compare the manifest and the letters

``` python
print('Items in manifest:', len(manifest_list))
print('Letters:', len(letter_locations))
```

### Follow-up questions

1.  Which items are in one list but not the other?
2.  Are there other structural regularities you could use to parse the
    data? (Note that in the letters, sometimes there are multiple
    letters under a single box header)

# Exception handling (optional)

Explicitly handle common errors, rather than waiting for your code to
blow up.

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

-   Use judiciously, and be as specific as possible. When in doubt,
    allow your code to blow up rather than silently commit errors.

# Performance and profiling (optional)

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

# Reducing memory usage 1: Read a file one line at a time (optional)

``` python
with open('pettigrew_letters_ORIGINAL.txt', 'r') as file_in:
    for line in file_in:
        # Do stuff to current line
        pass
```

# Reducing memory usage 2: Use an SQLite database (optional)

``` python
import sqlite3

conn = sqlite3.connect('my_database_name.db')
with conn:
    c = conn.execute("SELECT column_name FROM table_name WHERE criterion")
    results = c.fetchall()
    c.close

# Do stuff with `results`
```

# Other optional topics

-   Checking performance
-   List comprehensions
-   Defensive programming
-   Debugging and Testing

# Scientific Computing Libraries

## Downstream libraries

1.  Seaborn: Pythonic graphs built on Matplotlib
2.  Statsmodels: Statistical models and formulae built on Scipy.stats
    <https://www.statsmodels.org/stable/index.html>
3.  Scikit-Learn: Machine learning tools built on NumPy, SciPy, and
    Matplotlib <https://scikit-learn.org/stable/>
4.  ...and many more: <https://www.scipy.org/topical-software.html>

## Standard library vs. outside modules

1.  Install with conda package manager
2.  Install with pip

## SciPy project

1.  NumPy: matrix algebra
2.  Pandas: data filtering and transformation; factors
3.  Matplotlib: graphs
4.  Scipy.stats: probability distributions, basic tests
    <https://docs.scipy.org/doc/scipy/reference/stats.html>

## Statistics

### Libraries

1.  statistics Basic summary statistics. Part of the Python standard
    library.
2.  scipy.stats Descriptive statistics and distributions:
    <https://docs.scipy.org/doc/scipy/reference/stats.html>
3.  statsmodels Statistical models and tests. Incorporates scipy.stats.
    <https://www.statsmodels.org/stable/index.html>

### Regression example

#### Sample file

Download \"surveys.csv\" from
<https://figshare.com/articles/Portal_Project_Teaching_Database/1314459>
Direct download link: <https://ndownloader.figshare.com/files/10717177>

#### Import data

``` python
data = pd.read_csv('surveys.csv')

# Check for NaN
print("Valid weights:", data['weight'].count())
print("NaN weights:", data['weight'].isna().sum())
print("Valid lengths:", data['hindfoot_length'].count())
print("NaN lengths:", data['hindfoot_length'].isna().sum())
```

#### Fit OLS regression model

``` python
from statsmodels.formula.api import ols

model = ols("weight ~ hindfoot_length", data, missing='drop').fit()
print(model.summary())
```

#### Generic parameters for all models

``` python
import statsmodels

help(statsmodels.base.model.Model)
```

## Machine learning with Scikit-Learn

<https://scikit-learn.org/stable/>

### Which estimator?

<https://scikit-learn.org/stable/tutorial/machine_learning_map/index.html>
<https://scikit-learn.org/stable/_static/ml_map.png>

### Editorial comments about ML

1.  We already have statistics, so do the reading
2.  Talk to a domain expert
3.  Beware parameter mining
4.  Treat all software as beta software

## Command-Line Programs

Batch processing from command line, .py files, and editors

``` bash
python my_program.py
```

# Credits

-   Plotting and Programming in Python (Pandas-oriented):
    <http://swcarpentry.github.io/python-novice-gapminder/>
-   Programming with Python (NumPy-oriented):
    <https://swcarpentry.github.io/python-novice-inflammation/index.html>
-   Humanities Python Tour (file and text processing):
    <https://github.com/elliewix/humanities-python-tour/blob/master/Two-Hour-Beginner-Tour.ipynb>
-   Introduction to Cultural Analytics & Python:
    <https://melaniewalsh.github.io/Intro-Cultural-Analytics/welcome.html>
-   Rhondene Wint: Matplotlib and Seaborn notes

# References

-   Complete tutorial: <https://docs.python.org/3/tutorial/index.html>
-   String formatting: <https://pyformat.info/>
-   Python standard library: <https://docs.python.org/3/library/>
-   Pandas documentation:
    <https://pandas.pydata.org/pandas-docs/stable/>
-   Pandas user guide:
    <https://pandas.pydata.org/docs/user_guide/index.html>
-   Statistics in Python tutorial:
    <https://scipy-lectures.org/packages/statistics/>
-   Statsmodels library: <https://www.statsmodels.org/stable/index.html>
-   Seaborn gallery of examples:
    <https://seaborn.pydata.org/examples/index.html>
-   Matplotlib gallery of examples:
    <https://matplotlib.org/gallery/index.html>

# Data Sources

## Additional data files

1.  Gapminder data:
    <http://swcarpentry.github.io/python-novice-gapminder/files/python-novice-gapminder-data.zip>
2.  Ecology data (field surveys):
    <https://datacarpentry.org/python-ecology-lesson/data/portal-teachingdb-master.zip>
3.  Social Science data (SAFI):
    <https://datacarpentry.org/socialsci-workshop/data/>
4.  Humanities data (Pettigrew letters):
    <http://dx.doi.org/10.5334/data.1335350291>
