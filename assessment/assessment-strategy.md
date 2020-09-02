# Assessment Strategy

## Table of Contents

* [Assignment Types](#assignment-types)
* [Assessment Overview](#assessment-overview)
* [Assessment Strategy Details](#assessment-strategy-details)
  + [Laboratory Assignments](#laboratory-assignments)
  + [Practical Assignments and Technical Challenges](#practical-assignments-and-technical-challenges)
* [Advance Feedback on an Assignment](#advance-feedback-on-an-assignment)
* [Assessment Delivery](#assessment-delivery)
* [Discussion of a Graded Assignment](#discussion-of-a-graded-assignment)
* [Calculating Your Grade](#calculating-your-grade)
  + [Laboratory Assignments](#laboratory-assignments-1)
  + [Practical Assignments](#practical-assignments)
  + [Technical Challenges](#technical-challenges)
* [Questions About Your Grade](#questions-about-your-grade)

## Assignment Types

- [Technical Challenge](../assignments/technical-challenge.md)
- [Practical Assignment](../assignments/practical-assignment.md)
- [Laboratory Assignment](../assignments/laboratory-assignment.md)

## Assessment Overview

You will complete all of your course work through an industry standard system
called [GitHub](https://www.github.com). All students will create a free GitHub
account at the start of the Fall 2020 semester. You will use this account and
the GitHub repositories associated with it to receive starter materials and
submit the final version of each technical challenge, laboratory assignment, and
practical assignment.

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
grading](https://www.amazon.com/Specifications-Grading-Restoring-Motivating-Students/dp/1620362422),
the grade that a student receives on a laboratory assignment will be based on
whether or not it meets the standards for technical work in the fields of
software engineering and discrete structures. Instead of receiving a single
numerical or letter grade for this assignment, your grade will have the
following components:

- **Percentage of Correct GatorGrader Checks Ranging Between 0 and 100**: Your
  submitted Python program must pass all of GatorGrader's checks by, for
  instance, ensuring that it produces the correct output and has all of the
  required characteristics. Your technical writing must pass all of
  GatorGrader's checks about, for instance, the length of its output and its use
  of the required Markdown language features for technical writing. For this
  component of a laboratory assignment's grade, your work will receive a
  percentage, ranging from 0 to 100, that corresponds to the percentage of
  GatorGrader checks that automatically pass inside of a GitHub Actions build.

- **GitHub Actions Build Status of Either ✔  or ❌**: Since additional checks on
  the Python source code and/or technical writing are encoded in GitHub Action
  workflows and, moreover, all of the GatorGrader checks are also run in GitHub
  Actions, your work will receive a checkmark grade if the last
  before-the-deadline build in GitHub Actions passes and a ✔  appears in the
  GitHub commit log instead of an ❌. The build status reported by GitHub
  Actions will only be a ✔ if the source code and technical writing in the
  GitHub repository pass all of both the GatorGrader checks and the additional
  checks.

- **Technical Writing Mastery of Either ✔  or ❌**: Students will also receive a
  ✔ grade when the responses to the technical writing questions presented in the
  `writing/reflection.md` reveal a mastery of technical writing skills. To
  receive a checkmark grade, the submitted writing should have correct spelling,
  grammar, punctuation, and formatting in addition to following the rules of the
  Markdown language. Your work will receive a ✔ grade for this component
  if the build report from GitHub Actions reveals that there are no detected
  mistakes in the technical writing.

- **Technical Knowledge and Skill Mastery of Either ✔  or ❌**: Students will
  also receive a checkmark grade when the GitHub repository reveals that they
  have mastered all of the technical knowledge and skills developed during the
  completion of the laboratory assignment. As a part of this grade, the
  instructor will assess aspects of the project including, but not limited to,
  the use of effective Python source code comments, correct Git commit messages,
  and accurate responses to the technical writing questions.

### Practical Assignments and Technical Challenges

Again taking inspiration from the principles of [specification-based
grading](https://www.amazon.com/Specifications-Grading-Restoring-Motivating-Students/dp/1620362422),
the grade that a student receives on either a practical assignment or a
technical challenge will be based on whether or not it meets the standards for
technical work in the fields of software engineering and discrete structures as
evidenced by:

- **GitHub Actions Build Status of Either ✔  or ❌**: Your work will receive a ✔
  if the last before-the-deadline build in GitHub Actions passes and a ✔ appears
  in the GitHub commit log instead of an ❌. The build status reported by
  GitHub Actions will only be a ✔ if the Python source code and technical
  writing in the GitHub repository pass all of both the GatorGrader checks and
  any additional checks.

## Advance Feedback on an Assignment

Students who wish to receive feedback on their work for any course assignment
should first open an issue on the issue tracker for their assignment's GitHub
repository, giving an appropriate title and description for the type of feedback
that you would like the course instructor to provide. After creating this issue,
you will see that GitHub has created a unique web site that references it. To
alert the course instructor to the fact that the issue was created and that you
want feedback on your work, please send it to him by a Slack direct message at
least 24 hours in advance of the project's due date. After the instructor
responds to the issue, please resolve all of the stated concerns and participate
in the discussion until the issue is resolved and ultimately marked as closed.

## Assessment Delivery

The course instructor invites students to incrementally complete all of the
learning objectives for a technical challenge, laboratory assignment, and
practical assignment. As long as your work passes all of the GatorGrader checks
before an assignment's deadline, you will receive full credit for that part of
your assignment grade. After the deadline for project submission, all grades for
the course projects will be reported through a student's GitHub repository using
either messages in the GitHub repository's commit log, issues raised in the
issue tracker, or comments on a pull request in the GitHub repository. Students
should ask questions about their grade for any project on GitHub so as to
facilitate an effective conversation about the submitted deliverables and to
ensure that a student can ultimately master all of the technical knowledge and
skills developed as part of that assignment's exploration of a specific topic in
the field of discrete structures.

## Discussion of a Graded Assignment

Students who wish to receive feedback on their work for any graded course
assignment should leave question in the same region of Github where the course
instructor submitted the assignment's grade. For example, if the instructor
submits your grade to a pull request in your repository for a laboratory
assignment, then you should ask questions about your grade in that pull request,
bearing in mind the need to @-mention the course instructor in the body of your
comment. Students can continue to discuss the graded assignment with the course
instructor until they understand all the technical topics that were the
focus of the particular assignment.

## Calculating Your Grade

The instructor will convert the specification-based grades that you received to
a numerical grade for each type of assignment. The following example succinctly
illustrates the calculation of your grade under the simplifying assumption that
there are three of each type of assignment with the following grades:

### Laboratory Assignments

- Assignment One: 100%, ✔, ✔, ❌
- Assignment Two: 81%, ❌, ✔, ❌
- Assignment Three: 95%, ❌, ✔, ✔

Laboratory Assignment Grade:

- Assignment One:

  ```
  (100 + ((1+1+0)/3)*100)/200
          0.833
  ```

- Assignment Two:

  ```
  (81 + ((0+1+0)/3)*100)/200
         0.572
  ```

- Assignment Three:

  ```
  (95 + ((0+1+1)/3)*100)/200
         0.808
  ```

- Overall:

  ```
  (0.833 + 0.572 + 0.808) / 3 * 100
          73.767
  ```

### Practical Assignments

- Assignment One: ✔
- Assignment Two: ❌
- Assignment Three: ❌

- Overall:

  ```
  (1+0+0)/3 * 100
        33.33
  ```

### Technical Challenges

- Assignment One: ✔
- Assignment Two: ✔
- Assignment Three: ✔

- Overall:

  ```
  (1+1+1)/3 * 100
        100.00
  ```

## Questions About Your Grade

Before asking the course instructor a question about the calculation of your
assignment grades, please make sure that you have already consulted the GitHub
repository for each assignment to see your grades and then calculated your grade
using this approach outlined in this document. The course instructor will use
your calculations to support the discussion of any questions that you have about
how to calculate your grade for the technical challenges, laboratory
assignments, and practical assignments.
