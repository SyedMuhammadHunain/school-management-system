# School Management System Project

### Developed Using C++ and Qt Framework  
This **School Management System** is a desktop application designed to streamline administrative tasks in educational institutions. It provides features for managing students, teachers, courses, and schedules with an intuitive graphical interface.

---

## Members / Contributors
- **Sarim Khan**
- **Maaz**
- **Syed Muhammad Hunain**

---

## Project Overview
This project is organized into several components, each focusing on specific functionalities to ensure clarity and ease of use:

1. **Main.cpp**  
   - The entry point of the application.
   - Handles initialization, event loops, and application termination.

2. **StudentManager.h / .cpp**  
   - Manages student records, including adding, updating, and deleting student information.
   - Provides search functionality for quick access to student details.

3. **TeacherManager.h / .cpp**  
   - Handles teacher profiles, including their assigned courses and schedules.
   - Allows for adding, updating, and removing teacher records.

4. **CourseManager.h / .cpp**  
   - Manages course details, including course codes, descriptions, and assigned teachers.
   - Facilitates course enrollment for students.

5. **ScheduleManager.h / .cpp**  
   - Organizes class schedules and ensures no conflicts between courses.
   - Provides a visual representation of weekly schedules.

6. **DatabaseManager.h / .cpp**  
   - Handles data storage and retrieval using SQLite.
   - Ensures data consistency and integrity across all modules.

7. **UI Components**  
   - Built using Qt Designer for a user-friendly interface.
   - Includes forms for managing students, teachers, courses, and schedules.

---

## How to Run the Application
To run the School Management System, follow these steps:

1. **Set Up the Environment**  
   - Install Qt Creator and ensure the C++ compiler is configured.
   - Clone the repository to your local machine.

2. **Prepare the Database**  
   - Ensure the SQLite database file (`school.db`) is in the project directory.
   - The database should include tables for students, teachers, courses, and schedules.

3. **Build and Run**  
   - Open the project in Qt Creator.
   - Build the project using the provided `.pro` file.
   - Run the application directly from Qt Creator.

---

## Features
- Manage student and teacher records efficiently.
- Add, update, and delete courses with ease.
- Organize class schedules and resolve conflicts.
- Search functionality for quick access to records.
- User-friendly interface powered by Qt.

---

## Acknowledgments
This project was developed as part of an academic assignment. Special thanks to the contributors for their hard work and dedication.

---
