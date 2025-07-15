# School Management System  

A C++ and Qt-based school management system with separate interfaces for admin, teacher, and student. It manages student records, teachers, attendance, exams, and results using a MySQL database.

## Table of Contents  
- [Features](#features)  
- [Structure](#structure)  
- [Database](#database)  
- [Build & Run](#build--run)   

## Features  
- **Student Management**: Add, update, delete, and view student data.  
- **Teacher Management**: Manage teacher info and assignments.  
- **Class Scheduling**: Assign class schedules for students and teachers.  
- **Attendance**: Mark and view attendance.  
- **Exam Management**: Add, update, and remove exams.  
- **Exam Results**: Enter and view exam results.  
- **Login System**: Basic authentication for admin, teacher, and student panels.  
- **Role Separation**: Different interfaces for each role.  
- **Data Storage**: MySQL database integration.  
- **UI**: Built with Qt Designer and styled with basic stylesheets.  

## Structure  

### Admin Panel  
- **AdminPanel.cpp/h**: Main admin dashboard  
- **StudentManagement.cpp/h**: Student records  
- **TeacherManagement.cpp/h**: Teacher records  
- **ClassScheduleManagement.cpp/h**: Class timing  
- **AttendanceManagement.cpp/h**: Attendance  
- **ExamManagement.cpp/h**: Exam setup  

### Student Panel  
- **StudentPanel.cpp/h**: Dashboard  
- **StudentInfo.cpp/h**: Profile  
- **StudentAttendance.cpp/h**: View attendance  
- **StudentExam.cpp/h**: View exams  
- **StudentResult.cpp/h**: View results  
- **StudentSchedule.cpp/h**: View schedule  

### Teacher Panel  
- **TeacherPanel.cpp/h**: Dashboard  
- **AttendanceMarkingViewing.cpp/h**: Mark/view attendance  
- **ClassScheduleViewing.cpp/h**: View class timings  
- **TeacherExamManagement.cpp/h**: Exams  
- **ExamResultManagement.cpp/h**: Manage results  

### Core  
- **main.cpp**: Launch and UI setup  
- **Login.cpp/h**: Login screen  
- **DatabaseSetup.cpp/h**: MySQL connection and table creation  

### UI  
- All panels have `.ui` files for Qt Designer  

### Resources  
- **Images.qrc**: Icons and images  

## Database  
- **Backend**: MySQL  
- **Tables**: Students, Teachers, Classes, Exams, Attendance, Results  
- **Setup**: Handled by `DatabaseSetup.cpp`  
- **Connector**: Configure MySQL connector path in `.pro` file  

## Build & Run  

### Prerequisites  
- Qt 6.8.2 or compatible  
- C++17 compiler (e.g., MinGW 64-bit)  
- MySQL server + C connector  

### Steps  
1. Clone the repository:  
   ```bash
   git clone https://github.com/SyedMuhammadHunain/school-management-system.git
   cd school-management-system
