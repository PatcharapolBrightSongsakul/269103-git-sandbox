
# Exercise 11: Learn GitHub - Branch and Merge

## Instructions

* Fork this repo (original repo) to your GitHub account.
* Clone the forked repo to your local machine.
* On your local machine:
  * Create a new branch using `git checkout -b YOUR_STUDENT_ID` (replace YOUR_STUDENT_ID with your actual student ID).
  * Answer the questions below by editing this `README.md` file. You may refer to course materials but may NOT copy from other students.
  * After answering all questions, commit your changes.
  * Run the command `git log --oneline > YOUR_STUDENT_ID.log` to save your commit history to a file named with your student ID.
  * Add this log file to Git and commit this addition to your branch.
  * Switch to main branch using `git checkout main`, then merge your branch using `git merge YOUR_STUDENT_ID`. Do NOT delete your branch after merging.
  * Push all changes to your remote repo on GitHub.
* On GitHub:
  * Create a pull request (PR) to the original repo
  * Use **YOUR_STUDENT_ID** as the PR title
  * Submit by **Friday Febuary 27, 2024 1:00pm (GMT+7)**.
  * Leave the PR open after submission.
* Your PR must include the following:
  * Your answers of all questions.
  * Your commit history log file (`YOUR_STUDENT_ID.log`).
  * Note: Late submissions or PRs not visible in the original repo will NOT be graded.

## Resources
* [269103-2567-2](https://mango-cmu.instructure.com/courses/11947)
* [Git documentation](https://git-scm.com/docs)
* [Learning Git Branching](https://learngitbranching.js.org)

## Questions

1. Name two Linux commands from this course that you found most valuable. For each:
   * Briefly describe its function
   * Explain why it's essential for new engineers (in your own words)

**Answer:** 
grep
Function: use to globally search for regular expression and print out. It searches for pattern from input and displays all lines that contain that pattern
Essential: instead of scrolling through a huge chunk of code to find errors or bugs, this command lets us instantly filter for exactly what we need when we analyze massive terminal outputs or huge codebases.

chmod
Function: it stands for change mode, it modifies file or directory access by combining r,w,x permissions.
Essential: Sometime you could run into "permission denied" error even when youre running your own code/scripts. this command lets us actually run the files we build, while ensuring important system directories remain secure from accidental edits.

2. After one and a half years in the ISNE program, what advice would you give to prospective ISNE students? (Minimum 50 words)

**Answer:** 
Attend your fricking lectures, please. For a subject that is heavily code-based, I'd say attending lectures would make you understand it better because the teacher is literally right there and you could just straight up ask him, like how a chud would ask Dr. Ken, which is by no mean an embarrassing thing to do, it shows your motivation to learn and willing to understand. Also, practice, practice, practice writing code. It's like speaking or learning a new language. If you don't speak, write, or practice listening often, you will suck at it. Lastly, build yourself a good habit of using the correct syntax when writing lines.