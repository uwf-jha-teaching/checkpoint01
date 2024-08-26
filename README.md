# Rational Numbers
[![Points badge](../../blob/badges/.github/badges/points.svg)](../../actions)

## Project Outcomes:
Develop a C++ program that uses:
- Conditional structures
- Loops
- Basic input/output
- Makefile/make
- Multiple files

## Preparatory Readings:
- Zybook "Primer" sections

## Background Information:
### Project overview:
In preparation for the first project, you will develop a simple C++ class that allows us to represent rational numbers without the rounding errors that are inherent in floating point numbers.
Rational numbers are made up of an integer numerator and an integer denominator.
Rational numbers can be positive or negative and when displayed shall always show the minus sign before the fraction, e.g. **-1/2**.

### Project Requirements:
Your application must function as described below:
1. You must create a Makefile with a rule called **main**.
	1. The **main** rule must create an executable file, also called **main**.
	1. Running the executable shall be accomplished by typing `./main` at the command prompt.
1. Your main program should be very simple. It should read two integers in from the user (first the numerator, then the denominator) and output the simplified fraction for those values.
	1. For example if the input is `3` followed by `-6`, then your program would output `-1/2`.
1. If the denominator, after simplifying the fraction is 1, simply output the numerator, e.g. `5/1` should output as `5`.
1. If the denominator is zero, output `NaN`. This is a common symbol that means "not a number" since dividing by zero is not allowed in mathematics.

### Submission Requirements:
1. All code must be added and committed to your local git repository.
2. All code must be pushed to the GitHub repository created when you "accepted" the assignment.
	1. After pushing, with `git push origin main`, visit the web URL of your repository to verify that your code is there.
	If you don't see the code there, then we can't see it either.
3. Your code must compile and run. The auto-grading tests will indicate your score for your submission.
	1. The auto-grading build should begin automatically when you push your code to GitHub.
	2. If your program will not compile, you will not get credit

## Important Notes:
- Projects will be graded on whether they correctly solve the problem, and whether they adhere to good programming practices.
- Projects must be received by the time specified on the due date. Projects received after that time will get a grade of zero.
- Please review the academic honesty policy.
	- Note that viewing another student's solution, whether in whole or in part, is considered academic dishonesty.
	- Also note that submitting code obtained through the Internet or other sources, whether in whole or in part, is considered academic dishonesty.
	- All programs submitted will be reviewed for evidence of academic dishonesty, and all violations will be handled accordingly.

## Grading
- View on GitHub:
	1. On your GitHub repo page, Click the :arrow_forward: **Actions** tab to see your graded results.
	1. If it isn't a green check mark (:heavy_check_mark:) then at least part of the testing failed.
	1. Click the commit message for the failing version then click "Autograding" on the left side of the page.
	1. Follow the :x: path and expand things to see what errors exist.
	1. At the bottom of the _education/autograding_ section, you can view the score for the auto-grading portion of the rubric.
		It will look something like ***30/50***.
