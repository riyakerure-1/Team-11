Online Course Management System

1. Project Title

Online Course Management System

2. Project Description

The Online Course Management System is a simple system designed to manage students, courses, enrollments, assignments, and assignment status. It helps store student and course information and manages the process of enrolling students and submitting assignments.

3. Objective

The main objective of this project is to create a simple and organized system that can:

- Store student details.
- Store and display course details.
- Manage student enrollment.
- Allow enrolled students to submit assignments.
- Maintain assignment submission status.

4. Feature Set IV

A. Student Details

The system stores:

- Student ID
- Name
- Email
- Contact Number

Student information can be entered, stored, and displayed.

B. Course Details

The system stores:

- Course ID
- Course Name
- Instructor
- Course Duration

Available course information can be displayed to students.

C. Enrollment

The student selects a course for enrollment.

The system checks whether the student is already enrolled.

- If already enrolled → Display "Already Enrolled"
- If not enrolled → Enroll the student and set Enrollment Status = Active

D. Assignment Submission

The enrolled student can submit an assignment by entering:

- Assignment ID
- Assignment Name
- Submission Date

The system records and displays the assignment submission details.

E. Assignment Status

The system checks whether an assignment has been submitted.

- If submitted → Display "Submitted"
- If not submitted → Display "Pending"

5. Algorithm

1. Start.
2. Enter Student ID, Name, Email, and Contact Number.
3. Store and display student details.
4. Enter Course ID, Course Name, Instructor, and Course Duration.
5. Store and display course details.
6. Select a student and course for enrollment.
7. Check whether the student is already enrolled.
8. If already enrolled, display "Student Already Enrolled".
9. Otherwise, enroll the student and set the status to Active.
10. Display enrollment details.
11. Select the enrolled student and assignment.
12. Enter Assignment ID and Assignment Name.
13. Submit the assignment and record the submission date.
14. Display assignment submission details.
15. Check the assignment status.
16. If submitted, display "Submitted"; otherwise, display "Pending".
17. End.

6. Flowchart

The flowchart follows this sequence:

Start → Student Details → Course Details → Enrollment → Check Enrollment → Assignment Submission → Assignment Status → End

Decision Points

- Already Enrolled?
  
  - Yes → Display "Already Enrolled"
  - No → Enroll Student → Set Status as Active

- Assignment Submitted?
  
  - Yes → Display "Submitted"
  - No → Display "Pending"

7. ER Diagram

The ER diagram contains four main entities:

STUDENT

- Student_ID (PK)
- Name
- Email
- Contact_Number

COURSE

- Course_ID (PK)
- Course_Name
- Instructor
- Course_Duration

ENROLLMENT

- Enrollment_ID (PK)
- Student_ID (FK)
- Course_ID (FK)
- Enrollment_Date
- Enrollment_Status

ASSIGNMENT

- Assignment_ID (PK)
- Course_ID (FK)
- Assignment_Name
- Submission_Date
- Assignment_Status

Relationships

- STUDENT → ENROLLMENT: One student can have many enrollments.
- COURSE → ENROLLMENT: One course can have many enrollments.
- COURSE → ASSIGNMENT: One course can have many assignments.
- STUDENT → ASSIGNMENT: A student can submit assignments for enrolled courses.

PK = Primary Key
FK = Foreign Key

8. Technologies / Concepts Used

- Database Management System (DBMS)
- Entity-Relationship (ER) Model
- Algorithms
- Flowcharts
- Basic database concepts
- Student and course data management

9. Expected Outcome

The system provides an organized way to manage online course information. It allows students and courses to be recorded, manages enrollment, handles assignment submissions, and displays whether assignments are submitted or pending.

10. Conclusion

The Online Course Management System demonstrates how a basic computerized system can manage student and course-related activities. The project uses an algorithm, flowchart, and ER diagram to represent the system clearly and systematically.

Project Name: Online Course Management System
Feature Set: IV
Course: BCA
