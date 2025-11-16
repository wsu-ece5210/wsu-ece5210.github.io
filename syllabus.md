---
layout: default
title: Syllabus
nav_order: 1
---

# Instructor

{% assign instructors = site.staffers | where: 'role', 'Instructor' %} {% for staffer in instructors %} {{ staffer }} {% endfor %}


# Meeting Times

| Session | Day | Time | Location |
|---------|-----|------|----------|
| Lecture | MW | 4:30PM-7:20PM | NB 236 |
| Lab | MW | 4:30PM-7:200PM | NB 112 |


# Course description 

Theory, application, and implementation of digital signal processing (DSP) concepts, from the design and implementation perspective. Topics include Fast Fourier transforms, adaptive filters, state-space algorithms, random signals, and spectral estimation.


# Learning outcomes

The student will:
- Design and implement digital signal processing systems
- Understand discrete-time transform methods
- Design digital filters
- Become familiar with DSP on ARM processors



# Textbook 

Discrete-Time Signal Processing, 3rd Edition, by Oppenheim and Schafer, Pearson, 2010. ISBN-13: 978-0131988422


# Assignments 

You will have weekly homework assignments.  These assignments are based on selected problems from the textbook from various signal processing textbooks and old examinations.  You will be given Jupyter Notebooks to complete the assignments.  I strongly recommend that you work the problems out by hand (pencil and paper) and then complete the Notebook after you have worked the problem out.

Homework will be distributed and collected via GitHub.  Homework will be graded based on correctness.  You will receive feedback each week based on your work after it is graded.  You are welcome to work together in groups to solve the problems, but the solutions you submit must be your own.  I strongly encourage you to fully understand your submission because the examinations, which are an individual effort, will be based on the homework problems.

Each homework is associated with a particular exam (see schedule).  If your score on that exam exceeds the homework average for the homeworks associated with the exam, the exam grade will replace the homework grade.  The opposite is not true. If you score below the homework average on the exam, the homework grade will be used.

Occasionally pop quizzes will be given in class and will count towards your homework grade.  These quizzes will be based on the material covered in the previous week.



# Laboratory assignments 

We will have a weekly laboratory.  In this laboratory we will be implementing the theoretical concepts learned in lecture on ARM Cortex microprocessors for real-time DSP applications.  You will be provided STM32 discovery boards for these assignments.  The lab computers will have the STMCubeIDE installed on them to compile your code.  However, the IDE is free, and you are welcome to work on your personal laptops if you prefer.

The labs are meant to be an individual effort.  Because they are mostly software implementations, you are expected to implement the algorithms yourselves.  If you are sharing code or copying code you will automatically fail the course and will be referred to the dean of students for academic discipline.  The moment you start looking at each other's code, you have crossed the line.

The lab has 12 functioning stations.  However, there are more than 12 students in the course.  As such, we are going to need to share equipment.  You should be able to write your code on your machines and when it passes the tests, you can hook your board up to the lab equipment.

You will be issued a STM32F769I Discovery board and some cables to complete the labs.  If you fail to turn these back to the instructor at the semester you will receive an E grade.  If you withdraw from the course without returning this equipment, you will be barred from graduation until you return it.



# Late work policy 

Late work will not be accepted after the due date.  Once the GitHub repository is closed, you will not be able to submit your work.  Similarly, once the Canvas assignment is closed, you will not be able to submit your lab reports.



# Exams 

There will be two midterm examinations during the semester.  There will also be a comprehensive final examination.  The objective of the examinations will be to test your knowledge of fundamentals and your ability to apply the concepts learned in the class in situations you may not have encountered before.  You may bring one sheet of formulas for the first exam, two sheets of formulas for the second exam, and three sheets of formulas to the final exam.



# Project 

There will be a final project for the course.  The project will involve designing and implementing a digital signal processing system.  The details of the project will be provided later in the semester.


# Grading

As shown below, grades are based on the weighted average of the exams, homework, and laboratory assignments.

| Item | Percentage |
|------|------------|
| homework | 10% |
| labs | 20% |
| midterms | 20% |
| final | 20% |
| project | 10% |

Letter grades are assigned according to the scale below. These are the maximum cutoffs for each letter.  As an instructor, I reserve the right to lower the percentage cutoffs at the end of the semester as appropriate.

| Letter | Percentage |
|--------|------------|
| A | 93% |
| A- | 90% |
| B+ | 86% |
| B | 83% |
| B- | 80% |
| C+ | 76% |
| C | 73% |
| C- | 70% |
| D+ | 66% |
| D | 63% |


# Campus closure 

If the class needs to be held virtually due to campus closure, sickness, or any other appropriate reason, you will receive a notification from your instructor via Canvas. Remember that attendance is just as important virtually as in the face-to-face option. During video conferencing, be present, avoid multitasking, and wait for your turn to speak and/or contribute to the class discussion. Be courteous and respectful of your classmates. As stated in the class recording policy, you may not record any segments and/or the full class unless you have authorization from the instructor. If you do not have the technology necessary for video conferencing, contact your instructor as soon as possible. This policy applies also to virtual office hours.



# Disability services 

If you require accommodations or services due to a disability, please contact Disability Services (DS) in room 181 of the Student Services Center (Ogden campus) or room 262 Building D2 (Davis Campus). Disability Services can arrange to provide course materials (including this syllabus) in alternative formats upon request.



# Professionalism and respect 

The sense of human dignity and belonging of all members of the Weber State community is a necessary part of a healthy learning environment. Therefore, you should practice civil deportment, and avoid treating others in a manner that is demeaning or derisive in any respect. Diverse viewpoints and opinions are welcome in this class, and we will practice the mutual deference so important in the world of work when expressing them. Thus, while I encourage you to share your opinions, you will be expected to do so in a manner that is respectful toward others.



# Recording 

The university prohibits students from recording class lectures unless the faculty member grants explicit permission (PPM 6-22.6.6). Any lectures recorded and posted on Canvas or shared to your Weber State University student email are for the exclusive use of students enrolled in the class and may not be shared without previous authorization. Violations will be referred to the Dean of Students for adjudication under the student code (PPM 6-22).



# Academic integrity 

As part of the student code (PPM 6-22), you are expected to be academically honest and ethical. Academic dishonesty includes cheating; plagiarizing; colluding with others to be dishonest; falsifying information; giving, selling, or receiving unauthorized course or test information; using a tool or other aid not explicitly permitted by your instructor such as generative AI (e.g. ChatGPT) to complete assignments or exams; or infringing on others' copyrights and intellectual property. Academic dishonesty can have serious consequences in the class and/or at WSU. Be sure, if you borrow an idea, to express it in language entirely your own and let the reader know the idea's source in a citation note.

For software submissions, I will routinely run your code through a plagiarism detection system.  If you are caught cheating, you will receive a zero for the assignment and may be reported to the Dean of Students.  A second infraction will result in a failing grade for the course.



# Core beliefs and challenging subject matter 

Faculty members teach in line with the best standards of their discipline and choose materials appropriate to help the class master expected course outcomes. A student may disagree with course content, but unless the content conflicts with a student's core beliefs, students are expected to engage professionally, as described above. If after reading the syllabus and class program, you expect there will be a conflict with your core beliefs, you should consider withdrawing from the class before the last day to drop classes without penalty. If you find this solution unworkable, you may request a resolution from the instructor, in writing with a copy to the department chair, explaining what burden the class requirement would place on your beliefs. Students who are not satisfied with the outcome may seek assistance through the Office of Equal Opportunity.



# Student responsibilities 

As a student at Weber State University, you are expected to act responsibly and appropriately as you attend a public institution of higher education. When you enroll as a student at WSU, you agree to abide by the standards of appropriate and responsible behavior outlined in the student code (PPM 6-22). This applies to your behavior as an individual when participating in group settings on campus and if you represent Weber State University at an off-campus event. Choosing to ignore these important student responsibilities could result in university disciplinary actions.



# Harassment, discrimination, and sexual misconduct 

Weber State University is committed to providing an environment free from harassment and other forms of discrimination based upon race, color, national origin, pregnancy, and pregnancy-related conditions such as childbirth, false pregnancy, miscarriage, abortion, or related conditions, (including recovery), genetics, disability (see PPM 3-34), religion, sex, sexual orientation, gender identity/expression, veteran, active military status, age (over 40 in employment discrimination), and other classifications protected by law. If you have questions regarding the university's policy against discrimination and harassment, or if you have questions about reporting discrimination or harassment, you may contact the university's Office of Equal Opportunity (OEO) by calling 801-626-6240 or visit the OEO website.


