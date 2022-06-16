# Rubric for Assignment 4

## Submission

The submission should consist of four files:

* `vroom.ipynb`
* `gene_finder.py`
* `sars-cov-2.ipynb`
* `reflection.md`

For each file:

2: Changes to the file seem to show a good-faith attempt on all problem parts relating to this file.

1: Changes to the file seem to show a good-faith attempt on less than 50% of problem parts relating to this file.

0: The file was unchanged from its initial state.

**Points: XX/8**

#### Self-Assessment Comments/Questions

None.

#### Grader Comments

*None.*

## Correctness

### 1. Convoluted Plots

The submission for this problem is in `vroom.ipynb`.

#### 1.1. Write a Plotting Function

This step concerns the function `make_results_plot`.

3: The function correctly plots the data with the correct style, appropriate axis labels, and an appropriate plot title.

2: The function correctly plots the data, but there is a minor error in plot style, axis label (e.g., missing units), or plot title.

1: The function does not correctly plot the data, **or** there is a major error in the plot style, axis label, or plot title.

0: The function is missing or nonfunctional (e.g., has a syntax error).

**Points: XX/3**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

#### 1.2. Plot the correct Data

For each of the 4 plots:

1: The correct data set was plotted.

0: The correct data set was not plotted.

* Design 1: **XX/1**
* Design 2: **XX/1**
* Design 3: **XX/1**
* Design 4: **XX/1**

**Points: XX/4**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

#### Convoluted Plots Summary

Add the points from the previous sections.

**Points: XX/7**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

### 2. Gene Finder

#### 2.1. Function Implementation

The submission for this section is in `gene_finder.py`.

For each of the 10 functions:

3: The function passes all unit tests, or is otherwise fully functional.

2: The function contains a minor error.

1: The function contains a major error.

0: The function is missing or has a fatal flaw (e.g., syntax error).

* `get_complement`: **XX/3**
* `get_reverse_complement`: **XX/3**
* `rest_of_orf`: **XX/3**
* `find_all_orfs_one_frame`: **XX/3**
* `find_all_orfs`: **XX/3**
* `find_all_orfs_both_strands`: **XX/3**
* `find_longest_orf`: **XX/3**
* `noncoding_orf_threshold`: **XX/3**
* `encode_amino_acids`: **XX/3**
* `find_genes`: **XX/3**

**Points: XX/30**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

#### 2.2. Unit Tests

The submission for this section is in `test_gene_finder.py`.

For each of the 8 sets of test cases:

3: The set of test cases is correct (i.e., does not cause a correct implementation to fail), reasonably complete (i.e., tests an appropriate scope of cases in the function implementation), and well-justified in the accompanying comments.

2: The set of test cases has a minor flaw in one of the areas mentioned above (e.g., does not cover a reasonably foreseeable edge case).

1: The set of test cases has a minor flaw in multiple areas mentioned above, or a major flaw in one of the areas (e.g., accompanying comment is missing entirely).

0: No new test cases were added, or there is a fatal flaw (e.g., using the wrong type in test cases, causing testing to fail entirely).

* `get_complement_cases`: **XX/3**
* `get_reverse_complement_cases`: **XX/3**
* `rest_of_orf_cases`: **XX/3**
* `find_all_orfs_one_frame_cases`: **XX/3**
* `find_all_orfs_cases`: **XX/3**
* `find_all_orfs_both_strands_cases`: **XX/3**
* `find_longest_orf_cases`: **XX/3**
* `encode_amino_acids_cases`: **XX/3**

**Points: XX/24**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

#### 2.3. Analysis and Writeup

The submission for this section is in `sars-cov-2.ipynb`.

Grading is based on the following criteria:

* The computational essay has an appropriate title (1 point).
* The student's name is in the author field of the essay (1 point).
* There is a code cell showing the output of `find_genes` (1 point).
* For each of the five proteins asked for in the problem, the following information is mentioned:
    * The amino acid sequence of the specific protein (1 point).
    * The length of the protein (1 point).
    * The accession number of the protein (1 point).
* The essay is written in a way that flows well and tells the story of the analysis, rather than only presenting the information (2 points).

**Points: XX/20**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

#### 2.4. Reflection

For each of the two prompts in the reflection:

3: The reflection is well-written and addresses all aspects of the prompt.

2: The reflection has minor flaws, such as a lack of detail in the response.

1: The reflection has major flaws, such as not all addressing all aspects of the prompt.

0: The reflection is missing.

**Points: XX/6**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

#### Gene Finder Summary

Add the points from the previous sections.

**Points: XX/80**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

### Correctness Summary

Add the points from the summary sections of each problem.

**Points: XX/87**

## Style

### General

2: The submission contains at most one spelling/grammar mistake.

1: The submission contains a few spelling/grammar mistakes.

0: The submission contains a substantial number of spelling/grammar mistakes.

**Points: XX/2**

#### Self-Assessment Comments/Questions

None.

#### Grader Comments

*None.*

### Git

One point for meeting each of the following criteria (checked over all commits relevant to the submission):

* The header line of commit message succinctly summarizes what was changed.
* The commit message provides context for the changes made.
* The commit does not add, edit, or remove files that are not necessary for submission (e.g., adding notes for yourself, or editing/removing the Jupyter notebook describing the assignment).
* The commit does not contain Git conflict indicators (e.g., `<<<<<<< HEAD`) that need to be removed during grading.
* The commit message does not contain lines that exceed 72 characters in length.

**Points: XX/5**

#### Self-Assessment Comments/Questions

None.

#### Grader Comments

*None.*

### Python

#### Pylint

Pylint, when run, returns a "style score" out of 10. After running this on all Python files, take the style score and round it *down*, with minimum of 0 points.

**Points: XX/10**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

#### Docstrings

This section covers docstrings for the functions listed below. For each function:

2: The docstring is present, well-written, and includes all required information.

1: The docstring has a minor error, such as not mentioning or explaining a parameter/return type.

0: The docstring is missing or unchanged from the starter code.

* `get_complement`: **XX/2**
* `get_reverse_complement`: **XX/2**
* `rest_of_orf`: **XX/2**
* `find_all_orfs_one_frame`: **XX/2**
* `find_all_orfs`: **XX/2**
* `find_all_orfs_both_strands`: **XX/2**
* `find_longest_orf`: **XX/2**
* `noncoding_orf_threshold`: **XX/2**
* `encode_amino_acids`: **XX/2**
* `find_genes`: **XX/2**

**Points: XX/20**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

#### Miscellaneous Code Style

Outside of where they are already covered by other parts of this rubric, consider the following criteria:

* Variable names follow the course guidelines for formatting and descriptiveness.
* The code consistently uses single or double quotes except where it would be convoluted to write.
* Where needed, there are comments in the code to describe what a block of code does (at a high level) or why that code is there.
* The code is generally readable and easy to understand.

3: The code meets all of the above criteria.

2: The code has some minor issues with one of the above criteria.

1: The code has minor issues with more than one of the above criteria, or major issues with one criterion.

0: The code has major issues with more than one the above criteria.

**Points: XX/3**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

#### Python Style Summary

**Points: XX/33**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

### Overall Style Summary

Add up the points from all style subsection summaries.

**Points: XX/40**

## Self-Assessment

If an exercise lost points for correctness or style, there should be a student comment explaining why and, if applicable, how to avoid the bug or mistake in the future. If an exercise was marked completely correct, a student comment may note the differences between an approach taken by the sample solution versus the student's solution, or reflect on a key insight that helped in answering the question. Substantive questions are always welcome.

Addressing all issues in the submission and thoughtfully commenting on the submission gives full credit. In exercises where the submission could be improved, addressing the issues involves not only noting what the error was or what the sample solution says, but also reflects on assumptions and/or thought processes that might indicate a misunderstanding of the course concepts, as well as ways to fix those going forward.

**Points: XX/15**

### Grader Comments

*None.*

## Summary

Copy the point totals from each of the four major section summaries above.

**Submission: XX/8**

**Correctness: XX/87**

**Style: XX/40**

**Self-Assessment: XX/15**

### Total

**TOTAL POINTS: XX/150**

### General Self-Assessment Comments

None.

### General Grader Comments

*None.*

### Grader Information

*Grader*:

*Reviewer*:
