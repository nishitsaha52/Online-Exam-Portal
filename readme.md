# 🌐 Online Examination System

## Introduction 📚

This project is an **Online Examination System**, a web-based application developed using PHP, CodeIgniter, and MySQL Database. It offers an examination platform for students in colleges or universities, providing an effortless and efficient method for creating and conducting examinations. The system boasts a pleasant user interface using the Bootstrap Framework, AdminLTE Template, and other libraries, ensuring an enhanced user experience with user-friendly features and functionalities.

---

## About the Online Examination System 📋

### Technologies Used 💻

- **XAMPP v3.3.0**
- **PHP**
- **CodeIgniter**
- **MySQL Database**
- **HTML**
- **CSS**
- **JavaScript**
- **Ajax**
- **jQuery**
- **Bootstrap**
- **Font Awesome**
- **AdminLTE**
- **DataTables**

---

### User Roles and Permissions 🔑

#### Administrator 🛠️

- **Full Access**: Access all administrative features and functionalities.
- **Manage Users**: Add, edit, and delete information about faculty and students. Grant user access to Lecturers and Students.
- **Exam Management**: Access Exam Results, add questions for Lecturers, and clear all data in the database.

#### Lecturer/Faculty 👩‍🏫

- **Question Management**: Add questions for the classes or courses they handle.
- **Exam Creation**: Create or conduct exam sets with relevant information such as the Exam Title and Schedule.
- **Result Viewing**: View and print Exam Results per Exam Set. Access student result information for each exam set.

#### Student 👩‍🎓

- **Exam Participation**: Take exams created by their faculties or lecturers. The system automatically submits the student's completed answers when the countdown reaches zero.

---

## Features ✨

### Administrator 🛠️

- **Dashboard Page**
- **Department Management**: Add, list, edit, delete, import, print, export, and copy departments.
- **Class Management**: Add, list, edit, delete, import, print, export, and copy classes.
- **Course Management**: Add, list, edit, delete, import, print, export, and copy courses.
- **Lecturer Management**: Add, list, edit, delete, import, print, export, and copy lecturers.
- **Student Management**: Add, list, edit, delete, import, print, export, and copy students.
- **Relation Management**: Set multiple classes for lecturers and departments for classes.
- **Question Management**: Add, list, edit, delete, and view questions.
- **Reports**: List all exams and view, print, or download exam results.
- **User Management**: List, edit, delete, import, print, export, and copy users.
- **Account Management**: Update account details and credentials.
- **Database Management**: Clear all data in the database (except the admin user).
- **Login and Logout**

### Lecturer/Faculty 👩‍🏫

- **Login**
- **Exam Management**: Add, list, edit, delete, and re-generate exam tokens.
- **Exam Results**: View, download, or print exam results.
- **Account Management**: Update system account credentials.
- **Logout**

### Student 👩‍🎓

- **Login**
- **Exam List**: List all exam sets available.
- **Take Exam**: Take exams, mark questions as doubts, and submit answers.
- **Exam Timer**: Exam countdown and timer.
- **Exam Results**: View exam results.
- **Account Management**: Update system account credentials.
- **Logout**

---

## System Snapshots 📸

1. **Login Page**
   ![Login Page](https://github.com/nishitsaha52/Online-Exam-Portal/blob/main/Pic/CI-PHP-OES-Login-Page.png)
   - Online Examination System

2. **Admin Dashboard Page**
   ![Login Page](https://github.com/nishitsaha52/Online-Exam-Portal/blob/main/Pic/CI-PHP-OES-Admin-Dashbaord.png)
   - Online Examination System

3. **Admin User List Page**
   ![Admin User List Page](https://github.com/nishitsaha52/Online-Exam-Portal/blob/main/Pic/CI-PHP-OES-Admin-User-list.png)
   - Online Examination System

4. **Lecturer Exam List Page**
   ![Lecturer Exam List Page](https://github.com/nishitsaha52/Online-Exam-Portal/blob/main/Pic/CI-PHP-OES-Lecturer-Exam-list.png)
   - Online Examination System

5. **Lecturer Exam Result Page**
   ![Lecturer Exam Result Page](https://github.com/nishitsaha52/Online-Exam-Portal/blob/main/Pic/CI-PHP-OES-Lecturer-Exam-result.png)
   - Online Examination System

6. **Student Exam List Page**
   ![Student Exam List Page](https://github.com/nishitsaha52/Online-Exam-Portal/blob/main/Pic/CI-PHP-OES-Student-Exam-list.png)
   - Online Examination System

7. **Student Take Exam Page**
   ![Student Take Exam Page](https://github.com/nishitsaha52/Online-Exam-Portal/blob/main/Pic/CI-PHP-OES-Student-Take-Exam.png)
   - Online Examination System

---

## How to Run? 🚀

### Requirements

1. Download and install any local web server such as XAMPP.
2. Download the provided source code zip file.

### System Installation/Setup 🛠️

1. Open your XAMPP Control Panel and start Apache and MySQL.
2. Extract the downloaded source code zip file.
3. Copy the extracted source code folder and paste it into the XAMPP's "htdocs" directory.
4. Browse PHPMyAdmin in a browser. i.e. [http://localhost/phpmyadmin](http://localhost/phpmyadmin)
5. Create a new database named `exam_db`.
6. Import the provided SQL file located inside the `database` folder (`exam_db.sql`).
7. Browse the Online Examination System in a browser. i.e. [http://localhost/ci_exam/](http://localhost/ci_exam/)

### Admin Default Access

- **Email**: admin@mail.com
- **Password**: admin123

---

This source code was developed for educational purposes. You can download the source code for free and modify it as needed.

---
