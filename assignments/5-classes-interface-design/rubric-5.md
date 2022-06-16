# Rubric for Assignment 5

## Submission

The submission should consist of two files:

* `tic_tac_toe.py`
* `user_account.py`

### Timeliness

In this section, taking one or more late days results in full credit.

For each of the two files:

2: The file was committed to GitHub on time.

1: The file was committed to GitHub slightly late.

0: The file was committed to GitHub significantly late.

**Points: XX/4**

#### Self-Assessment Comments/Questions

None.

#### Grader Comments

*None.*

## Correctness

In all cells requiring a solution, a missing solution is automatically given 0
points.

The rubric describes some but not all possible point values and the criteria
that correspond to these values. Other point values are possible and given
subject to grader discretion.

### 1. A Cure for Your Board-om

The code for this problem is in `tic_tac_toe.py`.

For each of the six methods to implement (`__init__`, `next_move`, `mark`, `get_square`, `check_win`, and `__repr__`):

3: The method passes all unit tests.

2: The method passes half or more, but not all, unit tests.

1: The method passes fewer than half unit tests, but was reasonably attempted.

0: The method was not attempted or missing.

* `__init__`: **XX/3**
* `next_move`: **XX/3**
* `mark`: **XX/3**
* `get_square`: **XX/3**
* `check_win`: **XX/3**
* `__repr__`: **XX/3**

**Points: XX/18**

#### Self-Assessment Comments/Questions

None.

#### Grader Comments

*None.*

### 2. *Ex Post Refacto*

The code for this problem is in `user_account.py`.

#### 2.1. `@property` Value

This step concerns any method in `UserAccount` that references the variables originally named `username` or `posts`.

5: The refactored implementation passes all unit tests.

3: The refactored implementation passes half or more, but not all, unit tests.

1: The refactored implementation passes fewer than half unit tests, but was reasonably attempted.

0: The refactored implementation was not attempted or missing.

**Points: XX/5**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

#### 2.2. A-`dict`-ed to Refactoring

This step concerns any method in `UserAccount` that references the variable originally named `posts`, as well as the new method `num_posts`.

5: The refactored implementation passes all unit tests.

3: The refactored implementation passes half or more, but not all, unit tests.

1: The refactored implementation passes fewer than half unit tests, but was reasonably attempted.

0: The refactored implementation was not attempted or missing.

**Points: XX/5**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

#### 2.3. Moving the Post Goals

This step concerns the `post` method in `UserAccount` and the `generate_new_post_id` function outside of `UserAccount`.

6: The refactored implementation passes all unit tests.

4: The refactored implementation passes half or more, but not all, unit tests.

2: The refactored implementation passes fewer than half unit tests, but was reasonably attempted.

0: The refactored implementation was not attempted or missing.

**Points: XX/6**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

#### *Ex Post Refacto* Summary

Add the points from the previous sections.

**Points: XX/16**

### Correctness Summary

Add the points from the summary sections of each problem.

**Points: XX/34**

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

1: The docstring has a minor error, such as not mentioning or explaining a parameter/return type. (The parameter/return type is not required if there is none, or if all information is easily and explicitly in the docstring summary.)

0: The docstring is missing or unchanged from the starter code.

In `tic_tac_toe.py`:

* `TicTacToeBoard`: **XX/2**
* `__init__`: **XX/2**
* `next_move`: **XX/2**
* `mark`: **XX/2**
* `get_square`: **XX/2**
* `check_win`: **XX/2**
* `__repr__`: **XX/2**

In `user_account.py`:

* `UserAccount`: **XX/2**
* `username`: **XX/2**
* `num_posts`: **XX/2**
* `generate_new_post_id`: **XX/2**

**Points: XX/22**

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

### Overall Style Summary

Add up the points from all style subsection summaries.

**Points: XX/42**

## Self-Assessment

If an exercise lost points for correctness or style, there should be a student comment explaining why and, if applicable, how to avoid the bug or mistake in the future. If an exercise was marked completely correct, a student comment may note the differences between an approach taken by the sample solution versus the student's solution, or reflect on a key insight that helped in answering the question. Substantive questions are always welcome.

Addressing all issues in the submission and thoughtfully commenting on the submission gives full credit. In exercises where the submission could be improved, addressing the issues involves not only noting what the error was or what the sample solution says, but also reflects on assumptions and/or thought processes that might indicate a misunderstanding of the course concepts, as well as ways to fix those going forward.

**Points: XX/15**

### Grader Comments

*None.*

## Summary

Copy the point totals from each of the four major section summaries above.

**Submission: XX/4**

**Correctness: XX/34**

**Style: XX/42**

**Self-Assessment: XX/20**

### Total

**TOTAL POINTS: XX/100**

### General Self-Assessment Comments

None.

### General Grader Comments

*None.*

### Grader Information

*Grader*:

*Reviewer*: