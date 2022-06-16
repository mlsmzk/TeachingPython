# Rubric for Assignment 1

## Submission

This item concerns the five files that should be modified for submission:

* `baby_ai.py`
* `billion.py`
* `floating_point.py`
* `password.py`
* `pricy_fall.py`

For each file:

3: Changes to the file seem to show a good-faith attempt on all problem parts relating to this file.

2: Changes to the file seem to show a good-faith attempt on at least 50% (but strictly less than 100%) of problem parts relating to this file.

1: Changes to the file seem to show a good-faith attempt on less than 50% (but strictly more than 0%) of problem parts relating to this file.

0: The file was unchanged from its initial state.

**Points: XX/15**

### Self-Assessment Comments/Questions

None.

### Grader Comments

*None.*

## Correctness

### 1. (Describe Function Here)

For each function, one point is given for each of the following criteria:

* The docstring includes a one-sentence description of what the function does.
* The docstring indicates what type each parameter is (each parameter is worth one point).
* The docstring indicates what each parameter represents (each parameter is worth one point).
* If there is a return value, the docstring indicates the return type. (If there is no return value, one point for omitting the Returns section or for indicating that nothing is returned.)
* If there is a return value, the docstring indicates what the return value represents. (If there is no return value, one point for omitting the Returns section or for indicating that nothing is returned.)

**Extra credit**: for each function, one bonus point is given for adding extra detail to the docstring, which may include assumptions the function makes about the input, caveats about the return value or behavior, or a more precise description about what the function does.

#### One Billion Seconds

This part concerns the file `billion.py`.

**Points: XX/5**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

#### Artificial...Intelligence?

This part concerns the file `baby_ai.py`.

**Points: XX/9**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

#### (Describe Function Here) Summary

Add the points from the previous sections.

**Points: XX/14**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

### 2. Password Checker (9 points)

This part concerns the file `password.py`.

For each of the four checkers:

3: The given solution passes all tests.

2: The given solution fails one or more tests due to a minor error.

1: The given solution fails one or more tests due to a major error.

0: The given solution was not implemented.

#### Blacklisted Passwords

This part concerns the function `not_common_password`.

**Points: XX/3**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

#### Password Length

This part concerns the function `meets_length_restriction`.

**Points: XX/3**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

#### Character Classes

This part concerns the function `uses_all_character_classes`.

**Points: XX/3**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

#### Multiple Sets of Password Rules

This part concerns the function `long_enough_or_all_rules`.

**Points: XX/3**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

#### Password Checker Summary

Add the points from the previous sections.

**Points: XX/12**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

### 3. Let me `float` an idea by you...

This part concerns the file `floating_point.py`.

For each of the four steps:

3: The given solution passes all tests.

2: The given solution fails one or more tests due to a minor error.

1: The given solution fails one or more tests due to a major error.

0: The given solution was not implemented.

#### Split the Bitstring

This part concerns the function `split_bits`.

**Points: XX/3**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

#### Convert Exponent

This part concerns the function `convert_to_power`.

**Points: XX/3**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

#### Convert Fraction

This part concerns the function `convert_to_significand`.

**Points: XX/3**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

#### Assemble the Float

This part concerns the function `interpret_as_float`.

**Points: XX/3**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

#### Let me `float` an idea by you... Summary

Add the points from the previous sections.

**Points: XX/12**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

### 4. Code Repair

#### Variable Names

For each of the 10 variables that should be renamed:

1: The variable is reasonably named according to the course's style guidelines.

0: The variable is not named according to the style guidelines, including being the name of a mathematical symbol or using excessive abbreviation.

For every **two** variables that are "on the fence" (i.e., potentially reasonable), add back one point.

**Points: XX/10**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

#### Code Errors

2: The function passes all unit tests.

1: The function passes some, but not all, unit tests.

0: Errors remain in the function that prevent it from passing any unit tests.

**Points: XX/2**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

#### Code Repair Summary

Add the points from the previous sections.

**Points: XX/12**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

### Correctness Summary

Add the points from the summary sections of each problem.

**Points: XX/50**

#### Self-Assessment Comments/Questions

None.

#### Grader Comments

*None.*

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

**For this assignment, Git does not factor into the style score, but suggestions for improvement will be made in feedback. In future assignments, the criteria listed below will be part of the style score.**

The Git style score takes some or all of the following into account:

* The header line of commit message succinctly summarizes what was changed.
* The commit message provides context for the changes made.
* The commit does not add, edit, or remove files that are not necessary for submission (e.g., adding notes for yourself, or editing/removing the Jupyter notebook describing the assignment).
* The commit message does not contains lines that exceed 72 characters in length.

**Points: 0/0**

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

#### Python Summary

**Points: XX/13**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

### Style Summary

Add up the points from all style subsection summaries.

**Points: XX/15**

## Self-Assessment

If an exercise lost points for correctness or style, there should be a
student comment explaining why and, if applicable, how to avoid the bug or
mistake in the future. If an exercise was marked completely correct, a student
comment may note the differences between an approach taken by the sample
solution versus the student's solution, or reflect on a key insight that helped
in answering the question. Substantive questions are always welcome.

Addressing all issues in the submission and thoughtfully commenting on the
submission gives full credit. In exercises where the submission could be
improved, addressing the issues involves not only noting what the error was
or what the sample solution says, but also reflects on assumptions and/or
thought processes that might indicate a misunderstanding of the course concepts,
as well as ways to fix those going forward.

**Points: XX/20**

### Grader Comments

*None.*

## Summary

Copy the point totals from each of the four major section summaries above.

**Submission: XX/15**

**Correctness: XX/50**

**Style: XX/15**

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