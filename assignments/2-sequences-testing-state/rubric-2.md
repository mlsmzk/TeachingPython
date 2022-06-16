# Rubric for Assignment 1

## Submission

The submission should consist of five files:

* `test_paren_matching.py`
* `paren-matching-report.md`
* `palindrome.py`
* `palindrome-report.md`
* `sequence.py`

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

### 1. Parenthesis Antithesis

#### Write Unit Tests

Points are based on the following criteria:

* The student has added a sufficient diversity of unit tests to the file.
* The tests do not cause the correct solution to fail.
* The comments justify why each test was chosen.
* The comments sufficiently illustrate the student's thought process in writing and selecting unit tests.

8: The added tests and comments meet all of the criteria.

7: The added tests and comments have minor issues (e.g., overlooked cases, vague reasoning, etc).

4: The added tests and comments have substantial issues (e.g., several overlooked cases, badly flawed reasoning).

0: The added tests or comments have fatal flaws (e.g., missing or non-substantial, tests causes correct solution to fail).

**Points: XX/8**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

#### Determine Correct Implementations

6: The solution identifies all correct implementations and provides strong arguments for why they are correct.

4: The solution has minor errors, such as not identifying all correct implementations as correct or providing weak arguments for why implementations are correct.

0: The solution is missing or has major flaws.

**Points: XX/6**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

#### Parenthesis Antithesis Summary

Add the points from the previous sections.

**Points: XX/14**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

### 2. `next_palindrome(393)` Not Found


#### Bug Watching

For each of the three required additional test cases described, one point for each of the following criteria:

* The test case either identifies a bug or eliminates a potential bug.
* The test case substantially differs from the other cases.
* The written justification for the test case is well-reasoned.

**Points: XX/9**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

#### A Diagram State of Mind

3: The stack and state diagram is at the line of code containing the bug, and shows the state of all functions waiting to return.

2: The diagram has minor errors (e.g., close to, but not at, the bug, or missing some information).

1: The diagram has substantial errors (e.g., shows functions that are not waiting to return, such as those that have already completed).

0: The diagram is missing or contains little information.

**Points: XX/3**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

#### Fix the Bug

3: The bug is correctly fixed in `palindrome.py` and the report contains a description of how the change fixes the bug.

2: There is a minor error (e.g., the report does not correctly describe how the change fixed the bug).

1: There is a major error (e.g., the change does not actually fix the bug).

0: There is no change to the original code, and the section of the report is missing.

**Points: XX/3**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

#### `next_palindrome(393)` Not Found Summary

Add the points from the previous sections.

**Points: XX/15**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

### 3. Read Aloud with Python

#### Docstrings

For each of the two functions, give one point each for the following in the docstring:

* The docstring summarizes what the function does.
* The docstring lists the correct type and meaning of the function's parameter.
* The docstring lists the correct type and meaning of the function's return, or omits this if the function does not return anything.

**`next_number`: XX/3**

**`look_and_say`: XX/3**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

#### Implementation

For each of the two functions:

5: The implementation correctly passes all unit tests.

4: The implementation has a minor error (e.g., incorrect return type) but is otherwise correct.

2: The implementation has a more significant error (e.g., syntax error).

0: The implementation is missing.

**`next_number`: XX/5**

**`look_and_say`: XX/5**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

#### Read Aloud with Python Summary

Add the points from the previous sections.

**Points: XX/16**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

### Correctness Summary

Add the points from the summary sections of each problem.

**Points: XX/45**

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

**Points: XX/20**

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

**Correctness: XX/45**

**Style: XX/20**

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