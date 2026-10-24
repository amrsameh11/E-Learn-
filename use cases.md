**Casual Use Case 1:**
Enroll in a Course
The student logs in to the platform and browses available courses. The student selects a course and clicks the enroll button. The system confirms the enrollment.

-------------------------------------------------------------------------------------------------------

** Casual Use Case 2: Take a Quiz**
The student opens a course and selects a quiz. The system displays the questions, and the student submits the answers. The system calculates
the score and displays the result.

-------------------------------------------------------------------------------------------------------

**Fully Dressed Use Case 1: Enroll in a Course**

**Use Case ID:** UC-7

**Primary Actor:** Student

**Goal:** To enroll in a course.

**Preconditions:**
 The student is logged in.
 The course is available.

**Main Flow:**
 The student opens the courses page.
 The system displays available courses.
 The student selects a course.
 The system displays the course details.
 The student clicks the enroll button.
 The system confirms the enrollment.

**Alternative Flow:**
 If the course is unavailable, the system displays an error message.

**Postconditions:** The student is enrolled in the course.

-------------------------------------------------------------------------------------------------------

### Fully Dressed Use Case 2: Take a Quiz

**Use Case ID:** UC-12

**Primary Actor:** Student

**Goal:** To complete a quiz and view the score.

**Preconditions:**
 The student is logged in.
 The student has access to the course.

**Main Flow:**
 The student opens the course.
 The student selects a quiz.
 The system displays the quiz questions.
 The student answers the questions.
 The student submits the answers.
 The system calculates the score.
 The system displays the result.

**Alternative Flow:**
- If the student does not answer all questions, the system asks the student to review the unanswered questions before submission.

**Postconditions:** The quiz result is saved and displayed to the student.
