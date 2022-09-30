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
    -   [Navigation](#navigation)
    -   [Writing code](#writing-code)
-   [Variables and Assignment](#variables-and-assignment)
    -   [Use variables to store values](#use-variables-to-store-values)
    -   [Rules for naming things](#rules-for-naming-things)
    -   [Use `print()` to display values](#use-print-to-display-values)
    -   [Jupyter Lab will always echo the last value in a
        cell](#jupyter-lab-will-always-echo-the-last-value-in-a-cell)
    -   [(Optional) Variables must be created before they are
        used](#optional-variables-must-be-created-before-they-are-used)
    -   [Variables can be used in
        calculations](#variables-can-be-used-in-calculations)
    -   [Variables only change value when something is assigned to
        them](#variables-only-change-value-when-something-is-assigned-to-them)
-   [Data Types and Type Conversion](#data-types-and-type-conversion)
    -   [Every value has a type](#every-value-has-a-type)
    -   [The type determine what operations you can perform with a given
        value](#the-type-determine-what-operations-you-can-perform-with-a-given-value)
    -   [Use the built-in function `type()` to find the type of a
        value](#use-the-built-in-function-type-to-find-the-type-of-a-value)
    -   [You can explicitly convert data to a different
        type](#you-can-explicitly-convert-data-to-a-different-type)
    -   [Challenge: Explain what each operator
        does](#challenge-explain-what-each-operator-does)
-   [Built-in Functions and Help](#built-in-functions-and-help)
    -   [How do we find out what\'s
        possible?](#how-do-we-find-out-whats-possible)
    -   [(Optional) Use comments to add documentation to
        programs](#optional-use-comments-to-add-documentation-to-programs)
    -   [A function may take zero or more
        arguments](#a-function-may-take-zero-or-more-arguments)
    -   [Every function returns
        something](#every-function-returns-something)
    -   [Functions can have optional
        parameters](#functions-can-have-optional-parameters)
    -   [Use the built-in function `help()` to get help for a
        function](#use-the-built-in-function-help-to-get-help-for-a-function)
    -   [(Optional) Functions will typically generalize in sensible
        ways](#optional-functions-will-typically-generalize-in-sensible-ways)
    -   [*Methods* are functions that belong to
        objects](#methods-are-functions-that-belong-to-objects)
    -   [(Optional) Python produces informative error
        messages](#optional-python-produces-informative-error-messages)
    -   [(Optional) Challenge: What happens
        when?](#optional-challenge-what-happens-when)
-   [Libraries](#libraries)
    -   [Most of the power of a programming language is in its
        libraries](#most-of-the-power-of-a-programming-language-is-in-its-libraries)
    -   [A program must `import` a library module before using
        it](#a-program-must-import-a-library-module-before-using-it)
    -   [Use `help()` to learn about the contents of a library
        module](#use-help-to-learn-about-the-contents-of-a-library-module)
    -   [Import shortcuts](#import-shortcuts)
    -   [Python has opinions about how to write your
        programs](#python-has-opinions-about-how-to-write-your-programs)
-   [Lists](#lists)
    -   [A list stores many values in a single
        structure](#a-list-stores-many-values-in-a-single-structure)
    -   [Lists are indexed by position, counting from
        0](#lists-are-indexed-by-position-counting-from-0)
    -   [You can get a subset of the list by slicing
        it](#you-can-get-a-subset-of-the-list-by-slicing-it)
    -   [Why are lists indexed from 0?](#why-are-lists-indexed-from-0)
    -   [Some other properties of
        indexes](#some-other-properties-of-indexes)
    -   [Lists are mutable](#lists-are-mutable)
    -   [Many functions take collections as
        arguments](#many-functions-take-collections-as-arguments)
    -   [(Optional) Removing items from a
        list](#optional-removing-items-from-a-list)
    -   [Lists can contain anything](#lists-can-contain-anything)
-   [Strings are (kind of) like lists](#strings-are-kind-of-like-lists)
    -   [Strings are indexed like
        lists](#strings-are-indexed-like-lists)
    -   [(Optional) Strings have a
        length](#optional-strings-have-a-length)
    -   [But! Strings are immutable](#but-strings-are-immutable)
    -   [Building strings with `.join()`](#building-strings-with-.join)
    -   [(Optional) Challenge: From Strings to Lists and
        Back](#optional-challenge-from-strings-to-lists-and-back)
    -   [(Optional) Challenge: Locating the right
        module](#optional-challenge-locating-the-right-module)
-   [Dictionaries](#dictionaries)
    -   [Dictionaries are sets of key/value pairs. Instead of being
        indexed by position, they are indexed by
        key.](#dictionaries-are-sets-of-keyvalue-pairs.-instead-of-being-indexed-by-position-they-are-indexed-by-key.)
    -   [Update dictionaries by assigning a key/value
        pair](#update-dictionaries-by-assigning-a-keyvalue-pair)
    -   [(Optional) Check whether the dictionary contains an
        item](#optional-check-whether-the-dictionary-contains-an-item)
    -   [(Optional) Delete an item using `del` or
        `pop()`](#optional-delete-an-item-using-del-or-pop)
    -   [Dictionaries are the natural way to store tree-structured
        data](#dictionaries-are-the-natural-way-to-store-tree-structured-data)
    -   [Challenge: Convert a list to a
        dictionary](#challenge-convert-a-list-to-a-dictionary)
-   [(Optional) Other containers](#optional-other-containers)
-   [**WEEK 2: Data manipulation with
    Pandas**](#week-2-data-manipulation-with-pandas)
-   [(Optional) Review collections](#optional-review-collections)
    -   [Lists and dictionaries](#lists-and-dictionaries)
    -   [Strings](#strings)
-   [A very brief introduction to
    NumPy](#a-very-brief-introduction-to-numpy)
-   [A very brief introduction to
    Pandas](#a-very-brief-introduction-to-pandas)
-   [(Optional) Where are we?](#optional-where-are-we)
    -   [Python provides functions for working with the file
        system.](#python-provides-functions-for-working-with-the-file-system.)
    -   [These provide a rich Python alternative to shell
        functions](#these-provide-a-rich-python-alternative-to-shell-functions)
-   [Reading tabular data into data
    frames](#reading-tabular-data-into-data-frames)
    -   [Import tabular data using the Pandas
        library](#import-tabular-data-using-the-pandas-library)
    -   [Use `index_col` to use a column's values as row
        indices](#use-index_col-to-use-a-columns-values-as-row-indices)
    -   [Pandas help files are dense; you should prefer the online
        documentation](#pandas-help-files-are-dense-you-should-prefer-the-online-documentation)
-   [Data frames are objects that can tell you about their
    contents](#data-frames-are-objects-that-can-tell-you-about-their-contents)
    -   [Data frames have methods (i.e. functions) that perform
        operations using the data frame\'s contents as
        input](#data-frames-have-methods-i.e.-functions-that-perform-operations-using-the-data-frames-contents-as-input)
    -   [Data frames have fields (i.e. variables) that hold additional
        information](#data-frames-have-fields-i.e.-variables-that-hold-additional-information)
    -   [(Optional) Pandas introduces some new
        types](#optional-pandas-introduces-some-new-types)
    -   [(Optional) Challenge](#optional-challenge)
-   [Subsetting Data](#subsetting-data)
    -   [Treat the data frame as a matrix and select values by
        position](#treat-the-data-frame-as-a-matrix-and-select-values-by-position)
    -   [Treat the data frame as a table and select values by
        label](#treat-the-data-frame-as-a-table-and-select-values-by-label)
    -   [Shorten the column names using vectorized string
        methods](#shorten-the-column-names-using-vectorized-string-methods)
    -   [Use list slicing notation to get subsets of the data
        frame](#use-list-slicing-notation-to-get-subsets-of-the-data-frame)
    -   [Treat the data frame as an object and select values using
        flexible
        methods](#treat-the-data-frame-as-an-object-and-select-values-using-flexible-methods)
-   [Filtering data](#filtering-data)
    -   [Use comparisons to select data based on
        value](#use-comparisons-to-select-data-based-on-value)
    -   [Use method chaining to create final output without creating
        intermediate
        variables](#use-method-chaining-to-create-final-output-without-creating-intermediate-variables)
    -   [Methods we\'re not going to
        cover](#methods-were-not-going-to-cover)
-   [Working with missing data](#working-with-missing-data)
    -   [By default, most numerical operations ignore missing
        data](#by-default-most-numerical-operations-ignore-missing-data)
    -   [Check for missing values](#check-for-missing-values)
    -   [Replace missing values](#replace-missing-values)
    -   [Drop missing values](#drop-missing-values)
-   [Sorting and grouping](#sorting-and-grouping)
    -   [Motivating example: Calculate the wealth Z-score for each
        country](#motivating-example-calculate-the-wealth-z-score-for-each-country)
    -   [Append new columns to the data frame containing our summary
        statistics](#append-new-columns-to-the-data-frame-containing-our-summary-statistics)
    -   [Sort and group by new columns](#sort-and-group-by-new-columns)
-   [Write output](#write-output)
-   [Working with multiple tables (in an SQL-like
    manner)](#working-with-multiple-tables-in-an-sql-like-manner)
    -   [Concatenating data frames](#concatenating-data-frames)
    -   [Joining data frames](#joining-data-frames)
-   [Scientific Computing Libraries](#scientific-computing-libraries)
    -   [(Optional) Statsmodels regression
        example](#optional-statsmodels-regression-example)
    -   [(Optional) Getting started with machine learning
        estimators](#optional-getting-started-with-machine-learning-estimators)
-   [(Optional) Things we didn\'t talk
    about](#optional-things-we-didnt-talk-about)
-   [(Optional) Adding rows to
    DataFrames](#optional-adding-rows-to-dataframes)
-   [(Optional) Pandas method chaining in the
    wild](#optional-pandas-method-chaining-in-the-wild)
-   [(Optional) Introspecting on the DataFrame
    object](#optional-introspecting-on-the-dataframe-object)
-   [(Carpentries version) Group By:
    split-apply-combine](#carpentries-version-group-by-split-apply-combine)
-   [**WEEK 3: Visualization with Matplotlib and
    Seaborn**](#week-3-visualization-with-matplotlib-and-seaborn)
-   [Graphs](#graphs)
    -   [Big 5 graphs](#big-5-graphs)
-   [Plotting with Matplotlib](#plotting-with-matplotlib)
    -   [Create a basic plot](#create-a-basic-plot)
    -   [Oceania basic plot](#oceania-basic-plot)
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
-   [Notebooks vs Python](#notebooks-vs-python)
    -   [File contents](#file-contents)
    -   [Editors](#editors)
    -   [Workflow](#workflow)
    -   [When should I do this?](#when-should-i-do-this)
-   [Python from the terminal](#python-from-the-terminal)
-   [Use text processing and data frame processing as motivating
    examples for each
    section](#use-text-processing-and-data-frame-processing-as-motivating-examples-for-each-section)
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
    -   [(Optional) Use `range()` to iterate over a sequence of
        numbers](#optional-use-range-to-iterate-over-a-sequence-of-numbers)
    -   [(Optional) Use `enumerate()` to iterate over a sequence of
        items and their
        positions](#optional-use-enumerate-to-iterate-over-a-sequence-of-items-and-their-positions)
    -   [The Accumulator pattern turns many values into
        one](#the-accumulator-pattern-turns-many-values-into-one)
    -   [Dictionary iteration](#dictionary-iteration)
    -   [How do you know if an object is iterable?
        (optional)](#how-do-you-know-if-an-object-is-iterable-optional)
    -   [Don\'t use `for` loops with DataFrames or Numpy
        matrices](#dont-use-for-loops-with-dataframes-or-numpy-matrices)
-   [(move this up and incorporate) Looping Over Data
    Sets](#move-this-up-and-incorporate-looping-over-data-sets)
    -   [File paths as an example of increasing abstraction in program
        development](#file-paths-as-an-example-of-increasing-abstraction-in-program-development)
    -   [Use a `for` loop to process files given a list of their
        names](#use-a-for-loop-to-process-files-given-a-list-of-their-names)
    -   [Use glob.glob to find sets of files whose names match a
        pattern](#use-glob.glob-to-find-sets-of-files-whose-names-match-a-pattern)
    -   [Use glob and for to process batches of
        files](#use-glob-and-for-to-process-batches-of-files)
    -   [CHALLENGE: Comparing data (optional)
        (rewrite)](#challenge-comparing-data-optional-rewrite)
-   [Conditionals - motivate with data frame
    processing](#conditionals---motivate-with-data-frame-processing)
    -   [Use `if` statements to control whether or not a block of code
        is
        executed](#use-if-statements-to-control-whether-or-not-a-block-of-code-is-executed)
    -   [Conditionals are often used inside
        loops](#conditionals-are-often-used-inside-loops)
    -   [(Optional) Use pathlib to write code that works across
        operating
        systems](#optional-use-pathlib-to-write-code-that-works-across-operating-systems)
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
-   [(encapsulate cleaning functions) Writing
    Functions](#encapsulate-cleaning-functions-writing-functions)
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
    -   [Export to .py](#export-to-.py)
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
-   [Credits](#credits)
-   [References](#references)
-   [Data Sources](#data-sources)

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
-   You can export notebooks as .py files when they outgrow the notebook
    format

# Jupyter commands

## How to start Jupyter Lab

1.  Method 1

    1.  Open Anaconda Navigator
    2.  Run Jupyter Lab

2.  Method 2 Open Terminal (MacOS/Linux) or Anaconda Prompt (Windows)

    ``` bash
    cd Desktop/data
    jupyter lab
    ```

## Navigation

-   Navigate to where you want to be before creating new notebook
-   Rename your notebook to something informative
-   Use drag-and-drop interface to move .ipynb file to new location

## Writing code

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

4.  Many keyboard shortcuts are available; see
    <https://gist.github.com/discdiver/9e00618756d120a8c9fa344ac1c375ac>

5.  Jupyter Lab undestands (some) terminal commands

    ``` bash
    ls
    ```

6.  Jupyter Lab (IPython, actually) has \"magic\" commands that start
    with `%` (line) or `%%` (cell)

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

# Variables and Assignment

## Use variables to store values

Variables are names for values.

``` python
first_name = 'Derek'
age = 42
```

## Rules for naming things

1.  Can only contain letters, digits, and underscore
2.  Cannot start with a digit
3.  Are case sensitive: `age`, `Age` and `AGE`

## Use `print()` to display values

``` python
print(first_name, 'is', age, 'years old')
```

-   Functions are verbs
-   Functions end in `()`
-   Functions take arguments (i.e. they do stuff with the values that
    you give them)
-   `print()` useful for tracking progress, debugging

## Jupyter Lab will always echo the last value in a cell

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

## (Optional) Variables must be created before they are used

``` python
# Prints an informative error message; more about this later
print(last_name)
```

## Variables can be used in calculations

``` python
print(age)
age = age + 3
print(age)
```

## Variables only change value when something is assigned to them

Order of operations matters!

``` python
first = 1
second = 5 * first
first = 2
print('first is', first, 'and second is', second)
```

# Data Types and Type Conversion

## Every value has a type

Most data is text and numbers, but there are many other types.

1.  Integers: whole numbers (counting)
2.  Floats: real numbers (math)
3.  Strings: text
4.  Files
5.  Various collections (lists, sets, dictionaries, data frames, arrays)
6.  More abstract stuff (e.g., database connection)

## The type determine what operations you can perform with a given value

1.  Example 1: Subtraction makes sense for some kinds of data but not
    others

    ``` python
    print(5 - 3)
    print('hello' - 'h')
    ```

2.  Example 2: Some things have length and some don\'t Note that we can
    put functions inside other functions!

    ``` python
    print(len('hello'))
    print(len(5))
    ```

## Use the built-in function `type()` to find the type of a value

1.  Two types of number

    ``` python
    print(type(53))
    print(type(3.12))
    ```

2.  You can check the type of a variable

    ``` python
    fitness = 'average'
    type(fitness)
    ```

3.  Python is strongly-typed: It will (mostly) refuse to convert things
    automatically. The exception is mathematical operations with
    integers and floats.

    ``` python
    int_sum = 3 + 4
    mixed_sum = 3 + 4.0

    print(type(int_sum))
    print(type(mixed_sum))
    ```

## You can explicitly convert data to a different type

1.  Can\'t do math with text

    ``` python
    1 + '2'
    ```

2.  If you have string data, you can explicitly convert it to numeric
    data...

    ``` python
    print(1 + float('2'))
    print(1 + int('2'))
    ```

3.  ...and vice-versa

    ``` python
    text = str(3)

    print(text)
    print(type(text))
    ```

4.  This can work for more complex data types as well, e.g. Pandas data
    frames and Numpy arrays.

## Challenge: Explain what each operator does

``` python
# Floor
print('5 // 3:', 5 // 3)

# Floating point
print('5 / 3:', 5 / 3)

# Modulus (remainder)
print('5 % 3:', 5 % 3)
```

# Built-in Functions and Help

## How do we find out what\'s possible?

-   Python.org tutorial
-   Standard library reference (we will discuss libraries in the next
    section)
-   References section of this document
-   Stack Overflow

## (Optional) Use comments to add documentation to programs

Leave notes for Future You about what you\'ve learned and how your code
works.

``` python
# This line isn't executed by Python
print("This cell has many comments")   # The rest of this line isn't executed either
```

## A function may take zero or more arguments

``` python
print('before')
print()
print('after')
```

## Every function returns something

1.  Collect the results of a function in a new variable. This is one of
    the ways we build complex programs.

    ``` python
    result = len("hello")
    print(result)
    ```

2.  (Optional) Some function only have \"side effects\"; they return
    `None`

    ``` python
    result = print("hello")
    print(result)
    print(type(result))
    ```

## Functions can have optional parameters

``` python
# By default, we round to the nearest integer
round(3.712)
```

``` python
# You can optionally specify the number of significant digits
round(3.712, 1)
```

## Use the built-in function `help()` to get help for a function

1.  View the documentation for `round()`

    ``` python
    help(round)
    ```

    -   1 mandatory argument
    -   1 optional argument with a default value: `ndigits=None`

2.  You can proved arguments implicitly by order, or explicitly in any
    order

    ``` python
    # You can optionally specify the number of significant digits
    round(4.712823, ndigits=2)
    ```

## (Optional) Functions will typically generalize in sensible ways

1.  `max()` and `min()` do the intuitively correct thing with numerical
    and text data

    ``` python
    print(max(1, 2, 3))
    print(min('a', 'A', '0'))       # sort order is 0-9, A-Z, a-z
    ```

2.  Mixed numbers and text aren\'t meaningfully comparable

    ``` python
    max(1, 'a')
    ```

## *Methods* are functions that belong to objects

1.  An object packages data together with functions that operate on that
    data. This is a very common organizational strategy in Python.

    ``` python
    my_string = 'Hello world!'

    # Call the swapcase method on the my_string object
    print(my_string.swapcase())
    ```

2.  You can chain methods into processing pipelines

    ``` python
    print(my_string.isupper())          # Check whether all letters are uppercase
    print(my_string.upper())            # Capitalize all the letters
    ```

    ``` python
    # The output of upper() is as string; you can use more string methods on it
    my_string.upper().isupper()
    ```

3.  You can view an object\'s attributes (i.e. methods and fields) using
    `help()` or `dir()`. Some attributes are \"private\"; you\'re not
    supposed to use these directly.

    ``` python
    # More verbose help
    help(str)
    ```

    ``` python
    # The short, short version
    dir(my_string)
    ```

4.  The built-in string methods can be very useful for cleaning up data

    ``` python
    bad_string_1 = "  Hello world!   "
    bad_string_2 = "|...goodbye cruel world|"

    print(bad_string_1.strip(),
          bad_string_2.strip("|"))
    ```

## (Optional) Python produces informative error messages

1.  Python reports a syntax error when it can't understand the source of
    a program

    ``` python
    name = 'Bob
    age = = 54
    print("Hello world"
    ```

2.  Python reports a runtime error when something goes wrong while a
    program is executing

## (Optional) Challenge: What happens when?

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

print(math.pi)
print(math.cos(math.pi))
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

## Import shortcuts

1.  Import specific items from a library module. You want to be careful
    with this. It\'s safer to keep the namespace.

    ``` python
    from math import cos, pi

    cos(pi)
    ```

2.  Create an alias for a library module when importing it

    ``` python
    import math as m

    print(m.cos(m.pi))
    ```

## Python has opinions about how to write your programs

``` python
import this
```

# Lists

Lists are the central data structure in Python; we will explain many
things by making analogies to lists.

## A list stores many values in a single structure

``` python
pressure = [0.17, 0.23, 0.54, 0.38, 0.76, 0.43]
print(pressure)
print(len(pressure))
```

## Lists are indexed by position, counting from 0

``` python
print("First item:", pressure[0])
print("Fifth item:" , pressure[4])
```

## You can get a subset of the list by slicing it

1.  You slice a list from the start position up to, but not including,
    the stop position

    ``` python
    print("First 3 items:", pressure[0:3])
    print("3rd through 5th:", pressure[2:5])
    ```

2.  You can omit the start position if you\'re starting at the
    beginning...

    ``` python
    print("First 5 items:", pressure[0:5])
    print("First 5 items, but shorter:", pressure[:5])
    ```

3.  ...and you can omit the end position if you\'re going to the end

    ``` python
    # This is useful if you don't know how long the list is
    print("Everything but the first 3 items:", pressure[3:])
    ```

4.  You can add an optional step interval (every 2nd item, every 3rd
    item, etc.)

    ``` python
    print("First 5 items, every other item:", pressure[0:5:2])
    print("Every third item:", pressure[::3])
    ```

## Why are lists indexed from 0?

cf. <https://stackoverflow.com/a/11364711>

1.  Slice endpoints are compliments In both cases, the number you see
    represents what you want to do.

    ``` python
    # Get the first two items
    print(pressure[:2])

    # Get everything except the first two items
    print(pressure[2:])
    ```

2.  For non-negative indices, the length of a slice is the difference of
    the indices

    ``` python
    len(pressure[1:3]) == 2
    ```

## Some other properties of indexes

1.  Indexing beyond the end of the collection is an error

    ``` python
    pressure[20]
    ```

2.  You can count backwards from the end with negative integers

    ``` python
    print("Last item:", pressure[-1])
    ```

## Lists are mutable

1.  You can replace a value at a specific index location

    ``` python
    pressuressure[0] = 0.999
    print(pressure)
    ```

2.  Add an item to list with `append()`. This is a *method* of the list.

    ``` python
    primes = [2, 3, 5]
    print(primes)
    primes.append(7)
    print(primes)
    ```

3.  Add the items from one list to another with `extend()`

    ``` python
    teen_primes = [11, 13, 17, 19]

    # Add all of the elements of teen_primes to primes
    primes.extend(teen_primes)
    print(primes)
    ```

4.  (Optional) Slice endpoints are compliments, take 2

    ``` python
    new_pressure = pressure[:2]
    new_pressure.extend(pressure[2:])

    print(new_pressure == pressure)
    ```

## Many functions take collections as arguments

``` python
mean_p = sum(pressure)/len(pressure)
print(mean_p)
```

## (Optional) Removing items from a list

1.  Use `del` to remove an item at an index location

    ``` python
    primes = [2, 3, 5, 7, 9]
    print(primes)
    del primes[4]
    print(primes)
    ```

2.  Use `pop()` to remove the last item and assign it to a variable.
    This is useful for destructive iteration.

    ``` python
    p = primes.pop()

    print('Last prime in list', p)
    print(primes)
    ```

## Lists can contain anything

1.  You can mix data types

    ``` python
    ages = ['Derek', 42, 'Bill', 24, 'Susan', 37]

    # Get first pair
    print(ages[0:2])

    # Get all the names
    print(ages[::2])

    # Get all the ages
    print(ages[1::2])
    ```

2.  You can put lists inside other lists

    ``` python
    ages.append(primes)

    # List in our list
    print(ages)

    # The last item is a list
    print(ages[-1])

    # Get an item from that list
    print(ages[-1][2])
    ```

# Strings are (kind of) like lists

## Strings are indexed like lists

1.  Use an index to get a single character from a string

    ``` python
    element = 'carbon'
    element[0]
    ```

2.  Use a slice to get a substring

    ``` python
    element[0:3]
    ```

3.  Counting backwards

    ``` python
    element[-1]
    ```

4.  Et cetera

## (Optional) Strings have a length

``` python
len('carbon')
```

## But! Strings are immutable

1.  Can\'t change a string in place

    ``` python
    element[0] = 'C'
    ```

2.  String methods create a new string

    ``` python
    print(element.capitalize())
    print(element)
    ```

    ``` python
    carbon_title = element.capitalize()
    print(carbon_title)
    ```

## Building strings with `.join()`

``` python
date_list = ["3", "17", "2007"]
date = "/".join(date_list)
print(date)
```

## (Optional) Challenge: From Strings to Lists and Back

1.  Given this Python code...

    ``` python
    print('string to list:', list('tin'))
    print('list to string:', ''.join(['g', 'o', 'l', 'd']))
    ```

2.  ...and this output:

    ``` fundamental
    string to list: ['t', 'i', 'n']
    list to string: gold
    ```

3.  What does `list('some string')` do?

4.  What does `'-'.join(['x', 'y', 'z'])` generate?

## (Optional) Challenge: Locating the right module

You want to select a random character from a string:

``` python
bases = 'ACTTGCTTGAC'
```

1.  Which standard library module could help you?
    <https://docs.python.org/3/library/>
2.  Which function would you select from that module? Are there
    alternatives?
3.  Try to write a program that uses the function.

### Solutions:

1.  You could try the `random` module. The string has 11 characters,
    each having a positional index from 0 to 10. You could use either
    `random.randrange` or `random.randint` functions to get a random
    integer between 0 and 10, and then pick out the character at that
    position:

    ``` python
    from random import randrange

    random_index = randrange(len(bases))
    print(bases[random_index])
    ```

    ...or more compactly:

    ``` python
    from random import randrange

    print(bases[randrange(len(bases))])
    ```

2.  Perhaps you found the `random.sample()` function. It allows for
    slightly less typing:

    ``` python
    from random import sample

    print(sample(bases, 1)[0])
    ```

# Dictionaries

## Dictionaries are sets of key/value pairs. Instead of being indexed by position, they are indexed by key.

``` python
wave_fc = {"Girma": 4,
           "Sheridan": 3,
           "Morgan": 13}

# Returns 4
wave_fc["Girma"]
```

## Update dictionaries by assigning a key/value pair

1.  Update a pre-existing key with a new value

    ``` python
    wave_fc["Sheridan"] = 1

    print(wave_fc)
    ```

2.  Add a new key/value pair

    ``` python
    wave_fc["Shaw"] = 11
    ```

## (Optional) Check whether the dictionary contains an item

1.  Does a key already exist?

    ``` python
    "Girma" in wave_fc
    ```

2.  Does a value already exist (you generally don\'t want to do this;
    keys are unique but values are not)?

    ``` python
    4 in wave_fc.values()
    ```

## (Optional) Delete an item using `del` or `pop()`

``` python
print("Original dictionary", wave_fc)
del wave_fc["Morgan"]
print("1st deletion", wave_fc)

girma_num = wave_fc.pop("Girma")
print("2nd deletion", wave_fc)
print("Returned value", girma_num)
```

## Dictionaries are the natural way to store tree-structured data

As with lists, you can put anything in a dictionary.

``` python
location = {'latitude': [37.28306, 'N'],
            'longitude': [-120.50778, 'W']}

print(location['longitude'][0])
```

## Challenge: Convert a list to a dictionary

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
ages_dict = dict(zip(ages[::2], ages[1::2]))
```

# (Optional) Other containers

1.  Tuples
2.  Sets

# **WEEK 2: Data manipulation with Pandas**

# (Optional) Review collections

## Lists and dictionaries

1.  Reference item by index/key
2.  Insert item by index/key
3.  Indices/keys must be unique

## Strings

1.  Similar to lists: Reference item by index, have length
2.  Immutable, so need to use string **methods**
3.  `'/'.join()` is a very useful method

# A very brief introduction to NumPy

1.  NumPy is the linear algebra library for Python

    ``` python
    import numpy as np

    # Create an array of random numbers
    rand = np.random.rand(3, 4)

    print(rand)
    print(rand[0,0])
    ```

2.  Arrays are fast but inflexible - the entire array must be of a
    single type.

# A very brief introduction to Pandas

1.  Pandas is a library for working with spreadsheet-like data
    (\"DataFrames\")
2.  A DataFrame is a collection (dict) of Series columns
3.  Each Series is a 1-dimensional NumPy array with optional row labels
    (dict-like, similar to R vectors)
4.  Therefore, each series inherits many of the abilities (linear
    algebra) and limitations (single data type) of NumPy

# (Optional) Where are we?

## Python provides functions for working with the file system.

``` python
import os

# print current directory
print("Current working directory:", os.getcwd())
# print all of the files and directories
print("Working directory contents:", os.listdir())
```

## These provide a rich Python alternative to shell functions

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

# Reading tabular data into data frames

## Import tabular data using the Pandas library

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

## Use `index_col` to use a column's values as row indices

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

## Pandas help files are dense; you should prefer the online documentation

1.  Main documentation link:
    <https://pandas.pydata.org/docs/user_guide/index.html>
2.  Pandas can read many different data formats:
    <https://pandas.pydata.org/docs/user_guide/io.html>

# Data frames are objects that can tell you about their contents

## Data frames have methods (i.e. functions) that perform operations using the data frame\'s contents as input

1.  Use `.info()` to find out more about a data frame

    ``` python
    data.info()
    ```

2.  Use `.describe()` to get summary statistics about data

    ``` python
    data.describe()
    ```

3.  Look at the first few rows

    ``` python
    data.head(1)
    ```

## Data frames have fields (i.e. variables) that hold additional information

A \"field\" is a variable that belongs to an object.

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

4.  Use `DataFrame.T` to transpose a DataFrame. This doesn\'t copy or
    modify the data, it just changes the caller\'s view of it.

    ``` python
    data.T
    ```

## (Optional) Pandas introduces some new types

``` python
# DataFrame type
type(data)
type(data.T)

# Series type
type(data['gdpPercap_1952'])

# Index type
type(data.columns)
```

-   You can convert data between NumPy arrays, Series, and DataFrames
-   You can read data into any of the data structures from files or from
    standard Python containers

## (Optional) Challenge

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

# Subsetting Data

## Treat the data frame as a matrix and select values by position

Use `DataFrame.iloc[..., ...]` to select values by their (entry)
position. The `i` in `iloc` stands for \"index\".

``` python
import pandas as pd
data = pd.read_csv('data/gapminder_gdp_europe.csv', index_col='country')

data.iloc[0,0]
```

## Treat the data frame as a table and select values by label

This is most common way to get data

1.  Use `DataFrame.loc[..., ...]` to select values by their label

    ``` python
    # This returns a value
    data.loc["Albania", "gdpPercap_1952"]
    ```

## Shorten the column names using vectorized string methods

``` python
print(data.columns)

# The columns index can update all of its values in a single operation
data.columns = data.columns.str.strip("gdpPercap_")
print(data.columns)
```

## Use list slicing notation to get subsets of the data frame

1.  Select multiple columns or rows using `.loc` and a named slice. This
    generalizes the concept of a slice to include labeled indexes:

    ``` python
    # This returns a DataFrame
    data.loc['Italy':'Poland', '1962':'1972']
    ```

2.  Use `:` on its own to mean all columns or all rows. This is Python's
    usual slicing notation, which allows you to treat DataFrames as
    multi-dimensional lists. Note that Pandas automatically converts the
    1-dimensional row into a Series; we will discuss how to get around
    this in the next section.

    ``` python
    # This returns a Series
    data.loc["Albania", :]
    ```

3.  If you want specific rows or columns, pass in a list:

    ``` python
    data.loc[['Italy','Poland'], :]
    ```

4.  `.iloc` follows list index conventions (\"up to, but not
    including)\", but `.loc` does the intuitive right thing (\"A through
    B\"):

    ``` python
    index_subset = data.iloc[0:2, 0:2]
    label_subset = data.loc["Albania":"Belgium", "1952":"1962"]

    print(index_subset)
    print(label_subset)
    ```

5.  Result of slicing can be used in further operations

    ``` python
    subset = data.loc['Italy':'Poland', '1962':'1972']

    print(subset.describe)
    print(subset.max())
    ```

6.  (Optional) You can extract individual rows as Series, then
    concatenate them into a new DataFrame

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

## Treat the data frame as an object and select values using flexible methods

1.  `.filter()` is a general-purpose, flexible method

    ``` python
    help(data.filter)
    data.filter(like="20)", axis="columns")
    ```

2.  `.filter()` always returns the same type as the original item,
    whereas `.loc` and `.iloc` might return a data frame or a series.

    ``` python
    italy = data.filter(like="200", axis="columns").filter(items=["Italy"], axis="index")
    print(italy)
    print(type(italy))
    ```

# Filtering data

## Use comparisons to select data based on value

1.  Show which data frame elements match a criterion

    ``` python
    # Which GDPs are greater than 10,000?
    subset > 10000
    ```

2.  Use `.where()` method to find elements that match the criterion:

    ``` python
    fs = subset.where(subset > 10000)
    print(fs)
    ```

3.  (Optional) Use the criterion match to filter the data frame\'s
    contents. This uses index notation:

    ``` python
    subset[subset > 10000]
    ```

## Use method chaining to create final output without creating intermediate variables

``` python
# The rank() method turns numerical scores into ranks, e.g.:
subset.rank()

# Do this for countries above the median
data.where(data > data.median()).rank()
```

## Methods we\'re not going to cover

`.query()`

# Working with missing data

## By default, most numerical operations ignore missing data

Examples include min, max, mean, std, etc.

1.  Missing values ignored by default

    ``` python
    # Column means
    print(fs.mean())

    # Row means
    print(fs.mean(axis=1))
    ```

2.  Force inclusions with the `skipna` argument

    ``` python
    print(fs.mean(skipna=False))
    print(fs.mean(axis=1, skipna=False))
    ```

## Check for missing values

1.  Show which items are missing

    ``` python
    # Show which items are NaN
    fs.isna()
    ```

2.  Count missing values

    ``` python
    # Missing by row
    print(fs.isna().sum())

    # Missing by column
    print(fs.isna().sum(axis=1))

    # Aggregate sum
    fs.isna().sum().sum()
    ```

3.  Are any values missing?

    ``` python
    fs.isna().any(None)
    ```

4.  (Optional) Are all of the values missing?

    ``` python
    fs.isna().all(None)
    ```

## Replace missing values

1.  Replace with a fixed value

    ``` python
    fs_fixed = fs.fillna(0)
    ```

2.  (Optional) Interpolate missing values

    ``` python
    fs_inferred = fs.interpolate()
    ```

## Drop missing values

``` python
fs_drop = fs.dropna()
```

# Sorting and grouping

## Motivating example: Calculate the wealth Z-score for each country

``` python
# Calculate z scores for all elements
z = (data - data.mean())/data.std()

# Get the mean z score for each country (i.e. across all columns)
mean_z = z.mean(axis=1)

# Group countries into "wealthy" (z > 0) and "not wealthy" (z <= 0)
z_bool = mean_z > 0

print(mean_z)
print(z_bool)
```

## Append new columns to the data frame containing our summary statistics

Data frames are dictionaries of Series:

``` python
data["mean_z"] = mean_z
data["wealthy"] = z_bool
```

## Sort and group by new columns

``` python
data.sort_values(by="mean_z")
```

``` python
# Get descriptive statistics for the group
data.groupby("wealthy").mean()
data.groupby("wealthy").describe()
```

# Write output

Capture the results of your filter in a new file, rather than
overwriting your original data.

``` python
# Save to a new CSV, preserving your original data
data.to_csv('gapminder_gdp_europe_normed.csv')

# If you don't want to preserve row names:
#data.to_csv('gapminder_gdp_europe_normed.csv', index=False)
```

# Working with multiple tables (in an SQL-like manner)

## Concatenating data frames

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

## Joining data frames

1.  Import species data

    ``` python
    species = pd.read_csv('data/species.csv', index_col="species_id")
    print(species.shape)
    ```

2.  Join tables on common column. The inner join only includes rows
    where both tables match on the key column.

    ``` python
    df_join = surveys.merge(species, on="species_id")
    print(df_join.head())
    print(df_join.shape)
    ```

3.  Get the subset of species that match a criterion, and join on that
    subset.

    ``` python
    # Get the taxa column, masking the rows based on which values match "Bird"
    birds = species[species["taxa"] == "Bird"]
    df_birds = surveys.join(birds, on="species_id")

    print(joined_birds.head())
    print(joined_birds.shape)
    ```

# Scientific Computing Libraries

1.  SciPy projects
    1.  Numpy: Linear algebra
    2.  Pandas
    3.  Scipy.stats: Probability distributions and basic tests
2.  Statsmodels: Statistical models and formulae built on Scipy.stats
3.  Scikit-Learn: Machine learning tools built on NumPy
4.  Tensorflow/PyTorch: Deep learning and other voodoo

## (Optional) Statsmodels regression example

1.  Import data

    ``` python
    dataa = pd.read_csv('surveys.csv')

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
    importort statsmodels

    help(statsmodels.base.model.Model)
    ```

## (Optional) Getting started with machine learning estimators

<https://scikit-learn.org/stable/tutorial/machine_learning_map/index.html>
<https://scikit-learn.org/stable/_static/ml_map.png>

# (Optional) Things we didn\'t talk about

1.  pipe
2.  map/applymap/apply (in general you should prefer vectorized
    functions)

# (Optional) Adding rows to DataFrames

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

# (Optional) Pandas method chaining in the wild

<https://gist.githubusercontent.com/adiamaan92/d8ebee8937d271452def2a7314993b2f/raw/ce9fbb5013d94accf0779a25e182c4be77678bd0/wine_mc_example.py>

``` python
wine.rename(columns={"color_intensity": "ci"})
.assign(color_filter=lambda x: np.where((x.hue > 1) & (x.ci > 7), 1, 0))
.query("alcohol > 14 and color_filter == 1")
.sort_values("alcohol", ascending=False)
.reset_index(drop=True)
.loc[:, ["alcohol", "ci", "hue"]]
```

# (Optional) Introspecting on the DataFrame object

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

# (Carpentries version) Group By: split-apply-combine

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

2.  A DataFrame is a spreadsheet, but it is also a dictionary of
    columns.

    ``` python
    data['gdpPercap_1962']
    ```

3.  Add column to data frame

    ``` python
    # Warningealth Score is a series
    type(wealth_score)

    data['normalized_wealth'] = wealth_score
    ```

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

## Oceania basic plot

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

# Notebooks vs Python

## File contents

1.  Export notebook to .py file
2.  .ipynb vs. .py structure (demo in Spyder)

## Editors

## Workflow

1.  Version control
2.  Interactive debugging
3.  Graphics
4.  Output files in general

## When should I do this?

# Python from the terminal

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

3.  (Optional) Python programs can accept command line arguments as
    inputs

    1.  List of command line inputs: `sys.argv`
        (<https://docs.python.org/3/library/sys.html#sys.argv>)
    2.  Utility for working with arguments: `argparse`
        (<https://docs.python.org/3/library/argparse.html>)

# Use text processing and data frame processing as motivating examples for each section

1.  Clean text data
2.  Clean data frame data

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

## (Optional) Use `range()` to iterate over a sequence of numbers

``` python
for number in range(0, 3):
    print(number)
```

-   range() produces numbers on demand (a \"generator\" function)
-   useful for tracking progress

## (Optional) Use `enumerate()` to iterate over a sequence of items and their positions

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

# (move this up and incorporate) Looping Over Data Sets

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

# Conditionals - motivate with data frame processing

e.g. generate a data set with missing data, then check for it using
any()/all()

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

## (Optional) Use pathlib to write code that works across operating systems

Note the careful testing at each level of the code.

``` python
from pathlib import Path

relative_path = Path("data")   # data subdirectory
# relative_path = Path()       # current directory
print("Relative path:", relative_path)
print("Absolute path:", relative_path.absolute())
```

``` python
if relative_path.exists():
    for filename in relative_path.glob('gapminder_*.csv'):
        if filename.is_file():
            data = pd.read_csv(filename)
            print(filename, data['gdpPercap_1952'].min())
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

# (encapsulate cleaning functions) Writing Functions

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

## Export to .py

run in e.g. Spyder

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

# Credits

-   Plotting and Programming in Python (Pandas-oriented):
    <http://swcarpentry.github.io/python-novice-gapminder/>
-   Programming with Python (NumPy-oriented):
    <https://swcarpentry.github.io/python-novice-inflammation/index.html>
-   Python for Ecology:
    <https://datacarpentry.org/python-ecology-lesson/>
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
-   SciPy stats: <https://docs.scipy.org/doc/scipy/reference/stats.html>
-   Statistics in Python tutorial:
    <https://scipy-lectures.org/packages/statistics/>
-   Statsmodels library: <https://www.statsmodels.org/stable/index.html>
-   Seaborn gallery of examples:
    <https://seaborn.pydata.org/examples/index.html>
-   Matplotlib gallery of examples:
    <https://matplotlib.org/gallery/index.html>
-   IPython magic commands:
    <https://ipython.readthedocs.io/en/stable/interactive/magics.html>
-   A somewhat-biased comparison of tools for integrating Python with
    C/C++:
    <http://blog.behnel.de/posts/cython-pybind11-cffi-which-tool-to-choose.html>

# Data Sources

1.  Gapminder data:
    <http://swcarpentry.github.io/python-novice-gapminder/files/python-novice-gapminder-data.zip>
2.  Ecology data (field surveys):
    <https://datacarpentry.org/python-ecology-lesson/data/portal-teachingdb-master.zip>
3.  Social Science data (SAFI):
    <https://datacarpentry.org/socialsci-workshop/data/>
4.  Humanities data (Pettigrew letters):
    <http://dx.doi.org/10.5334/data.1335350291>
