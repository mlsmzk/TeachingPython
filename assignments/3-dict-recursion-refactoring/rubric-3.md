# Rubric for Assignment 3

## Submission

The submission should consist of five files:

* `markov.py`
* `recursive_art.py`
* `portfolio/random.jpg`
* `vote.py`
* `vote-report.md`
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

### 1. Markov Text Generation

The functions for this problem are in `markov.py`.

#### 1.1. Generate the Word List

This step concerns the function `build_word_list`.

2: The function passes all unit tests.

1: The function fails one or more unit tests due to a minor error.

0: The function fails one or more unit tests due to being missing or having a major error.

**Points: XX/2**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

#### 1.2. Build the Dictionary

This step concerns the function `build_next_words`.

7: The function passes all unit tests.

5: The function fails one or more unit tests due to a minor error.

3: The function fails one or more unit tests due to a major error.

0: The function is missing or has a fatal flaw (e.g., syntax error).

**Points: XX/7**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

#### 1.3. Generate a Single Sentence

This step concerns the function `generate_sentence`.

3: The function passes all unit tests.

2: The function fails one or more unit tests due to a minor error (e.g., extra whitespace).

1: The function fails one or more unit tests due to a major error (e.g., infinite loop).

0: The function is missing or has a fatal flaw (e.g., syntax error).

**Points: XX/3**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

#### 1.4. Generate More Text

This step concerns the function `generate_text`.

3: The function passes all unit tests.

2: The function fails one or more unit tests due to a minor error (e.g., extra whitespace).

1: The function fails one or more unit tests due to a major error (e.g., infinite loop).

0: The function is missing or has a fatal flaw (e.g., syntax error).

**Points: XX/3**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

#### Markov Text Generation Summary

Add the points from the previous sections.

**Points: XX/15**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

### 2. The Art of Randomness

The submissions for this problem are in `recursive_art.py` and the `portfolio/` directory.

#### 2.1. Generate Random Art

This step concerns the function `build_random_function`. Testing for this function is done manually due to the random element.

8: The function passes all tests.

6: The function fails one or more tests due to a minor error.

4: The function fails one or more tests due to a major error.

0: The function is missing or has a fatal flaw (e.g., syntax error).

**Points: XX/8**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

#### 2.2. Save Your Artwork

This step concerns the function `portfolio/random.jpg`.

2: The file is an image reasonably matching the images produced by a correct script.

1: The file is an image, but it does not resemble an image produced by a correct script (e.g., uniform color, random colors).

0: The file is missing (or unmodified from its original empty file).

**Points: XX/2**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

#### The Art of Randomness Summary

Add the points from the previous sections.

**Points: XX/10**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

### 3. Alternatives for Alternative Voting

The submissions for this problem are in `vote.py` and `vote-report.md`.

#### 3.1. Refactor Recursively

This step concerns the function `hold_alternative_vote`.

6: The function passes all unit tests.

4: The function fails one or more unit tests due to a minor error.

2: The function fails one or more unit tests due to a major error.

0: The function is missing or has a fatal flaw (e.g., syntax error).

**Points: XX/6**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

#### 3.2. Noisrucer: Reflect on Recursion

4: The reflection is well-written and explains why one approach to implementation was easier to understand or write than the other.

3: The reflection has minor flaws, such as a lack of detail in the response.

2: The reflection either does not mention which implementation was easier to understand/write, or does not provide justification.

0: The reflection is missing.

**Points: XX/4**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

#### Alternatives for Alternative Voting Summary

Add the points from the previous sections.

**Points: XX/10**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

### Correctness Summary

Add the points from the summary sections of each problem.

**Points: XX/35**

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

#### Docstrings

This section covers docstrings for the functions listed below. For each function:

2: The docstring is present, well-written, and includes all required information.

1: The docstring has a minor error, such as not mentioning or explaining a parameter/return type.

0: The docstring is missing or unchanged from the starter code.

* `build_word_list`: **XX/2**
* `build_next_words`: **XX/2**
* `generate_sentence`: **XX/2**
* `generate_text`: **XX/2**
* `build_random_function`: **XX/2**

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

**Points: XX/23**

##### Self-Assessment Comments/Questions

None.

##### Grader Comments

*None.*

### Style Summary

Add up the points from all style subsection summaries.

**Points: XX/30**

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

**Correctness: XX/35**

**Style: XX/30**

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
