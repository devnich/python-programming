- <a href="#week-1-fundamentals" id="toc-week-1-fundamentals"><strong>WEEK 1: Fundamentals</strong></a>
- <a href="#orientation" id="toc-orientation">Orientation</a>
  - <a href="#what-programming-language-should-i-use" id="toc-what-programming-language-should-i-use">What programming language should I use?</a>
  - <a href="#python-is-pretty-good-at-lots-of-things" id="toc-python-is-pretty-good-at-lots-of-things">Python is pretty good at lots of things</a>
  - <a href="#literate-programming-and-notebooks" id="toc-literate-programming-and-notebooks">Literate programming and notebooks</a>
- <a href="#jupyter-commands" id="toc-jupyter-commands">Jupyter commands</a>
  - <a href="#how-to-start-jupyter-lab" id="toc-how-to-start-jupyter-lab">How to start Jupyter Lab</a>
  - <a href="#navigation" id="toc-navigation">Navigation</a>
  - <a href="#writing-code" id="toc-writing-code">Writing code</a>
- <a href="#variables-and-assignment" id="toc-variables-and-assignment">Variables and Assignment</a>
  - <a href="#use-variables-to-store-values" id="toc-use-variables-to-store-values">Use variables to store values</a>
  - <a href="#rules-for-naming-things" id="toc-rules-for-naming-things">Rules for naming things</a>
  - <a href="#use-print-to-display-values" id="toc-use-print-to-display-values">Use <code>print()</code> to display values</a>
  - <a href="#jupyter-lab-will-always-echo-the-last-value-in-a-cell" id="toc-jupyter-lab-will-always-echo-the-last-value-in-a-cell">Jupyter Lab will always echo the last value in a cell</a>
  - <a href="#optional-variables-must-be-created-before-they-are-used" id="toc-optional-variables-must-be-created-before-they-are-used">(Optional) Variables must be created before they are used</a>
  - <a href="#variables-can-be-used-in-calculations" id="toc-variables-can-be-used-in-calculations">Variables can be used in calculations</a>
  - <a href="#variables-only-change-value-when-something-is-assigned-to-them" id="toc-variables-only-change-value-when-something-is-assigned-to-them">Variables only change value when something is assigned to them</a>
- <a href="#data-types-and-type-conversion" id="toc-data-types-and-type-conversion">Data Types and Type Conversion</a>
  - <a href="#every-value-has-a-type" id="toc-every-value-has-a-type">Every value has a type</a>
  - <a href="#the-type-determine-what-operations-you-can-perform-with-a-given-value" id="toc-the-type-determine-what-operations-you-can-perform-with-a-given-value">The type determine what operations you can perform with a given value</a>
  - <a href="#use-the-built-in-function-type-to-find-the-type-of-a-value" id="toc-use-the-built-in-function-type-to-find-the-type-of-a-value">Use the built-in function <code>type()</code> to find the type of a value</a>
  - <a href="#you-can-explicitly-convert-data-to-a-different-type" id="toc-you-can-explicitly-convert-data-to-a-different-type">You can explicitly convert data to a different type</a>
  - <a href="#challenge-explain-what-each-operator-does" id="toc-challenge-explain-what-each-operator-does"><strong>Challenge</strong>: Explain what each operator does</a>
- <a href="#built-in-functions-and-help" id="toc-built-in-functions-and-help">Built-in Functions and Help</a>
  - <a href="#how-do-we-find-out-whats-possible" id="toc-how-do-we-find-out-whats-possible">How do we find out what's possible?</a>
  - <a href="#optional-use-comments-to-add-documentation-to-programs" id="toc-optional-use-comments-to-add-documentation-to-programs">(Optional) Use comments to add documentation to programs</a>
  - <a href="#a-function-may-take-zero-or-more-arguments" id="toc-a-function-may-take-zero-or-more-arguments">A function may take zero or more arguments</a>
  - <a href="#functions-can-have-optional-arguments" id="toc-functions-can-have-optional-arguments">Functions can have optional arguments</a>
  - <a href="#use-the-built-in-function-help-to-get-help-for-a-function" id="toc-use-the-built-in-function-help-to-get-help-for-a-function">Use the built-in function <code>help()</code> to get help for a function</a>
  - <a href="#every-function-returns-something" id="toc-every-function-returns-something">Every function returns something</a>
  - <a href="#optional-functions-will-typically-generalize-in-sensible-ways" id="toc-optional-functions-will-typically-generalize-in-sensible-ways">(Optional) Functions will typically generalize in sensible ways</a>
  - <a href="#methods-are-functions-that-belong-to-objects" id="toc-methods-are-functions-that-belong-to-objects"><em>Methods</em> are functions that belong to objects</a>
  - <a href="#optional-python-produces-informative-error-messages" id="toc-optional-python-produces-informative-error-messages">(Optional) Python produces informative error messages</a>
  - <a href="#optional-beginner-challenge-what-happens-when" id="toc-optional-beginner-challenge-what-happens-when"><strong>(Optional) Beginner Challenge</strong>: What happens when?</a>
- <a href="#libraries" id="toc-libraries">Libraries</a>
  - <a href="#most-of-the-power-of-a-programming-language-is-in-its-libraries" id="toc-most-of-the-power-of-a-programming-language-is-in-its-libraries">Most of the power of a programming language is in its libraries</a>
  - <a href="#a-program-must-import-a-library-module-before-using-it" id="toc-a-program-must-import-a-library-module-before-using-it">A program must <code>import</code> a library module before using it</a>
  - <a href="#use-help-to-learn-about-the-contents-of-a-library-module" id="toc-use-help-to-learn-about-the-contents-of-a-library-module">Use <code>help()</code> to learn about the contents of a library module</a>
  - <a href="#optional-import-shortcuts" id="toc-optional-import-shortcuts">(Optional) Import shortcuts</a>
  - <a href="#python-has-opinions-about-how-to-write-your-programs" id="toc-python-has-opinions-about-how-to-write-your-programs">Python has opinions about how to write your programs</a>
- <a href="#lists" id="toc-lists">Lists</a>
  - <a href="#a-list-stores-many-values-in-a-single-structure" id="toc-a-list-stores-many-values-in-a-single-structure">A list stores many values in a single structure</a>
  - <a href="#lists-are-indexed-by-position-counting-from-0" id="toc-lists-are-indexed-by-position-counting-from-0">Lists are indexed by position, counting from 0</a>
  - <a href="#you-can-get-a-subset-of-the-list-by-slicing-it" id="toc-you-can-get-a-subset-of-the-list-by-slicing-it">You can get a subset of the list by slicing it</a>
  - <a href="#why-are-lists-indexed-from-0" id="toc-why-are-lists-indexed-from-0">Why are lists indexed from 0?</a>
  - <a href="#some-other-properties-of-indexes" id="toc-some-other-properties-of-indexes">Some other properties of indexes</a>
  - <a href="#lists-are-mutable" id="toc-lists-are-mutable">Lists are mutable</a>
  - <a href="#many-functions-take-collections-as-arguments" id="toc-many-functions-take-collections-as-arguments">Many functions take collections as arguments</a>
  - <a href="#optional-removing-items-from-a-list" id="toc-optional-removing-items-from-a-list">(Optional) Removing items from a list</a>
  - <a href="#lists-can-contain-anything" id="toc-lists-can-contain-anything">Lists can contain anything</a>
- <a href="#strings-are-kind-of-like-lists" id="toc-strings-are-kind-of-like-lists">Strings are (kind of) like lists</a>
  - <a href="#strings-are-indexed-like-lists" id="toc-strings-are-indexed-like-lists">Strings are indexed like lists</a>
  - <a href="#optional-strings-have-a-length" id="toc-optional-strings-have-a-length">(Optional) Strings have a length</a>
  - <a href="#but-strings-are-immutable" id="toc-but-strings-are-immutable">But! Strings are immutable</a>
  - <a href="#building-strings-with-.join" id="toc-building-strings-with-.join">Building strings with <code>.join()</code></a>
  - <a href="#optional-beginner-challenge-from-strings-to-lists-and-back" id="toc-optional-beginner-challenge-from-strings-to-lists-and-back"><strong>(Optional) Beginner Challenge</strong>: From Strings to Lists and Back</a>
  - <a href="#challenge-locating-the-right-module" id="toc-challenge-locating-the-right-module"><strong>Challenge</strong>: Locating the right module</a>
- <a href="#dictionaries" id="toc-dictionaries">Dictionaries</a>
  - <a href="#dictionaries-are-sets-of-keyvalue-pairs.-instead-of-being-indexed-by-position-they-are-indexed-by-key." id="toc-dictionaries-are-sets-of-keyvalue-pairs.-instead-of-being-indexed-by-position-they-are-indexed-by-key.">Dictionaries are sets of key/value pairs. Instead of being indexed by position, they are indexed by key.</a>
  - <a href="#update-dictionaries-by-assigning-a-keyvalue-pair" id="toc-update-dictionaries-by-assigning-a-keyvalue-pair">Update dictionaries by assigning a key/value pair</a>
  - <a href="#optional-check-whether-the-dictionary-contains-an-item" id="toc-optional-check-whether-the-dictionary-contains-an-item">(Optional) Check whether the dictionary contains an item</a>
  - <a href="#optional-delete-an-item-using-del-or-pop" id="toc-optional-delete-an-item-using-del-or-pop">(Optional) Delete an item using <code>del</code> or <code>pop()</code></a>
  - <a href="#dictionaries-are-the-natural-way-to-store-tree-structured-data" id="toc-dictionaries-are-the-natural-way-to-store-tree-structured-data">Dictionaries are the natural way to store tree-structured data</a>
  - <a href="#optional-advanced-challenge-convert-a-list-to-a-dictionary" id="toc-optional-advanced-challenge-convert-a-list-to-a-dictionary"><strong>(Optional) Advanced Challenge</strong>: Convert a list to a dictionary</a>
- <a href="#optional-other-containers" id="toc-optional-other-containers">(Optional) Other containers</a>
- <a href="#week-2-data-manipulation-with-pandas" id="toc-week-2-data-manipulation-with-pandas"><strong>WEEK 2: Data manipulation with Pandas</strong></a>
- <a href="#optional-review-collections" id="toc-optional-review-collections">(Optional) Review collections</a>
  - <a href="#lists-and-dictionaries" id="toc-lists-and-dictionaries">Lists and dictionaries</a>
  - <a href="#strings" id="toc-strings">Strings</a>
- <a href="#a-very-brief-introduction-to-numpy" id="toc-a-very-brief-introduction-to-numpy">A very brief introduction to NumPy</a>
- <a href="#a-very-brief-introduction-to-pandas" id="toc-a-very-brief-introduction-to-pandas">A very brief introduction to Pandas</a>
- <a href="#optional-where-are-we" id="toc-optional-where-are-we">(Optional) Where are we?</a>
  - <a href="#python-provides-functions-for-working-with-the-file-system." id="toc-python-provides-functions-for-working-with-the-file-system.">Python provides functions for working with the file system.</a>
  - <a href="#these-provide-a-rich-python-alternative-to-shell-functions" id="toc-these-provide-a-rich-python-alternative-to-shell-functions">These provide a rich Python alternative to shell functions</a>
- <a href="#reading-tabular-data-into-data-frames" id="toc-reading-tabular-data-into-data-frames">Reading tabular data into data frames</a>
  - <a href="#import-tabular-data-using-the-pandas-library" id="toc-import-tabular-data-using-the-pandas-library">Import tabular data using the Pandas library</a>
  - <a href="#use-index_col-to-use-a-columns-values-as-row-indices" id="toc-use-index_col-to-use-a-columns-values-as-row-indices">Use <code>index_col</code> to use a column’s values as row indices</a>
  - <a href="#pandas-help-files-are-dense-you-should-prefer-the-online-documentation" id="toc-pandas-help-files-are-dense-you-should-prefer-the-online-documentation">Pandas help files are dense; you should prefer the online documentation</a>
- <a href="#data-frames-are-objects-that-can-tell-you-about-their-contents" id="toc-data-frames-are-objects-that-can-tell-you-about-their-contents">Data frames are objects that can tell you about their contents</a>
  - <a href="#data-frames-have-methods-i.e.-functions-that-perform-operations-using-the-data-frames-contents-as-input" id="toc-data-frames-have-methods-i.e.-functions-that-perform-operations-using-the-data-frames-contents-as-input">Data frames have methods (i.e. functions) that perform operations using the data frame's contents as input</a>
  - <a href="#data-frames-have-fields-i.e.-variables-that-hold-additional-information" id="toc-data-frames-have-fields-i.e.-variables-that-hold-additional-information">Data frames have fields (i.e. variables) that hold additional information</a>
  - <a href="#optional-pandas-introduces-some-new-types" id="toc-optional-pandas-introduces-some-new-types">(Optional) Pandas introduces some new types</a>
  - <a href="#optional-beginner-challenge" id="toc-optional-beginner-challenge"><strong>(Optional) Beginner Challenge</strong></a>
- <a href="#subsetting-data" id="toc-subsetting-data">Subsetting Data</a>
  - <a href="#treat-the-data-frame-as-a-matrix-and-select-values-by-position" id="toc-treat-the-data-frame-as-a-matrix-and-select-values-by-position">Treat the data frame as a matrix and select values by position</a>
  - <a href="#treat-the-data-frame-as-a-table-and-select-values-by-label" id="toc-treat-the-data-frame-as-a-table-and-select-values-by-label">Treat the data frame as a table and select values by label</a>
  - <a href="#shorten-the-column-names-using-vectorized-string-methods" id="toc-shorten-the-column-names-using-vectorized-string-methods">Shorten the column names using vectorized string methods</a>
  - <a href="#use-list-slicing-notation-to-get-subsets-of-the-data-frame" id="toc-use-list-slicing-notation-to-get-subsets-of-the-data-frame">Use list slicing notation to get subsets of the data frame</a>
  - <a href="#optional-treat-the-data-frame-as-an-object-and-select-values-using-flexible-methods" id="toc-optional-treat-the-data-frame-as-an-object-and-select-values-using-flexible-methods">(Optional) Treat the data frame as an object and select values using flexible methods</a>
- <a href="#filtering-i.e.-masking-data" id="toc-filtering-i.e.-masking-data">Filtering (i.e. masking) data</a>
  - <a href="#use-comparisons-to-select-data-based-on-value" id="toc-use-comparisons-to-select-data-based-on-value">Use comparisons to select data based on value</a>
  - <a href="#you-can-filter-using-any-method-that-returns-a-data-frame" id="toc-you-can-filter-using-any-method-that-returns-a-data-frame">You can filter using any method that returns a data frame</a>
  - <a href="#use-method-chaining-to-create-final-output-without-creating-intermediate-variables" id="toc-use-method-chaining-to-create-final-output-without-creating-intermediate-variables">Use method chaining to create final output without creating intermediate variables</a>
  - <a href="#methods-were-not-going-to-cover" id="toc-methods-were-not-going-to-cover">Methods we're not going to cover</a>
- <a href="#working-with-missing-data" id="toc-working-with-missing-data">Working with missing data</a>
  - <a href="#by-default-most-numerical-operations-ignore-missing-data" id="toc-by-default-most-numerical-operations-ignore-missing-data">By default, most numerical operations ignore missing data</a>
  - <a href="#check-for-missing-values" id="toc-check-for-missing-values">Check for missing values</a>
  - <a href="#replace-missing-values" id="toc-replace-missing-values">Replace missing values</a>
  - <a href="#drop-missing-values" id="toc-drop-missing-values">Drop missing values</a>
  - <a href="#challenge-filter-and-trim-with-a-boolean-vector" id="toc-challenge-filter-and-trim-with-a-boolean-vector"><strong>Challenge: Filter and trim with a boolean vector</strong></a>
- <a href="#sorting-and-grouping" id="toc-sorting-and-grouping">Sorting and grouping</a>
  - <a href="#motivating-example-calculate-the-wealth-z-score-for-each-country" id="toc-motivating-example-calculate-the-wealth-z-score-for-each-country">Motivating example: Calculate the wealth Z-score for each country</a>
  - <a href="#append-new-columns-to-the-data-frame-containing-our-summary-statistics" id="toc-append-new-columns-to-the-data-frame-containing-our-summary-statistics">Append new columns to the data frame containing our summary statistics</a>
  - <a href="#sort-and-group-by-new-columns" id="toc-sort-and-group-by-new-columns">Sort and group by new columns</a>
- <a href="#write-output" id="toc-write-output">Write output</a>
- <a href="#working-with-multiple-tables-in-an-sql-like-manner" id="toc-working-with-multiple-tables-in-an-sql-like-manner">Working with multiple tables (in an SQL-like manner)</a>
  - <a href="#concatenating-data-frames" id="toc-concatenating-data-frames">Concatenating data frames</a>
  - <a href="#joining-data-frames" id="toc-joining-data-frames">Joining data frames</a>
- <a href="#optional-adding-rows-to-dataframes" id="toc-optional-adding-rows-to-dataframes">(Optional) Adding rows to DataFrames</a>
- <a href="#scientific-computing-libraries" id="toc-scientific-computing-libraries">Scientific Computing Libraries</a>
  - <a href="#optional-statsmodels-regression-example" id="toc-optional-statsmodels-regression-example">(Optional) Statsmodels regression example</a>
  - <a href="#optional-getting-started-with-machine-learning-estimators" id="toc-optional-getting-started-with-machine-learning-estimators">(Optional) Getting started with machine learning estimators</a>
- <a href="#optional-things-we-didnt-talk-about" id="toc-optional-things-we-didnt-talk-about">(Optional) Things we didn't talk about</a>
- <a href="#optional-pandas-method-chaining-in-the-wild" id="toc-optional-pandas-method-chaining-in-the-wild">(Optional) Pandas method chaining in the wild</a>
- <a href="#optional-introspecting-on-the-dataframe-object" id="toc-optional-introspecting-on-the-dataframe-object">(Optional) Introspecting on the DataFrame object</a>
- <a href="#carpentries-version-group-by-split-apply-combine" id="toc-carpentries-version-group-by-split-apply-combine">(Carpentries version) Group By: split-apply-combine</a>
- <a href="#week-3-building-programs" id="toc-week-3-building-programs"><strong>WEEK 3: Building Programs</strong></a>
- <a href="#notebooks-vs-python-scripts" id="toc-notebooks-vs-python-scripts">Notebooks vs Python scripts</a>
  - <a href="#differences-between-.ipynb-and-.py" id="toc-differences-between-.ipynb-and-.py">Differences between .ipynb and .py</a>
  - <a href="#workflow-differences-between-notebooks-and-scripts" id="toc-workflow-differences-between-notebooks-and-scripts">Workflow differences between notebooks and scripts</a>
- <a href="#python-from-the-terminal" id="toc-python-from-the-terminal">Python from the terminal</a>
- <a href="#for-loops" id="toc-for-loops">For Loops</a>
  - <a href="#a-for-loop-executes-commands-once-for-each-value-in-a-collection" id="toc-a-for-loop-executes-commands-once-for-each-value-in-a-collection">A <code>for</code> loop executes commands once for each value in a collection</a>
  - <a href="#the-first-line-of-the-for-loop-must-end-with-a-colon-and-the-body-must-be-indented" id="toc-the-first-line-of-the-for-loop-must-end-with-a-colon-and-the-body-must-be-indented">The first line of the <code>for</code> loop must end with a colon, and the body must be indented</a>
  - <a href="#loop-variables-can-be-called-anything" id="toc-loop-variables-can-be-called-anything">Loop variables can be called anything</a>
  - <a href="#the-body-of-a-loop-can-contain-many-statements" id="toc-the-body-of-a-loop-can-contain-many-statements">The body of a loop can contain many statements</a>
  - <a href="#optional-use-range-to-iterate-over-a-sequence-of-numbers" id="toc-optional-use-range-to-iterate-over-a-sequence-of-numbers">(Optional) Use <code>range()</code> to iterate over a sequence of numbers</a>
  - <a href="#optional-use-enumerate-to-iterate-over-a-sequence-of-items-and-their-positions" id="toc-optional-use-enumerate-to-iterate-over-a-sequence-of-items-and-their-positions">(Optional) Use <code>enumerate()</code> to iterate over a sequence of items and their positions</a>
  - <a href="#common-pattern-1-accumulate-a-running-total" id="toc-common-pattern-1-accumulate-a-running-total">Common pattern 1: Accumulate a running total</a>
  - <a href="#common-pattern-2-create-a-new-collection-from-an-existing-collection" id="toc-common-pattern-2-create-a-new-collection-from-an-existing-collection">Common pattern 2: Create a new collection from an existing collection</a>
  - <a href="#optional-dictionary-iteration" id="toc-optional-dictionary-iteration">(Optional) Dictionary iteration</a>
  - <a href="#optional-how-do-you-know-if-an-object-is-iterable" id="toc-optional-how-do-you-know-if-an-object-is-iterable">(Optional) How do you know if an object is iterable?</a>
  - <a href="#dont-use-for-loops-with-dataframes-or-numpy-matrices" id="toc-dont-use-for-loops-with-dataframes-or-numpy-matrices">Don't use <code>for</code> loops with DataFrames or Numpy matrices</a>
- <a href="#looping-over-data-sets" id="toc-looping-over-data-sets">Looping Over Data Sets</a>
  - <a href="#file-paths-as-an-example-of-increasing-abstraction-in-program-development" id="toc-file-paths-as-an-example-of-increasing-abstraction-in-program-development">File paths as an example of increasing abstraction in program development</a>
  - <a href="#use-a-for-loop-to-process-files-given-a-list-of-their-names" id="toc-use-a-for-loop-to-process-files-given-a-list-of-their-names">Use a <code>for</code> loop to process files given a list of their names</a>
  - <a href="#use-glob.glob-to-find-sets-of-files-whose-names-match-a-pattern" id="toc-use-glob.glob-to-find-sets-of-files-whose-names-match-a-pattern">Use glob.glob to find sets of files whose names match a pattern</a>
  - <a href="#use-glob-and-a-for-loop-to-process-batches-of-files" id="toc-use-glob-and-a-for-loop-to-process-batches-of-files">Use glob and a <code>for</code> loop to process batches of files</a>
- <a href="#conditionals" id="toc-conditionals">Conditionals</a>
  - <a href="#evaluating-the-truth-of-a-statement" id="toc-evaluating-the-truth-of-a-statement">Evaluating the truth of a statement</a>
  - <a href="#use-if-statements-to-control-whether-or-not-a-block-of-code-is-executed" id="toc-use-if-statements-to-control-whether-or-not-a-block-of-code-is-executed">Use <code>if</code> statements to control whether or not a block of code is executed</a>
  - <a href="#use-else-to-execute-a-block-of-code-when-an-if-condition-is-not-true" id="toc-use-else-to-execute-a-block-of-code-when-an-if-condition-is-not-true">Use else to execute a block of code when an if condition is not true</a>
  - <a href="#use-elif-to-specify-additional-tests" id="toc-use-elif-to-specify-additional-tests">Use <code>elif</code> to specify additional tests</a>
  - <a href="#optional-conditionals-are-often-used-inside-loops" id="toc-optional-conditionals-are-often-used-inside-loops">(Optional) Conditionals are often used inside loops</a>
  - <a href="#optional-conditions-are-tested-once-in-order" id="toc-optional-conditions-are-tested-once-in-order">(Optional) Conditions are tested once, in order</a>
  - <a href="#optional-compound-relations-using-and-or-and-parentheses" id="toc-optional-compound-relations-using-and-or-and-parentheses">(Optional) Compound Relations Using <code>and</code>, <code>or</code>, and Parentheses</a>
  - <a href="#optional-use-pathlib-to-write-code-that-works-across-operating-systems" id="toc-optional-use-pathlib-to-write-code-that-works-across-operating-systems">(Optional) Use pathlib to write code that works across operating systems</a>
- <a href="#generic-file-handling" id="toc-generic-file-handling">Generic file handling</a>
  - <a href="#open-the-file-with-a-context-manager" id="toc-open-the-file-with-a-context-manager">Open the file with a context manager</a>
  - <a href="#a-file-is-a-collection-of-lines" id="toc-a-file-is-a-collection-of-lines">A file is a collection of lines</a>
  - <a href="#strings-contain-formatting-marks" id="toc-strings-contain-formatting-marks">Strings contain formatting marks</a>
- <a href="#text-processing" id="toc-text-processing">Text processing</a>
  - <a href="#use-string-methods-to-determine-which-lines-to-keep" id="toc-use-string-methods-to-determine-which-lines-to-keep">Use string methods to determine which lines to keep</a>
  - <a href="#open-an-output-file-for-writing" id="toc-open-an-output-file-for-writing">Open an output file for writing</a>
  - <a href="#format-output-as-a-comma-delimited-text-file" id="toc-format-output-as-a-comma-delimited-text-file">Format output as a comma-delimited text file</a>
  - <a href="#optional-avoid-memory-limitations-by-processing-the-input-file-one-line-at-a-time" id="toc-optional-avoid-memory-limitations-by-processing-the-input-file-one-line-at-a-time">(Optional) Avoid memory limitations by processing the input file one line at a time</a>
  - <a href="#optional-notes" id="toc-optional-notes">(Optional) Notes</a>
- <a href="#writing-functions" id="toc-writing-functions">Writing Functions</a>
  - <a href="#break-programs-down-into-functions-to-make-them-easier-to-understand" id="toc-break-programs-down-into-functions-to-make-them-easier-to-understand">Break programs down into functions to make them easier to understand</a>
  - <a href="#define-a-function-using-def-with-a-name-parameters-and-a-block-of-code" id="toc-define-a-function-using-def-with-a-name-parameters-and-a-block-of-code">Define a function using <code>def</code> with a name, parameters, and a block of code</a>
  - <a href="#defining-a-function-does-not-run-it" id="toc-defining-a-function-does-not-run-it">Defining a function does not run it</a>
  - <a href="#arguments-in-call-are-matched-to-parameters-in-definition" id="toc-arguments-in-call-are-matched-to-parameters-in-definition">Arguments in call are matched to parameters in definition</a>
  - <a href="#functions-may-return-a-result-to-their-caller-using-return" id="toc-functions-may-return-a-result-to-their-caller-using-return">Functions may return a result to their caller using <code>return</code></a>
  - <a href="#challenge-option-1-encapsulate-text-processing-in-a-function" id="toc-challenge-option-1-encapsulate-text-processing-in-a-function"><strong>Challenge (option 1): Encapsulate text processing in a function</strong></a>
  - <a href="#challenge-option-2-encapsulate-data-processing-in-a-function" id="toc-challenge-option-2-encapsulate-data-processing-in-a-function"><strong>Challenge (option 2): Encapsulate data processing in a function</strong></a>
  - <a href="#optional-a-worked-example-the-lorenz-attractor" id="toc-optional-a-worked-example-the-lorenz-attractor">(Optional) A worked example: The Lorenz attractor</a>
- <a href="#carpentries-version-conditionals" id="toc-carpentries-version-conditionals">(Carpentries version) Conditionals</a>
  - <a href="#use-if-statements-to-control-whether-or-not-a-block-of-code-is-executed-1" id="toc-use-if-statements-to-control-whether-or-not-a-block-of-code-is-executed-1">Use <code>if</code> statements to control whether or not a block of code is executed</a>
  - <a href="#conditionals-are-often-used-inside-loops" id="toc-conditionals-are-often-used-inside-loops">Conditionals are often used inside loops</a>
  - <a href="#use-else-to-execute-a-block-of-code-when-an-if-condition-is-not-true-1" id="toc-use-else-to-execute-a-block-of-code-when-an-if-condition-is-not-true-1">Use else to execute a block of code when an if condition is not true</a>
  - <a href="#use-elif-to-specify-additional-tests-1" id="toc-use-elif-to-specify-additional-tests-1">Use <code>elif</code> to specify additional tests</a>
  - <a href="#conditions-are-tested-once-in-order" id="toc-conditions-are-tested-once-in-order">Conditions are tested once, in order</a>
  - <a href="#use-conditionals-in-a-loop-to-evolve-the-values-of-variables" id="toc-use-conditionals-in-a-loop-to-evolve-the-values-of-variables">Use conditionals in a loop to “evolve” the values of variables</a>
  - <a href="#compound-relations-using-and-or-and-parentheses-optional" id="toc-compound-relations-using-and-or-and-parentheses-optional">Compound Relations Using <code>and</code>, <code>or</code>, and Parentheses (optional)</a>
- <a href="#optional-variable-scope" id="toc-optional-variable-scope">(Optional) Variable Scope</a>
- <a href="#optional-programming-style" id="toc-optional-programming-style">(Optional) Programming Style</a>
- <a href="#week-4-visualization-with-matplotlib-and-seaborn" id="toc-week-4-visualization-with-matplotlib-and-seaborn"><strong>WEEK 4: Visualization with Matplotlib and Seaborn</strong></a>
- <a href="#orientation-1" id="toc-orientation-1">Orientation</a>
  - <a href="#briefly-revisit-week-1" id="toc-briefly-revisit-week-1">Briefly revisit week 1</a>
  - <a href="#a-brief-history-of-plotting-in-matplotlib" id="toc-a-brief-history-of-plotting-in-matplotlib">A brief history of plotting in Matplotlib</a>
- <a href="#plotting-with-matplotlib" id="toc-plotting-with-matplotlib">Plotting with Matplotlib</a>
  - <a href="#the-basic-plot" id="toc-the-basic-plot">The basic plot</a>
  - <a href="#two-kinds-of-plotting-objects" id="toc-two-kinds-of-plotting-objects">Two kinds of plotting objects</a>
  - <a href="#optional-three-ways-of-showing-a-figure" id="toc-optional-three-ways-of-showing-a-figure">(Optional) Three ways of showing a figure</a>
  - <a href="#the-lifecycle-of-a-custom-plot" id="toc-the-lifecycle-of-a-custom-plot">The lifecycle of a custom plot</a>
  - <a href="#plotting-multiple-data-sets" id="toc-plotting-multiple-data-sets">Plotting multiple data sets</a>
  - <a href="#optional-plot-directly-from-pandas" id="toc-optional-plot-directly-from-pandas">(Optional) Plot directly from Pandas</a>
- <a href="#visualization-strategy" id="toc-visualization-strategy">Visualization Strategy</a>
  - <a href="#there-are-many-kinds-of-plots" id="toc-there-are-many-kinds-of-plots">There are many kinds of plots</a>
  - <a href="#read-the-docs" id="toc-read-the-docs">Read the docs</a>
  - <a href="#workflow-strategy" id="toc-workflow-strategy">Workflow strategy</a>
- <a href="#fast-visualization-and-theming-with-seaborn" id="toc-fast-visualization-and-theming-with-seaborn">Fast visualization and theming with Seaborn</a>
  - <a href="#seaborn-is-a-nice-way-to-look-at-your-data" id="toc-seaborn-is-a-nice-way-to-look-at-your-data">Seaborn is a nice way to look at your data</a>
  - <a href="#using-preset-styles" id="toc-using-preset-styles">Using preset styles</a>
  - <a href="#optional-there-are-many-styling-options" id="toc-optional-there-are-many-styling-options">(Optional) There are many styling options</a>
  - <a href="#optional-bar-charts" id="toc-optional-bar-charts">(Optional) Bar Charts</a>
  - <a href="#optional-histograms" id="toc-optional-histograms">(Optional) Histograms</a>
  - <a href="#optional-box-plots-and-swarm-plots" id="toc-optional-box-plots-and-swarm-plots">(Optional) Box Plots and Swarm Plots</a>
- <a href="#optional-how-matplotlib-works" id="toc-optional-how-matplotlib-works">(Optional) How Matplotlib works</a>
  - <a href="#understanding-matplotlib" id="toc-understanding-matplotlib">Understanding Matplotlib</a>
  - <a href="#matplotlib-object-syntax" id="toc-matplotlib-object-syntax">Matplotlib object syntax</a>
- <a href="#special-topics" id="toc-special-topics"><strong>Special Topics</strong></a>
- <a href="#working-with-unstructured-files" id="toc-working-with-unstructured-files">Working with unstructured files</a>
  - <a href="#open-the-file-with-a-context-handler" id="toc-open-the-file-with-a-context-handler">Open the file with a context handler</a>
  - <a href="#strings-contain-formatting-marks-1" id="toc-strings-contain-formatting-marks-1">Strings contain formatting marks</a>
  - <a href="#many-ways-of-handling-a-file" id="toc-many-ways-of-handling-a-file">Many ways of handling a file</a>
  - <a href="#working-with-unstructured-file-data" id="toc-working-with-unstructured-file-data">Working with unstructured file data</a>
- <a href="#exception-handling" id="toc-exception-handling">Exception handling</a>
- <a href="#performance-and-profiling" id="toc-performance-and-profiling">Performance and profiling</a>
- <a href="#reducing-memory-usage" id="toc-reducing-memory-usage">Reducing memory usage</a>
  - <a href="#read-a-file-one-line-at-a-time" id="toc-read-a-file-one-line-at-a-time">Read a file one line at a time</a>
  - <a href="#use-a-sqlite-database" id="toc-use-a-sqlite-database">Use a SQLite database</a>
- <a href="#other-optional-topics" id="toc-other-optional-topics">Other optional topics</a>
- <a href="#endnotes" id="toc-endnotes"><strong>Endnotes</strong></a>
- <a href="#credits" id="toc-credits">Credits</a>
- <a href="#references" id="toc-references">References</a>
- <a href="#data-sources" id="toc-data-sources">Data Sources</a>

# **WEEK 1: Fundamentals**

# Orientation

## What programming language should I use?

1.  Use the language that your friends use (so you can ask them for help)
2.  Use a language that has a community of practice for your desired use case (you can find documentation, bug reports, sample code, etc.)
3.  Use a language that is "best" by some technical definition

## Python is pretty good at lots of things

- "Glue" language intended to replace shell and Perl
- Concise, readable, good for rapid prototyping
- Access to linear algebra libraries in FORTRAN/C → user-friendly numeric computing

## Literate programming and notebooks

- Blend code, documentation, and visualization
- Good for trying things, demos
- Bad for massive or long-running processes
- You can export notebooks as .py files when they outgrow the notebook format

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

- Navigate to where you want to be before creating new notebook
- Rename your notebook to something informative
- Use drag-and-drop interface to move .ipynb file to new location

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

4.  Many keyboard shortcuts are available; see <https://gist.github.com/discdiver/9e00618756d120a8c9fa344ac1c375ac>

5.  (Optional) Jupyter Lab undestands (some) terminal commands

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
    - Some commands are not available on Windows (e.g. `%%bash`)

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

- Functions are verbs
- Functions end in `()`
- Functions take arguments (i.e. they do stuff with the values that you give them)
- `print()` useful for tracking progress, debugging

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
print('first:', first)
print('second:', second)
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

3.  Python is strongly-typed: It will (mostly) refuse to convert things automatically. The exception is mathematical operations with integers and floats.

    ``` python
    int_sum = 3 + 4
    mixed_sum = 3 + 4.0

    print(type(int_sum))
    print(type(mixed_sum))
    ```

## You can explicitly convert data to a different type

1.  Can't do math with text

    ``` python
    1 + '2'
    ```

2.  If you have string data, you can explicitly convert it to numeric data…

    ``` python
    print(1 + float('2'))
    print(1 + int('2'))
    ```

3.  …and vice-versa

    ``` python
    text = str(3)

    print(text)
    print(type(text))
    ```

4.  What's going on under the hood?

    1.  `int`, `float`, and `str` are types. More precisely, they are *classes*.
    2.  `int()`, `float()`, and `str()` are functions that create new *instances* of their respective classes. The argument to the creation function (e.g., `'2'`) is the raw material for creating the new instance.

5.  This can work for more complex data types as well, e.g. Pandas data frames and Numpy arrays.

## **Challenge**: Explain what each operator does

``` python
# Floor
print('5 // 3:', 5 // 3)

# Floating point
print('5 / 3:', 5 / 3)

# Modulus (remainder)
print('5 % 3:', 5 % 3)
```

# Built-in Functions and Help

## How do we find out what's possible?

- Python.org tutorial
- Standard library reference (we will discuss libraries in the next section)
- References section of this document
- Stack Overflow

## (Optional) Use comments to add documentation to programs

Leave notes for Future You about what you've learned and how your code works.

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

## Functions can have optional arguments

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

    - 1 mandatory argument
    - 1 optional argument with a default value: `ndigits=None`

2.  You can proved arguments implicitly by order, or explicitly in any order

    ``` python
    # You can optionally specify the number of significant digits
    round(4.712823, ndigits=2)
    ```

## Every function returns something

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
    print(type(result))
    ```

## (Optional) Functions will typically generalize in sensible ways

1.  `max()` and `min()` do the intuitively correct thing with numerical and text data

    ``` python
    print(max(1, 2, 3))
    print(min('a', 'A', '0'))       # sort order is 0-9, A-Z, a-z
    ```

2.  Mixed numbers and text aren't meaningfully comparable

    ``` python
    max(1, 'a')
    ```

## *Methods* are functions that belong to objects

1.  An object packages data together with functions that operate on that data. This is a very common organizational strategy in Python.

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

3.  (Optional) Strings are immutable. This will be covered later, but may come up here. If it comes up here, this is a good example:

    ``` python
    print(my_string.upper())
    print(my_string)
    upper_string = my_string.upper()
    print(upper_string)
    ```

4.  You can view an object's attributes (i.e. methods and fields) using `help()` or `dir()`. Some attributes are "private"; you're not supposed to use these directly.

    ``` python
    # More verbose help
    help(str)
    ```

    ``` python
    # The short, short version
    dir(my_string)
    ```

5.  The built-in string methods can be very useful for cleaning up data

    ``` python
    bad_string_1 = "  Hello world!   "
    bad_string_2 = "|...goodbye cruel world|"

    print(bad_string_1.strip(),
          bad_string_2.strip("|"))
    ```

## (Optional) Python produces informative error messages

1.  Python reports a syntax error when it can’t understand the source of a program

    ``` python
    name = 'Bob
    age = = 54
    print("Hello world"
    ```

2.  Python reports a runtime error when something goes wrong while a program is executing

## **(Optional) Beginner Challenge**: What happens when?

Explain in simple terms the order of operations in the following program: when does the addition happen, when does the subtraction happen, when is each function called, etc. What is the final value of radiance?

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

- Refer to things from the module as `module-name.thing-name`
- Python uses "." to mean "part of" or "belongs to".

## Use `help()` to learn about the contents of a library module

``` python
help(math)                      # user friendly
```

``` python
dir(math)                       # brief reminder, not user friendly
```

## (Optional) Import shortcuts

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

## Python has opinions about how to write your programs

``` python
import this
```

# Lists

Lists are the central data structure in Python; we will explain many things by making analogies to lists.

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

1.  You slice a list from the start position up to, but not including, the stop position

    ``` python
    print(pressure[0:3])
    print(pressure[2:5])
    ```

2.  You can omit the start position if you're starting at the beginning…

    ``` python
    print("First 5 items:", pressure[0:5])
    print("First 5 items, but shorter:", pressure[:5])
    ```

3.  …and you *must* omit the end position if you're going to the end (otherwise it's up to, but not including, the end!)

    ``` python
    # This is useful if you don't know how long the list is
    print("Everything but the first 3 items:", pressure[3:])
    ```

4.  You can add an optional step interval (every 2nd item, every 3rd item, etc.)

    ``` python
    print("First 5 items, every other item:", pressure[0:5:2])
    print("Every third item:", pressure[::3])
    ```

## Why are lists indexed from 0?

cf. <https://stackoverflow.com/a/11364711>

1.  Slice endpoints are compliments In both cases, the number you see represents what you want to do.

    ``` python
    # Get the first two items
    print(pressure[:2])

    # Get everything except the first two items
    print(pressure[2:])
    ```

2.  For non-negative indices, the length of a slice is the difference of the indices

    ``` python
    len(pressure[1:3]) == 2
    ```

## Some other properties of indexes

1.  You can count backwards from the end with negative integers

    ``` python
    print("Last item:", pressure[-1])
    ```

2.  Indexing beyond the end of the collection is an error

    ``` python
    pressure[20]
    ```

## Lists are mutable

1.  You can replace a value at a specific index location

    ``` python
    pressure[0] = 0.999
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

2.  Use `pop()` to remove the last item and assign it to a variable. This is useful for destructive iteration.

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

1.  Can't change a string in place

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

1.  Use `.join()` to concatenate strings

    ``` python
    date_list = ["3", "17", "2007"]
    date = "/".join(date_list)
    print(date)
    ```

2.  This is going to be useful for building CSV files

    ``` python
    date_list = ["3", "17", "2007"]
    date = ",".join(date_list)
    print(date)
    ```

## **(Optional) Beginner Challenge**: From Strings to Lists and Back

1.  Given this Python code…

    ``` python
    print('string to list:', list('tin'))
    print('list to string:', ''.join(['g', 'o', 'l', 'd']))
    ```

2.  What does `list('some string')` do?

3.  What does `'-'.join(['x', 'y', 'z'])` generate?

## **Challenge**: Locating the right module

You want to select a random character from a string:

``` python
bases = 'ACTTGCTTGAC'
```

1.  Which standard library module could help you? <https://docs.python.org/3/library/>
2.  Which function would you select from that module? Are there alternatives?
3.  Try to write a program that uses the function.

### Solutions:

1.  You could try the `random` module. The string has 11 characters, each having a positional index from 0 to 10. You could use either `random.randrange` or `random.randint` functions to get a random integer between 0 and 10, and then pick out the character at that position:

    ``` python
    from random import randrange

    random_index = randrange(len(bases))
    print(bases[random_index])
    ```

    …or more compactly:

    ``` python
    from random import randrange

    print(bases[randrange(len(bases))])
    ```

2.  Perhaps you found the `random.sample()` function. It allows for slightly less typing:

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

2.  Does a value already exist (you generally don't want to do this; keys are unique but values are not)?

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

## **(Optional) Advanced Challenge**: Convert a list to a dictionary

How can you convert our list of names and ages into a dictionary? Hint: You will need to populate the dictionary with a list of keys and a list of values.

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
    ```

2.  Arrays are indexed like lists

    ``` python
    print(rand[0,0])
    ```

3.  Arrays are fast but inflexible - the entire array must be of a single type.

# A very brief introduction to Pandas

1.  Pandas is a library for working with spreadsheet-like data ("DataFrames")
2.  A DataFrame is a collection (dict) of Series columns
3.  Each Series is a 1-dimensional NumPy array with optional row labels (dict-like, similar to R vectors)
4.  Therefore, each series inherits many of the abilities (linear algebra) and limitations (single data type) of NumPy

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

- File and directory names are strings
- You can use relative or absolute file paths

## Use `index_col` to use a column’s values as row indices

Rows are indexed by number by default (0, 1, 2,….). For convenience, we want to index by country:

``` python
data = pd.read_csv('data/gapminder_gdp_oceania.csv', index_col='country')
print(data)
```

- By default, rows are indexed by position, like lists.
- Setting the `index_col` parameter lets us index rows by label, like dictionaries. For this to work, the index column needs to have unique values for every row.
- You can verify the contents of the CSV by double-clicking on the file in Jupyter Lab

## Pandas help files are dense; you should prefer the online documentation

1.  Main documentation link: <https://pandas.pydata.org/docs/user_guide/index.html>
2.  Pandas can read many different data formats: <https://pandas.pydata.org/docs/user_guide/io.html>

# Data frames are objects that can tell you about their contents

## Data frames have methods (i.e. functions) that perform operations using the data frame's contents as input

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

## Data frames have fields (i.e. variables) that hold additional information

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

- You can convert data between NumPy arrays, Series, and DataFrames
- You can read data into any of the data structures from files or from standard Python containers

## **(Optional) Beginner Challenge**

1.  Read the data in `gapminder_gdp_americas.csv` into a variable called `americas` and display its summary statistics.
2.  After reading the data for the Americas, use `help(americas.head)` and `help(americas.tail)` to find out what `DataFrame.head` and `DataFrame.tail` do.
    1.  How can you display the first three rows of this data?
    2.  How can you display the last three columns of this data? (Hint: You may need to change your view of the data).
3.  As well as the `read_csv` function for reading data from a file, Pandas provides a `to_csv` function to write DataFrames to files. Applying what you’ve learned about reading from files, write one of your DataFrames to a file called `processed.csv`. You can use `help` to get information on how to use `to_csv`.

### Solution

``` python
americas = pd.read_csv('data/gapminder_gdp_americas.csv', index_col='country')
americas.describe()
americas.head(3)
americas.T.tail(3)
americas.to_csv('processed.csv')
```

# Subsetting Data

## Treat the data frame as a matrix and select values by position

Use `DataFrame.iloc[..., ...]` to select values by their (entry) position. The `i` in `iloc` stands for "index".

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

3.  (Optional) If you want specific rows or columns, pass in a list

    ``` python
    data.loc[['Italy','Poland'], :]
    ```

4.  `.iloc` follows list index conventions ("up to, but not including)", but `.loc` does the intuitive right thing ("A through B")

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

## (Optional) Treat the data frame as an object and select values using flexible methods

Pandas always drills down to the most parsimonious representation. On one hand, this is convenient; on the other, it violates the Pythonic expectation for strong types.

| Shape of data selection | Pandas return type |
|:------------------------|:-------------------|
| 2D                      | DataFrame          |
| 1D                      | Series             |
| 0D                      | single value       |

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

# Filtering (i.e. masking) data

## Use comparisons to select data based on value

1.  Show which data frame elements match a criterion.

    ``` python
    # Which GDPs are greater than 10,000?
    subset > 10000
    ```

2.  Use `.where()` method to find elements that match the criterion:

    ``` python
    fs = subset.where(subset > 10000)
    print(fs)
    ```

    1.  `subset > 10000` returns a data frame of True/False values
    2.  `subset.where()` filters its contents based on that True/False data frame
    3.  This section is more properly called "Masking Data," because it involves operations for overlaying a data frame's values without changing the data frame's shape. We don't drop anything from the data frame, we just replace it with `NaN`.

3.  (Optional) Use the criterion match to filter the data frame's contents. This uses index notation:

    ``` python
    subset[subset > 10000]
    ```

## You can filter using any method that returns a data frame

``` python
# GDP for all countries greater than the median
subset.where(subset > subset.median())
```

## Use method chaining to create final output without creating intermediate variables

``` python
# The .rank() method turns numerical scores into ranks
subset.rank()
```

``` python
# GDP ranking for all countries greater than the median
subset.where(subset > subset.median()).rank()
```

## Methods we're not going to cover

`.query()` is a flexible, general-purpose way of filtering data frames.

# Working with missing data

## By default, most numerical operations ignore missing data

Examples include min, max, mean, std, etc.

1.  Missing values ignored by default

    ``` python
    print("Column means")
    print(fs.mean())

    print("Row means")
    print(fs.mean(axis=1))
    ```

2.  Force inclusions with the `skipna` argument

    ``` python
    print("Column means")
    print(fs.mean(skipna=False))

    print("Row means")
    print(fs.mean(axis=1, skipna=False))
    ```

## Check for missing values

1.  Show which items are missing. "NA" includes `NaN` and `None`. It doesn't include empty strings or `numpy.inf`.

    ``` python
    # Show which items are NA
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
    fs.isna().any(axis=None)
    ```

4.  (Optional) Are all of the values missing?

    ``` python
    fs.isna().all(axis=None)
    ```

## Replace missing values

1.  Replace with a fixed value

    ``` python
    fs_fixed = fs.fillna(99)
    print(fs_fixed)
    ```

2.  (Optional) Impute missing values. Read the docs, this may or may not be sufficient for your needs.

    ``` python
    fs_imputed = fs.interpolate()
    ```

## Drop missing values

Drop all rows with missing values

``` python
fs_drop = fs.dropna()
```

## **Challenge: Filter and trim with a boolean vector**

A DataFrame is a dictionary of Series columns. With this in mind, experiment with the following code and try to explain what each line is doing. What operation is it performing, and what is being returned?

Feel free to use `print()`, `help()`, `type()`, etc as you investigate.

``` python
fs["1962"]
fs["1962"].notna()
fs[fs["1962"].notna()]
```

### Solution

1.  Line 1 returns the column as a Series vector
2.  Line 2 returns a boolean Series vector (True/False)
3.  Line 3 performs *boolean indexing* on the DataFrame using the Series vector. It only returns the rows that are True (i.e. it performs true filtering).

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

Capture the results of your filter in a new file, rather than overwriting your original data.

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

2.  Join tables on common column. The "left" join is a strategy for augmenting the first table (surveys) with information from the second table (species).

    ``` python
    df_join = surveys.merge(species, on="species_id", how="left")
    print(df_join.head())
    print(df_join.shape)
    ```

3.  The resulting table loses its index because `surveys.record_id` is not being used in the join. To keep `record_id` as the index for the final table, we need to retain it as an explicit column.

    ``` python
    # Don't set record_id as index during initial import
    surveys = pd.read_csv('data/surveys.csv')
    df_join = surveys.merge(species, on="species_id", how="left").set_index("record_id")

    df_join.index
    ```

4.  Get the subset of species that match a criterion, and join on that subset. The "inner" join only includes rows where both tables match on the key column; it's a strategy for filtering the first table by the second table.

    ``` python
    # Get the taxa column, masking the rows based on which values match "Bird"
    birds = species[species["taxa"] == "Bird"]
    df_birds = surveys.join(birds, on="species_id").set_index("record_id")

    print(df_birds.head())
    print(df_birds.shape)
    ```

# (Optional) Adding rows to DataFrames

A row is a view onto the *nth* item of each of the column Series. Appending rows is a performance bottleneck because it requires a separate append operation for each Series. You should concatenate data frames instead.s

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

<https://scikit-learn.org/stable/tutorial/machine_learning_map/index.html> <https://scikit-learn.org/stable/_static/ml_map.png>

# (Optional) Things we didn't talk about

1.  pipe
2.  map/applymap/apply (in general you should prefer vectorized functions)

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

4.  Objects have fields (i.e. data/variables) and methods (i.e. functions/procedures). The difference between a method and a function is that methods are attached to objects, whereas functions are free-floating ("first-class citizens"). Methods and functions are "callable":

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

# (Carpentries version) Group By: split-apply-combine

1.  Split data according to criterion, do numeric transformations, then recombine.

    ``` python
    # Get all GDPs greater than the mean
    mask_higher = data > data.mean()

    # Count the number of time periods in which each country exceeds the mean
    higher_count = mask_higher.aggregate('sum', axis=1)

    # Create a normalized wealth-over-time score
    wealth_score = higher_count / len(data.columns)
    wealth_score
    ```

2.  A DataFrame is a spreadsheet, but it is also a dictionary of columns.

    ``` python
    data['gdpPercap_1962']
    ```

3.  Add column to data frame

    ``` python
    # Warningealth Score is a series
    type(wealth_score)

    data['normalized_wealth'] = wealth_score
    ```

# **WEEK 3: Building Programs**

# Notebooks vs Python scripts

## Differences between .ipynb and .py

1.  Export notebook to .py file
2.  Move .py file into data directory
3.  Compare files in TextEdit/Notepad

## Workflow differences between notebooks and scripts

Broadly, a trade-off between managing big code bases and making it easy to experiment. See: <https://github.com/elliewix/Ways-Of-Installing-Python/blob/master/ways-of-installing.md#why-do-you-need-a-specific-tool>

1.  Interactive testing and debugging
2.  Graphics integration
3.  Version control
4.  Remote scripts

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

3.  (Optional) Python programs can accept command line arguments as inputs

    1.  List of command line inputs: `sys.argv` (<https://docs.python.org/3/library/sys.html#sys.argv>)
    2.  Utility for working with arguments: `argparse` (<https://docs.python.org/3/library/argparse.html>)

# For Loops

## A `for` loop executes commands once for each value in a collection

"For each thing in this group, do these operations"

``` python
for number in [2, 3, 5]:
    print(number)
```

- A for loop is made up of a collection, a loop variable, and a body
- The collection, **\[2, 3, 5\]**, is what the loop is being run on.
- The body, **print(number)**, specifies what to do for each value in the collection.
- The loop variable, **number**, is what changes for each iteration of the loop (i.e. the “current thing”)

## The first line of the `for` loop must end with a colon, and the body must be indented

Whitespace is syntactically meaningful!

``` python
for number in [2, 3, 5]:
print(number)
```

``` python
firstName = "Jon"
lastName = "Smith"
```

## Loop variables can be called anything

``` python
for bob in [2, 3, 5]:
    print(bob)
```

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

- range() produces numbers on demand (a "generator" function)
- useful for tracking progress

## (Optional) Use `enumerate()` to iterate over a sequence of items and their positions

``` python
for number, p in enumerate(primes):
    print(number, ":", p)
```

## Common pattern 1: Accumulate a running total

Initialize an accumulator variable to zero, the empty string, or the empty list; then iteratively update the variable with values from a collection.

``` python
total = 0
for number in range(7):
   total = total + number
print(total)
```

## Common pattern 2: Create a new collection from an existing collection

``` python
prime_exponents = []
for p in primes:
   prime_exponents.append(p**2)

print(prime_exponents)
```

## (Optional) Dictionary iteration

1.  Iterate over key: value pairs

    ``` python
    ages = {'Derek': 42,
            'Bill': 24,
            'Susan': 37}

    for key, val in ages.items():
        print(key, val)
    ```

2.  You can iterate over keys and values separately

    ``` python
    # Iterate over keys; you can also explicitly call .keys()
    for key in ages:
        print(key)

    # Iterate over values
    for val in ages.values():
        print(val)
    ```

3.  Iteration can be useful for unpacking complex dictionaries

    ``` python
    localsation = {'latitude': [37.28306, 'N'],
                'longitude': [-120.50778, 'W']}

    for key, val in location.items():
        print(key, 'is', val[0], val[1])
    ```

## (Optional) How do you know if an object is iterable?

1.  Lists, dictionaries, and strings are iterable

    ``` python
    hasattr(location, "__iter__")
    ```

2.  Integers are not iterable

    ``` python
    hasattr(5, "__iter__")
    ```

## Don't use `for` loops with DataFrames or Numpy matrices

There is almost always a faster vectorized function that does what you want.

# Looping Over Data Sets

## File paths as an example of increasing abstraction in program development

1.  File paths as literal strings
2.  File paths as string patterns
3.  File paths as abstract Path objects

## Use a `for` loop to process files given a list of their names

``` python
import pandas as pd

file_list = ['data/gapminder_gdp_africa.csv', 'data/gapminder_gdp_asia.csv']
for filename in file_list:
    data = pd.read_csv(filename, index_col='country')
    print(filename)
    print(data.head(1))
```

## Use glob.glob to find sets of files whose names match a pattern

1.  Get a list of all the CSV files

    ``` python
    import glob
    glob.glob('data/*.csv')
    ```

2.  In Unix, the term “globbing” means “matching a set of files with a pattern”. It uses shell expansion rules, **not** regular expressions, so there's an upper limit to how flexible it can be. The most common patterns are:

    - \`\*\` meaning “match zero or more characters”
    - \`?\` meaning “match exactly one character”

3.  Get a list of all the Gapminder CSV files

    ``` python
    glob.glob('data/gapminder_*.csv')
    ```

4.  Exclude the "all" CSV file

    ``` python
    glob.glob('data/gapminder_[!all]*.csv')
    ```

## Use glob and a `for` loop to process batches of files

``` python
data_frames = []
for filename in glob.glob('data/gapminder_[!all]*.csv'):
    data = pd.read_csv(filename)
    data_frames.append(data)

all_data = pd.concat(data_frames)
print(all_data.shape)
```

# Conditionals

## Evaluating the truth of a statement

1.  Value of a variable

    ``` python
    mass = 3

    print(mass == 3)
    print(mass > 5)
    print(mass < 4)
    ```

2.  Membership in a collection

    ``` python
    primes = [2, 3, 5]

    print(2 in primes)
    print(7 in primes)
    ```

3.  Truth of a collection Note that `any()` and `all()` evaluate each item using `.__bool__()` or `.__len()__`, which tells you whether an item is "truthy" or "falsey" (i.e. interpreted as being true or false).

    ``` python
    my_list = [2.75, "green", 0]

    print(any(my_list))
    print(all(my_list))
    ```

4.  (Optional) Understanding "truthy" and "falsey" values in Python (cf. <https://stackoverflow.com/a/53198991>) Every value in Python, regardless of type, is interpreted as being `True` except for the following values (which are interpreted as `False`). "Truthy" values satisfy `if` or `while` statements; "Falsey" values do not.

    1.  Constants defined to be false: `None` and `False`.
    2.  Zero of any numeric type: `0`, `0.0`, `0j`, `Decimal(0)`, `Fraction(0, 1)`
    3.  Empty sequences and collections: `''`, `()`, `[]`, `{}`, `set()`, `range(0)`

## Use `if` statements to control whether or not a block of code is executed

An `if` statement (more properly called a conditional statement) controls whether some block of code is executed or not.

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

Structure is similar to a `for` statement:

- First line opens with `if` and ends with a colon
- Body containing one or more statements is indented (usually by 4 spaces)

## Use else to execute a block of code when an if condition is not true

`else` can be used following an `if`. This allows us to specify an alternative to execute when the if branch isn’t taken.

``` python
if m > 3.0:
    print(m, 'is large')
else:
    print(m, 'is small')
```

## Use `elif` to specify additional tests

May want to provide several alternative choices, each with its own test; use `elif` (short for “else if”) and a condition to specify these.

``` python
if m > 9.0:
    print(m, 'is HUGE')
elif m > 3.0:
    print(m, 'is large')
else:
    print(m, 'is small')
```

- Always associated with an `if`.
- Must come before the `else` (which is the “catch all”).

## (Optional) Conditionals are often used inside loops

Not much point using a conditional when we know the value (as above), but useful when we have a collection to process.

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

## (Optional) Conditions are tested once, in order

Python steps through the branches of the conditional in order, testing each in turn. Order matters! The following is wrong:

``` python
grade = 85
if grade >= 70:
    print('grade is C')
elif grade >= 80:
    print('grade is B')
elif grade >= 90:
    print('grade is A')
```

## (Optional) Compound Relations Using `and`, `or`, and Parentheses

Often, you want some combination of things to be true. You can combine relations within a conditional using `and` and `or`. Continuing the example above, suppose you have:

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

- Use () to group subsets of conditions
- Aside: For a more natural way of working with many lists, look at `zip()`

## (Optional) Use pathlib to write code that works across operating systems

1.  Pathlib provides cross-platform path objects

    ``` python
    from pathlib import Path

    relative_path = Path("data")   # data subdirectory
    # relative_path = Path()       # current directory
    print("Relative path:", relative_path)
    print("Absolute path:", relative_path.absolute())
    ```

2.  The file objects have methods that provide much better information about files and directories.

    ``` python
    #Note the careful testing at each level of the code.
    if relative_path.exists():
        for filename in relative_path.glob('gapminder_*.csv'):
            if filename.is_file():
                data = pd.read_csv(filename)
                print(filename)
                print(data.head(1))
    ```

# Generic file handling

Pandas understands specific file types, but what if you need to work with a generic file?

## Open the file with a context manager

``` python
with open("data/bouldercreek_09_2013.txt", "r") as infile:
    lines = infile.readlines()
```

- The context manager closes the file when you're done reading it
- `"bouldercreek_09_2013.txt"` is the name of the file
- `infile` is a variable that refers to the file on disk

## A file is a collection of lines

`.readlines()` produces the file contents as a list of lines; each line is a string.

``` python
print(len(text))
print(type(text))

# View the first 10 lines
print(text[:10])
```

## Strings contain formatting marks

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

# Text processing

## Use string methods to determine which lines to keep

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

## Open an output file for writing

``` python
outfile_name = "data/tabular_data.txt"

with open(outfile_name, "w") as outfile:
    outfile.writelines(tabular_lines)
```

## Format output as a comma-delimited text file

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

## (Optional) Avoid memory limitations by processing the input file one line at a time

``` python
infile_name = "data/bouldercreek_09_2013.txt"
outfile_name = "data/csv_data.csv"

with open(infile_name, "r") as infile, open(outfile_name, "w") as outfile:
    writer = csv.writer(outfile)
    for line in infile:
        if not line.startswith("#"):
            writer.writerow(line.strip().split("\t"))
```

## (Optional) Notes

1.  Pandas has utilities for reading fixed-width files: <https://pandas.pydata.org/docs/reference/api/pandas.read_fwf.html>

2.  Saving datasets with new-style string formatting

    ``` python
    for i in datasets_list:
       do_something(f'{i}.png'
    ```

# Writing Functions

## Break programs down into functions to make them easier to understand

- Human beings can only keep a few items in working memory at a time.
- Understand larger/more complicated ideas by understanding and combining pieces
- Functions serve the same purpose in programs:
  1.  Encapsulate complexity so that we can treat it as a single “thing”
  2.  Removes complexity from remaining code, making it easier to test
  3.  Enables re-use: Write one time, use many times

## Define a function using `def` with a name, parameters, and a block of code

``` python
def print_greeting():
    print('Hello!')
```

- Begin the definition of a new function with `def`, followed by the name of the function.
- Must obey the same rules as variable names.
- Parameters in parentheses; empty parentheses if the function doesn’t take any inputs.
- Indent function body

## Defining a function does not run it

``` python
print_greeting()
```

- Like assigning a value to a variable
- Must call the function to execute the code it contains.

## Arguments in call are matched to parameters in definition

1.  Positional arguments

    ``` python
    def print_date(year, month, day):
        joined = '/'.join([year, month, day])
        print(joined)

    print_date(1871, 3, 19)
    ```

2.  (Optional) Keyword arguments

    ``` python
    print_date(month=3, day=19, year=1871)
    ```

## Functions may return a result to their caller using `return`

1.  Use `return ...` to give a value back to the caller. `return` ends the function's execution and *returns* you to the code that originally called the function.

    ``` python
    def average(values):
        """Return average of values, or None if no values are supplied."""

        if len(values) == 0:
            return None
        else:
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

3.  Notes:

    1.  `return` can occur anywhere in the function, but functions are easier to understand if return occurs:
        1.  At the start to handle special cases
        2.  At the very end, with a final result
    2.  Docstring provides function help. Use triple quotes if you need the docstring to span multiple lines.

## **Challenge (option 1): Encapsulate text processing in a function**

Write a function that takes `line` as an input and returns the information required by `writer.writerow()`.

## **Challenge (option 2): Encapsulate data processing in a function**

Write a function that encapsulates the data normalization from the Pandas workshop into a function. The function should:

1.  Take a data frame as its input
2.  Calculate the mean Z score for each country
3.  Divide countries into "wealthy" and "non-wealthy" categories
4.  Add this information to the data frame as new columns
5.  Return the modified data frame

### Solution

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

## (Optional) A worked example: The Lorenz attractor

<https://matplotlib.org/stable/gallery/mplot3d/lorenz_attractor.html>

# (Carpentries version) Conditionals

## Use `if` statements to control whether or not a block of code is executed

An `if` statement (more properly called a conditional statement) controls whether some block of code is executed or not.

``` python
mass = 3.54
if mass > 3.0:
    print(mass, 'is large')

mass = 2.07
if mass > 3.0:
    print (mass, 'is large')
```

Structure is similar to a `for` statement:

- First line opens with `if` and ends with a colon
- Body containing one or more statements is indented (usually by 4 spaces)

## Conditionals are often used inside loops

Not much point using a conditional when we know the value (as above), but useful when we have a collection to process.

``` python
masses = [3.54, 2.07, 9.22, 1.86, 1.71]
for m in masses:
    if m > 3.0:
        print(m, 'is large')
```

## Use else to execute a block of code when an if condition is not true

`else` can be used following an `if`. This allows us to specify an alternative to execute when the if branch isn’t taken.

``` python
masses = [3.54, 2.07, 9.22, 1.86, 1.71]
for m in masses:
    if m > 3.0:
        print(m, 'is large')
    else:
        print(m, 'is small')
```

## Use `elif` to specify additional tests

May want to provide several alternative choices, each with its own test; use `elif` (short for “else if”) and a condition to specify these.

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

- Always associated with an `if`.
- Must come before the `else` (which is the “catch all”).

## Conditions are tested once, in order

Python steps through the branches of the conditional in order, testing each in turn. Order matters! The following is wrong:

``` python
grade = 85
if grade >= 70:
    print('grade is C')
elif grade >= 80:
    print('grade is B')
elif grade >= 90:
    print('grade is A')
```

## Use conditionals in a loop to “evolve” the values of variables

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

- This is how dynamical systems simulations work

## Compound Relations Using `and`, `or`, and Parentheses (optional)

Often, you want some combination of things to be true. You can combine relations within a conditional using `and` and `or`. Continuing the example above, suppose you have:

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

- Use () to group subsets of conditions
- Aside: For a more natural way of working with many lists, look at `zip()`

# (Optional) Variable Scope

# (Optional) Programming Style

# **WEEK 4: Visualization with Matplotlib and Seaborn**

# Orientation

## Briefly revisit week 1

1.  Python orientation
2.  Jupyter orientation

## A brief history of plotting in Matplotlib

1.  Multiple interfaces
2.  Local graphs and global settings
3.  Matplotlib is the substrate for higher-level libraries
4.  Drawing things is verbose in any language

# Plotting with Matplotlib

## The basic plot

``` python
import matplotlib.pyplot as plt
fig, ax = plt.subplots()

time = [0, 1, 2, 3]
position = [0, 100, 200, 300]

ax.plot(time, postion)
```

## Two kinds of plotting objects

``` python
type(fig)
```

``` python
print(type(fig))
print(type(ax))
```

- Figure objects handle display, printing, saving, etc.
- Axes objects contain graph information

## (Optional) Three ways of showing a figure

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

## The lifecycle of a custom plot

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

## Plotting multiple data sets

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

    1.  (Optional) Original column names are object (i.e. string) data

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
    ```

## (Optional) Plot directly from Pandas

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

# Visualization Strategy

## There are many kinds of plots

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

## Read the docs

1.  Matplotlib gallery: <https://matplotlib.org/stable/gallery/index.html>
    1.  "Plotting categorical variables" example of multiple subplots
    2.  Download code examples
    3.  .py vs .ipynb
2.  Matplotlib tutorials: <https://matplotlib.org/stable/tutorials/index.html>
3.  Seaborn gallery: <https://seaborn.pydata.org/examples/index.html>
4.  Seaborn tutorials: <https://seaborn.pydata.org/tutorial.html>

## Workflow strategy

1.  Get in the ball park
2.  Look at lots of data
3.  Try lots of presets
4.  Customize judiciously
5.  Build collection of interactive and publication code snippets

# Fast visualization and theming with Seaborn

Seaborn is a set of high-level pre-sets for Matplotlib.

## Seaborn is a nice way to look at your data

``` python
# Import the Seaborn library
import seaborn as sns

ax = sns.lineplot(data=data.T, legend=False, dashes=False)
```

- Doing more with this data set requires transforming the data from wide form to long form; see <https://seaborn.pydata.org/tutorial/data_structure.html>

## Using preset styles

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
    plt.style.use("dark_background")

    # Fix grid if necessary
    #plt.rcParams["axes.grid"] = False

    # Make everything visible at a distance
    sns.set_context('poster')

    # Color by species
    ax = sns.scatterplot(data=iris, x='sepal_length', y='petal_length', hue='species', palette='colorblind', size='petal_width')
    ```

4.  The Seaborn plot uses Matplotlib under the hood

    ``` python
    # Set the figure size
    fig = ax.get_figure()
    fig.set_size_inches(8,6)

    fig
    ```

## (Optional) There are many styling options

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

## (Optional) Bar Charts

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

## (Optional) Histograms

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

## (Optional) Box Plots and Swarm Plots

1.  Box plot

    ``` python
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
    ax = sns.swarmplot(data=iris,x='species', y='petal_length', hue='species', palette='Set1')
    ax.legend(loc='upper left', fontsize=16)
    ax.tick_params(axis='x', labelrotation = 45)
    ```

4.  Overlapping plots

    ``` python
    ax = sns.boxplot(data=iris, x='species', y='petal_length')
    sns.stripplot(data=iris, x='species', y='petal_length', ax=ax, palette='Set1')
    ```

# (Optional) How Matplotlib works

## Understanding Matplotlib

1.  Everything is an Artist (object)
2.  Multiple levels of specificity
    - `plt` vs `axes`
    - rcParams vs temporary stylings
3.  Simplified high-level interfaces, aka "syntactic sugar"
    - `legend()` vs get legend handles and patches

## Matplotlib object syntax

- The `object.set_field(value)` usage is taken from Java, which was popular in 2003 when Matplotlib was developing its object-oriented syntax
- You get values back out with `object.get_field(value)`
- The Pythonic way to set a value would be `object.field = value`. However, the Matplotlib getters and setters do a lot of internal bookkeeping, so if you try to set field values directly you will get errors. For example, compare `ax.get_ylabel()` with `ax.yaxis.label`.
- Read "The Lifecycle of a Plot": <https://matplotlib.org/stable/tutorials/introductory/lifecycle.html>
- Read "Why you hate Matplotlib": <https://ryxcommar.com/2020/04/11/why-you-hate-matplotlib/>

# **Special Topics**

# Working with unstructured files

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

1.  check if all the letters reported in the manifest appear in the actual file
2.  check if all the letters in the file are reported in the manifest
3.  Therefore, construct two variables: (1) A list of every location line from the manifest, and (2) a list of every location line within the file proper

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

- Before automate everything, we run the code with lots of `print()` statements so that we can see what's happening

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
2.  Are there other structural regularities you could use to parse the data? (Note that in the letters, sometimes there are multiple letters under a single box header)

# Exception handling

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

# Performance and profiling

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

# Reducing memory usage

## Read a file one line at a time

``` python
with open('pettigrew_letters_ORIGINAL.txt', 'r') as file_in:
    for line in file_in:
        # Do stuff to current line
        pass
```

## Use a SQLite database

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

- Checking performance
- List comprehensions
- Defensive programming
- Debugging and Testing

# **Endnotes**

# Credits

- Plotting and Programming in Python (Pandas-oriented): <http://swcarpentry.github.io/python-novice-gapminder/>
- Programming with Python (NumPy-oriented): <https://swcarpentry.github.io/python-novice-inflammation/index.html>
- Python for Ecology: <https://datacarpentry.org/python-ecology-lesson/>
- Humanities Python Tour (file and text processing): <https://github.com/elliewix/humanities-python-tour/blob/master/Two-Hour-Beginner-Tour.ipynb>
- Introduction to Cultural Analytics & Python: <https://melaniewalsh.github.io/Intro-Cultural-Analytics/welcome.html>
- Rhondene Wint: Matplotlib and Seaborn notes

# References

- Complete tutorial: <https://docs.python.org/3/tutorial/index.html>
- Python standard library: <https://docs.python.org/3/library/>
- Pandas documentation: <https://pandas.pydata.org/pandas-docs/stable/>
- Pandas user guide: <https://pandas.pydata.org/docs/user_guide/index.html>
- String formatting: <https://pyformat.info/>
- True and False in Python: <https://docs.python.org/3/library/stdtypes.html#truth-value-testing>
- SciPy stats library: <https://docs.scipy.org/doc/scipy/reference/stats.html>
- Statistics in Python tutorial: <https://scipy-lectures.org/packages/statistics/>
- Statsmodels library: <https://www.statsmodels.org/stable/index.html>
- Matplotlib gallery of examples: <https://matplotlib.org/gallery/index.html>
- Seaborn gallery of examples: <https://seaborn.pydata.org/examples/index.html>
- IPython magic commands: <https://ipython.readthedocs.io/en/stable/interactive/magics.html>
- A somewhat-biased comparison of tools for integrating Python with C/C++: <http://blog.behnel.de/posts/cython-pybind11-cffi-which-tool-to-choose.html>
- How to choose a code editor: <https://github.com/elliewix/Ways-Of-Installing-Python/blob/master/ways-of-installing.md#why-do-you-need-a-specific-tool>

# Data Sources

1.  Gapminder data: <http://swcarpentry.github.io/python-novice-gapminder/files/python-novice-gapminder-data.zip>
2.  Ecology data (field surveys): <https://datacarpentry.org/python-ecology-lesson/data/portal-teachingdb-master.zip>
3.  Social Science data (SAFI): <https://datacarpentry.org/socialsci-workshop/data/>
4.  Humanities data (Pettigrew letters): <http://dx.doi.org/10.5334/data.1335350291>
