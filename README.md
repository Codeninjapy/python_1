Student Grades Management System

📖 Overview

The Student Grades Management System is a lightweight, console-based Python application designed to help teachers or administrators manage student academic records efficiently. It utilizes a dictionary-based data structure to allow for fast storage, retrieval, and modification of student names and their corresponding grades.

This project serves as a practical implementation of Python fundamentals, including functions, loops, conditional statements, and data structures.

🚀 Features

The application offers a menu-driven interface with the following capabilities:

Add Student: Create new records with a student's name and grade.

Update Student: Modify the grade of an existing student. Checks if the student exists before updating to prevent errors.

Delete Student: Remove a student's record from the system permanently.

View All Students: Display a comprehensive list of all students and their grades currently stored in the system.

Error Handling: Basic validation to handle invalid menu choices or attempts to modify non-existent students.

🛠️ Technologies & Tools Used

Language: Python 3.x

IDE/Editor: VS Code / PyCharm / IDLE (compatible with any Python editor)

Interface: Command Line Interface (CLI)

⚙️ Steps to Install & Run

Prerequisites

Ensure you have Python installed on your system. You can check this by running:

python --version


Installation

Clone the repository (or download the source code):

git clone [https://github.com/Codeninjapy/python_1.git]


Navigate to the project directory:

cd student-grades-management


Running the Project

Run the script using the python command:

python_1

🧪 Instructions for Testing

To ensure the system works correctly, follow this test sequence:

Start the program: You should see the main menu.

Test Adding:

Select Option 1.

Enter Name: Sagar

Enter Grade: 90

Result: Program should confirm addition.

Test Viewing:

Select Option 4.

Result: You should see Sagar : 90.

Test Updating:

Select Option 2.

Enter Name: Sagar

Enter Grade: 95

Result: Program should confirm the update. Verify by selecting Option 4 again.

Test Deleting:

Select Option 3.

Enter Name: Sagar

Result: Program should confirm deletion. View list (Option 4) to confirm it is empty.

Test Invalid Input:

Try updating a name that doesn't exist (e.g., "Rahul").

Result: Program should say "Rahul is not found!"

📸 Screenshots / Demo

(If you have actual screenshots, upload them to your repo and link them here using: ![Alt Text](path/to/image.png))

Sample Output:

 student grades management system
1. Add a Student
2. Update a Student
3. Delete a Student
4. View student
5. exit
enter your choice = 1
enter student name = Alice
enter student grade = 92
Added Alice with a 92


🤝 Contributing

Feel free to fork this repository and submit pull requests. Suggestions for improvements (like adding file handling to save data permanently) are welcome!

📜 License

This project is open-source and free to use.
