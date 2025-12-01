# QUIZ-SYSTEM-WITH-TIMER

**Java Quiz System – Desktop Application (Swing-Based)**
A fully interactive and user-friendly Java Quiz Application built using Java Swing, designed for students, instructors, and beginners to test their knowledge across multiple difficulty levels.
The project includes user login, admin login, timed quiz sessions, question navigation, auto-evaluation, pie-chart visualization, and result management.

✨** Features**

👤 **User Login**
Simple and intuitive login interface
Username and full-name validation
Auto-watermark placeholders
Dynamic image loading support

🛠 **Admin Panel**
Dedicated admin login
Secure credential validation
Access to quiz results (extendable for database integration)

📚 **Multi-Level Quiz System**
Beginner, Intermediate, and Advanced difficulty levels
Randomized question selection from a structured question bank
Clean and responsive layout built with GridBagLayout, BorderLayout, and BoxLayout

⏳ **Countdown Timer**
15-minute countdown for every quiz
Auto-submit when time expires

📌 **Smart Question Navigation**
Jump to any question using horizontal scrollable buttons
Color-coded indicators:
Yellow: Current Question
Green: Answered
Gray: Unanswered

📝 **Answer Management**
Stores user responses per question
Supports navigating back and changing answers
Auto-save behavior before switching questions

📊 **Result Summary with Pie Chart**
Final score breakdown: Correct, Incorrect, Unattempted
Percentage calculation
Graphical Pie Chart visualization
Legend with color-coded keys
Option to return to login screen

🧱 **Modular Code Structure**
The project follows a clean OOP architecture with dedicated classes:
Component	Description
LoginFrame	User login screen
AdminLoginFrame	Admin authentication
LevelSelectionFrame	Difficulty selection
QuizFrame	Full quiz engine with timer + navigation
ResultFrame	Score visualization and summary
QuizDatabase	Stores quiz result entries
Question & QuestionBank	Question structure and repository

🚀 **Technologies Used**
Java 8+
Java Swing
AWT Layout Managers
Collections Framework
Swing Timer
Custom Graphics (Pie Chart using Graphics2D)
