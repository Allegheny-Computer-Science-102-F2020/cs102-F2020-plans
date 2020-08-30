# Assessment Strategy

## Table of Contents

* [Assignment Types](#assignment-types)
* [Assessment Overview](#assessment-overview)
* [Assessment Strategy Details](#assessment-strategy-details)
  + [Laboratory Assignments](#laboratory-assignments)
  + [Practical Assignments](#practical-assignments)
  + [Technical Challenges](#technical-challenges)
* [Assessment Delivery](#assessment-delivery)

## Assignment Types

- [Technical Challenge](../assignments/technical-challenge.md)
- [Practical Assignment](../assignments/practical-assignment.md)
- [Laboratory Assignment](../assignments/laboratory-assignment.md)

## Assessment Overview

You will complete all of your course work through an industry standard system
called [GitHub](https://www.github.com). All students will create a free GitHub
account at the start of the Fall 2020 semester. You will use this account and
the GitHub repositories associated with it to receive starter materials and
submit the final version of each technical challenge, laboratory and practical assignment and
examination.

You will receive rapid feedback on your work through a tool called
[GatorGrader](https://github.com/GatorEducator/gatorgrader). The course
instructor will define GatorGrader checks for each type of course assignment and
your job will be use a programming language like Python to implement a complete
solution that passes all of the GatorGrader checks. In addition to running the
GatorGrader tool on your laptop, you will see the results from running
GatorGrader checks in the [GitHub Actions](https://github.com/features/actions)
continuous integration environment.

## Assessment Strategy Details

### Laboratory Assignments

Taking inspiration from the principles of [specification-based
grading](http://rtalbert.org/return-to-specs-grading-calculus/), the grade that
a student receives on a laboratory assignment will be based on whether or not it
meets the standards for technical work in the fields of software engineering and
discrete structures. Instead of receiving a numerical or letter grade for this
assignment, your grade will have the following components:

- **Percentage of Correct GatorGrader Checks Ranging Between 0 and 100**:
  Students are invited to repeatedly try to implement a Python program that
  passes all of GatorGrader's checks by, for instance, ensuring that their
  program produces the correct output and has all of the required
  characteristics. Students should also repeatedly revise their technical
  writing to ensure that it also passes all of GatorGrader's checks about, for
  instance, the length of its content and its appropriate use of the Markdown
  language for technical writing. For this component of a laboratory
  assignment's grade, your work will receive a percentage, ranging from 0 to
  100, that corresponds to the percentage of GatorGrader checks that
  automatically pass inside of a GitHub Actions build.

- **GitHub Actions Build Status of Either ✔  or ❌**: Since additional checks on
  the source code and/or technical writing may be encoded in GitHub Action
  workflows and, moreover, all of the GatorGrader checks are also run in GitHub
  Actions, your work will receive a checkmark grade if the last
  before-the-deadline build passes and a ✔  appears in their GitHub commit log
  instead of an ❌. The build status reported by GitHub Actions will only be a
  checkmark if the source code and technical writing in the GitHub repository
  passes all of the GatorGrader checks. .

- **Technical Writing Mastery of Either ✔  or ❌**: Students will also receive a
  checkmark grade when the responses to the technical writing questions
  presented in the `writing/reflection.md` reveal a mastery of technical writing
  skills. To receive a checkmark grade, the submitted writing should have
  correct spelling, grammar, punctuation, and formatting in addition to
  following the rules of Markdown language. Your work will receive a checkmark
  grade for this component if the build report from GitHub Actions reveals that
  there are no detected mistakes in the technical writing.

- **Overall Technical Knowledge Mastery of Either ✔  or ❌**: Students will also
  receive a checkmark grade when their GitHub repository reveals that they have
  mastered all of the technical knowledge and skills developed during the
  completion of the laboratory assignment. As a part of this grade, the
  instructor will assess aspects of the project including, but not limited to,
  the use of effective Python source code comments and Git commit messages.
  Students are encouraged to ask the course instructor or a student technical
  leader to use the GitHub issue tracker to provide feedback on how well their
  work demonstrates mastery of the assignment's technical knowledge and skills.

As with all other grading components, students are encouraged to repeatedly
revise their source code and technical writing in an attempt to get their GitHub
Action build to pass correctly. 

### Practical Assignments

### Technical Challenges

## Assessment Delivery

All grades for course projects will be reported through a student's GitHub
repository using either messages in the GitHub commit log or issues raised in
the issue tracker. Students should ask questions about their grade for any
project in GitHub so as to facilitate an effective conversation about the
submitted deliverables and to ensure that a student can ultimately master all of
the technical knowledge and skills developed as part of that assignment's
exploration of a specific topic in the field of discrete structures.

## Project Feedback

Students who wish to receive feedback on their work for an assignment should
first open an issue on the issue tracker for their assignment's GitHub
repository, giving an appropriate title and description for the type of feedback
that you would like the course instructor to provide. After creating this issue,
you will see that GitHub has created a unique web site that references it. To
alert the course instructor to the fact that the issue was created and that you
want feedback on your work, please send it to him by a Slack direct message at
least 24 hours in advance of the project's due date. After the instructor
responds to the issue, please resolve all of the stated concerns and participate
in the discussion until the issue is closed.
