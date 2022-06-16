# Rubric for Assignment 5

## Submission

The submission should consist of three files:

* `tic_tac_toe_view.py`
* `tic_tac_toe_controller.py`
* `tic_tac_toe_game.py`

### Timeliness

In this section, taking one or more late days results in full credit.

For each of the three files:

2: The file was committed to GitHub on time.

1: The file was committed to GitHub slightly late.

0: The file was committed to GitHub significantly late.

**Points: XX/6**

#### Self-Assessment Comments/Questions

None.

#### Grader Comments

*None.*

## Correctness

The rubric describes some but not all possible point values and the criteria
that correspond to these values. Other point values are possible and given
subject to grader discretion.

### 1. An Inherited View (and an Acquired Taste)

The code for this problem is in `tic_tac_toe_view.py`.

#### 1.1. As Easy as `abc`

This part covers the classes `TicTacToeView` and `TextView` (implicitly) in
`tic_tac_toe_view.py`.

There are six test functions run as part of `test_view_classes` in
`test_tic_tac_toe_view.py`. The submission earns one point for each test
function passed.

**Points: XX/6**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

#### 1.2. A More Concrete View

This part covers the `draw` method of the `TextView` class in
`tic_tac_toe_view.py`.

There are three test cases for the `test_draw` function in
`test_tic_tac_toe_view.py`. The submission earns two points for each test case
passed.

**Points: XX/6**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

#### An Inherited View (and an Acquired Taste) Summary

Add the points from the previous sections.

**Points: XX/12**

### 2. Taking Control

The code for this problem is in `tic_tac_toe_controller.py`.

#### Class Structure

This part covers the classes `TicTacToeController` and `TextController`
(implicitly) in `tic_tac_toe_controller.py`.

There are six test functions run as part of `test_controller_classes` in
`test_tic_tac_toe_controller.py`. The submission earns one point for each test
function passed.

**Points: XX/6**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

#### Move Input Processing

This part covers the `draw` method of the `TextController` class in
`tic_tac_toe_controller.py`.

There are seven test cases for the `test_move` function in
`test_tic_tac_toe_controller.py`. The submission earns one point for each test
case passed.

**Points: XX/7**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

#### Taking Control Summary

Add the points from the previous sections.

**Points: XX/13**

### 3. All Together Now

The code for this problem is in `tic_tac_toe_game.py`, and concerns the `main`
function.

3: The method passes all unit tests.

2: The method passes half or more, but not all, unit tests.

1: The method passes fewer than half unit tests, but was reasonably attempted.

0: The method was not attempted or missing.

**Points: XX/3**

#### Self-Assessment Comments/Questions

None.

#### Grader Comments

*None.*

### Correctness Summary

Add the points from the summary sections of each problem.

**Points: XX/28**

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

In `tic_tac_toe_view.py`:

* `TicTacToeView`: **XX/2**
* `__init__`: **XX/2**
* `board`: **XX/2**
* `TicTacToeView.draw`: **XX/2**
* `TextView`: **XX/2**
* `TextView.draw`: **XX/2**

In `tic_tac_toe_controller.py`:

* `TicTacToeController`: **XX/2**
* `__init__`: **XX/2**
* `board`: **XX/2**
* `TicTacToeController.move`: **XX/2**
* `TextController`: **XX/2**
* `TextController.move`: **XX/2**

In `tic_tac_toe_game.py`:

* `main`: **XX/2**

**Points: XX/26**

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

**Points: XX/46**

## Self-Assessment

If an exercise lost points for correctness or style, there should be a student comment explaining why and, if applicable, how to avoid the bug or mistake in the future. If an exercise was marked completely correct, a student comment may note the differences between an approach taken by the sample solution versus the student's solution, or reflect on a key insight that helped in answering the question. Substantive questions are always welcome.

Addressing all issues in the submission and thoughtfully commenting on the submission gives full credit. In exercises where the submission could be improved, addressing the issues involves not only noting what the error was or what the sample solution says, but also reflects on assumptions and/or thought processes that might indicate a misunderstanding of the course concepts, as well as ways to fix those going forward.

**Points: XX/20**

### Grader Comments

*None.*

## Summary

Copy the point totals from each of the four major section summaries above.

**Submission: XX/6**

**Correctness: XX/28**

**Style: XX/46**

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
