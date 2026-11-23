Student Management System – C++

📌 Project Overview

This is a beginner-friendly C++ mini project that demonstrates Object-Oriented Programming (OOP) concepts using a Student class.

The program stores student details, validates marks, displays student information, and checks whether each student has passed or failed.

🎯 Concepts Used

* Classes and Objects
* Encapsulation
* Private and Public Access Specifiers
* Parameterized Constructor
* Getter Functions
* Setter Functions
* Data Validation
* Array of Objects
* Functions
* Conditional Statements (if-else)
* Loops (for loop)

⚙️ Features

1. Student Details: Stores roll number, name, and marks.
2. Data Encapsulation: Uses private data members to protect student information.
3. Constructor: Initializes student objects with values.
4. Getter Functions: Retrieves student details.
5. Setter Function: Updates marks with validation.
6. Marks Validation: Accepts marks only between 0 and 100. Invalid marks are automatically set to 0.
7. Display Details: Displays all student information.
8. Pass/Fail Checking: Students scoring 40 or above PASS; otherwise, they FAIL.
9. Update Marks: Updates Ammu’s marks from 35 to 45.

💻 Student Information

Roll No	Name	Initial Marks
101	Anila	82
102	Ammu	35
103	Ashwanth 105

Note: Ashwanth’s marks are invalid, so the program automatically sets them to 0.

Rahul’s marks are later updated from 35 to 45.

📂 Project Structure

STUDENT-MANAGEMENT/
│
├── Student_Management.cpp
└── README.md

▶️ How to Run the Program

Step 1: Compile the C++ program.

g++ Student_Management.cpp -o student

Step 2: Run the program.

./student

📊 Expected Output

Invalid marks for Meera, set to 0
Student Details
------------------------
101 | Anila | 82
102 | Ammu | 35
103 | Ashwanth | 0
Student Results
------------------------
Anila: PASS
Ammu: PASS
Ashwanth: FAIL

📚 Learning Outcome

Through this project, I learned how to implement basic Object-Oriented Programming concepts in C++. I also understood how to use constructors, getters, setters, encapsulation, arrays of objects, and data validation in a practical program.

⸻

Language: C++

Project Type: Mini Project

Topic: Object-Oriented Programming (OOP)

Author: Ashwanth MK