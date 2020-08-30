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
your job will be to use a programming language like Python to implement a
complete solution that passes all of the GatorGrader checks. In addition to
running the GatorGrader tool on your laptop, you will see the results from
running GatorGrader checks in the [GitHub
Actions](https://github.com/features/actions) continuous integration
environment.

## Assessment Strategy Details

### Laboratory Assignments

Taking inspiration from the principles of [specification-based
grading](http://rtalbert.org/return-to-specs-grading-calculus/), the grade that
a student receives on a laboratory assignment will be based on whether or not it
meets the standards for technical work in the fields of software engineering and
discrete structures. Instead of receiving a single numerical or letter grade for
this assignment, your grade will have the following components:

- **Percentage of Correct GatorGrader Checks Ranging Between 0 and 100**: Your
  submitted Python program must pass all of GatorGrader's checks by, for
  instance, ensuring that it produces the correct output and has all of the
  required characteristics. Your technical writing must pass all of
  GatorGrader's checks about, for instance, the length of its content and its
  appropriate use of the Markdown language features for technical writing. For
  this component of a laboratory assignment's grade, your work will receive a
  percentage, ranging from 0 to 100, that corresponds to the percentage of
  GatorGrader checks that automatically pass inside of a GitHub Actions build.

- **GitHub Actions Build Status of Either ✔  or ❌**: Since additional checks on
  the source code and/or technical writing are encoded in GitHub Action
  workflows and, moreover, all of the GatorGrader checks are also run in GitHub
  Actions, your work will receive a checkmark grade if the last
  before-the-deadline build passes and a ✔  appears in their GitHub commit log
  instead of an ❌. The build status reported by GitHub Actions will only be a ✔
  if the source code and technical writing in the GitHub repository passes all
  of the GatorGrader checks and all the additional checks pass without error.

- **Technical Writing Mastery of Either ✔  or ❌**: Students will also receive a
  ✔ grade when the responses to the technical writing questions presented in the
  `writing/reflection.md` reveal a mastery of technical writing skills. To
  receive a checkmark grade, the submitted writing should have correct spelling,
  grammar, punctuation, and formatting in addition to following the rules of the
  Markdown language. Your work will receive a ✔ grade for this component
  if the build report from GitHub Actions reveals that there are no detected
  mistakes in the technical writing.

- **Technical Knowledge and Skill Mastery of Either ✔  or ❌**: Students will
  also receive a checkmark grade when their GitHub repository reveals that they
  have mastered all of the technical knowledge and skills developed during the
  completion of the laboratory assignment. As a part of this grade, the
  instructor will assess aspects of the project including, but not limited to,
  the use of effective Python source code comments, correct Git commit messages,
  and accurate responses to the technical writing questions.

### Practical Assignments

### Technical Challenges

## Calculating Your Grade

### Laboratory Assignments

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

## Assignment Feedback

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
