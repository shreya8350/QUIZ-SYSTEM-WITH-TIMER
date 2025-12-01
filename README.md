Java Quiz System – Swing-Based Application

A fully interactive, GUI-based Java Quiz System built using Java Swing.
This application provides a complete quiz experience with user login, admin login, multiple difficulty levels, timed quizzes, question navigation, automatic evaluation, and graphical results using a custom pie chart.

✨ Features

👤 User Module

User login with username & full-name validation

Beginner, Intermediate & Advanced level quizzes
15-minute countdown timer
Question navigation panel (jump to any question)
Auto-save selected answers
Previous / Next navigation
Real-time color indicators:
Yellow → Current question
Green → Answered
Grey → Unanswered

🛡 Admin Module

Admin login with secure credentials
Access to quiz results stored in the internal database class
View username, full name, level, score, attempts, and performance summary

📝 Quiz Engine

Dynamic question loading from a dedicated QuestionBank
Shuffles through levels: Beginner | Intermediate | Advanced
Tracks:
Correct answers
Incorrect answers
Unattempted questions
Total attempted

📊 Result & Analytics

Automatic evaluation after submission
Display of:
Total score
Percentage score
Performance breakdown
Custom Pie Chart Renderer
Correct (Green)
Incorrect (Red)
Unattempted (Gray)

🧱 Technologies Used

Java (Core + OOP)
Java Swing (JFrame, JPanel, Layout Managers)
AWT (Graphics, Colors, Events)
Swing Timer for quiz countdown
Custom Drawing for charts
