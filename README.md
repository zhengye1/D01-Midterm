This repository contains the implementation of Question 3 in 2015 midterm

Suppose you are working on designing (a part of) a university grades management system. The student's <code>GradesMgr </code> must support the following operations:
1. <code>addGrade(int, String) </code> adds the given grade (integer between 0 and 100) for a given course ID (string) to this student's record,
2. <code>inGoodStanding()</code> returns whether this student is in good standing.
3. <code>cgpa()</code> returns this students' cumulative GPA (floating point number between 0 and 4), and
4. <code>printTranscript()</code> return a nicely formatted string with this student's academic history.

Grades for graduate and for undergraduate students are maintained differenlty. For undergraduate students,
1. a grade is stored as an integer between 0 and 100, 
2. a grade of at least 50 is considered a passing grade, and
3. a student is considerered "in good standing" if her CGPA is not below 1.5

For graduate students,
1. a grade is stored as a letter A+, A, A-, B+, B, B- or F,
2. a passing grade is a grade of B- or above, and 
3. a student is considered "in good standing" if there are no failing grades.

Task: Use Factory design pattern to design and implement this part of the system. Consider the starter for a UML class diagram below. The <code>GradesMgr</code> uses two Maps: one to store and maintain grades and another to look up course information.

