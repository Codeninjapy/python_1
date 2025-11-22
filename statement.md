Project Statement: Student Grades Management System

1. Problem Statement

In educational environments, manually tracking student grades using paper records or scattered digital files can be inefficient, prone to errors, and difficult to update. Teachers and administrators often struggle to quickly retrieve or modify specific student data when needed.

There is a need for a streamlined, digital solution that allows for the centralized management of student academic performance, enabling quick additions, updates, and removal of records without the complexity of manual bookkeeping.

2. Scope of the Project

This project focuses on building a lightweight, console-based application using Python. The scope is defined as follows:

Data Structure: Utilization of Python dictionaries for fast lookups and data storage.

Core Operations: Implementation of CRUD (Create, Read, Update, Delete) functionality for student records.

Interface: A simple Command Line Interface (CLI) that runs in a continuous loop until the user decides to exit.

Limitations: Currently, the system stores data in temporary memory (runtime only) and does not persist data to a database or file after the program closes.

3. Target Users

The primary users of this application include:

Teachers & Instructors: For managing grades of small classes or specific subject groups.

Teaching Assistants: To assist in updating marks during grading periods.

School Administrators: For quick entry and modification of student records.

Programming Students: As an educational tool to understand Python data structures and function management.

4. High-Level Features

The system provides the following specific functionalities based on the menu-driven architecture:

Student Registration: Allows the user to input a student's name and grade to add them to the system.

Grade Modification: Enables the user to update the grade of an existing student by searching for their name. Includes validation to ensure the student exists before updating.

Record Deletion: Provides the ability to permanently remove a student's record from the dictionary.

Data Retrieval: Displays a comprehensive list of all students and their associated grades currently stored in the system.

Interactive Menu: A user-friendly loop that keeps the program running, allowing multiple operations to be performed in a single session.
