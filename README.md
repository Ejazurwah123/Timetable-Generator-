# Timetable-Generator-
Generates timetable upon the given constraints using Genetic Algorithm.

Hard Constraints
• An exam will be scheduled for each course.
• A student is enrolled in at least 3 courses. A student cannot take more than 1 exam at a
time.
• Exam will not be held on weekends.
• Each exam must be held between 9 am and 5 pm.
• Each exam must be invigilated by a teacher. A teacher cannot invigilate two exams
at the same time.
• A teacher cannot invigilate two exams in a row.

Soft Constraints
• All students and teachers shall be given a break on Friday from 1-2.
• A student shall not take more than 1 exam consecutively.
• If a student is enrolled in an MG course and a CS course, it is preferred that their
MG course exam be held before their CS course exam.
• Two hours of break in the week such that at least half the faculty is free in one slot
and the rest of the faculty is free in the other slot so the faculty meetings shall be
held in parts as they are now.


Input & Output
Input data for each exam are teachers’ names, students ‘names, exam duration, courses
(course codes), and a list of allowed classrooms (e.g. C301 to C310)
Output data are classroom and starting time for each exam along with course code and
invigilating teacher. Time is determined by day (Monday to Friday) and the start hour of the exam.
• Output will be a chromosome that satisfies all hard constraints and soft
constraints at least three. (as much as you can)
• You have to display a list of all hard and soft constraints that are fulfilled in the output.
• Don’t forget to show fitness values at each iteration.
• The output should be in a proper format preferably a Table or a Chart.


