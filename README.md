Download Link: https://assignmentchef.com/product/solved-cs143-assignment-3
<br>
For this assignment you will complete programming challenges 4, 5, and 6. Each challenge leads from one to the next. When you are finished, submit a single working application that consists of the code that results from doing the three programming challenges, one after another.

<h3>Chapter 10, Programming Challenge 4</h3>

Start by implementing Challenge 4 in chapter 10.

Design an <strong><em>Essay</em></strong> class that extends the <strong><em>GradedActivity</em></strong> class presented in chapter 10 (edition 3) of the Gaddis text for the course. The <strong><em>Essay</em></strong> class should determine the grade a student receives for an essay. The student’s essay score can be up to 100 and is determined in the following manner:

<ul>

 <li>Grammar: 30 points</li>

 <li>Spelling: 20 points</li>

 <li>Correct length: 20 points</li>

 <li>Content: 30 points</li>

</ul>

<h3>Chapter 10, Programming Challenge 5</h3>

In a course, a teacher gives the following tests and assignments:

<ul>

 <li>A lab activity that is observed by the teacher and assigned a numeric score</li>

 <li>A pass/fail exam that has 10 questions. The minimum passing score is 70</li>

 <li>An essay that is assigned a numeric score</li>

 <li>A final exam that has 50 questions</li>

</ul>

Write a class named <strong><em>CourseGrades</em></strong>. The class should have a <strong><em>GradedActivity</em></strong> array named grades as a field. The array should have four elements, one for each of the assignments previously described. The class should have the following methods:

<strong><em>setLab</em></strong> – This method should accept a <strong><em>GradedActivity</em></strong> object as its argument. This object should already hold the student’s score for the lab activity. Element 0 of the <strong><em>grades</em></strong> field should reference this object.

<strong><em>setPassFailExam</em></strong> – This method should accept a <strong><em>PassFailExam</em></strong> object as its argument. This object should already hold the student’s score for the pass/fail exam. Element 1 of the <strong><em>grades</em></strong> field should reference this object.

<strong><em>setEssay</em></strong> – This method should accept as <strong><em>Essay</em></strong> object as its argument. See Programming Challenge 4 for the <strong><em>Essay</em></strong> class. This object should already hold the student’s score for the essay. Element 2 of the <strong><em>grades</em></strong> field should reference this object.

<strong><em>setFinalExam</em></strong> – This method should accept a <strong><em>FinalExam</em></strong> object as its argument. This object should already hold the student’s score for the final. Exam. Element 3 of the <strong><em>grades</em></strong> field should reference this object.

<strong><em>toString</em></strong> – This method should return a string that contains the numeric scores and grades for each element in the <strong><em>grades</em></strong> array.

<h3>Chapter 10, Programming Challenge</h3>

Modify the <strong><em>CoursesGrades</em></strong> class created in Programming Challenge 5 so it implements the following interface:

Public interface Analyzable {

Double getAverage();

GradedActivity getHighest();

GradedActivity getLowest();

}

The <strong><em>getAverage</em></strong> method should return the average of the numeric scores stored in the <strong><em>grades</em></strong> array. The <strong><em>getHighest</em></strong> method should return a reference to the element of the <strong><em>grades</em></strong> array that has the highest numeric score. The <strong><em>getLowest</em></strong> method should return a reference to the element of the <strong><em>grades</em></strong> array that has the lowest numeric score.