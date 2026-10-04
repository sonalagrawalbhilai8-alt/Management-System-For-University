# Management System For University
.
# 🎓 University Management System

A **Java-based University Management System** designed to manage student and teacher information, attendance/leave records, examination details, fee information, and other university-related activities through a graphical user interface.

## 📌 About the Project

The University Management System is a desktop application developed using **Java Swing** and **MySQL**. It provides a centralized interface for managing different academic and administrative tasks.

The application includes separate modules for managing:

- 👨‍🎓 Student information
- 👨‍🏫 Teacher information
- 📝 Examination and marks
- 💰 Student fee details
- 📅 Student leave
- 📅 Teacher leave
- 🔍 Student and teacher records
- 🔄 Updating student and teacher information
- 🔐 Login system

## ✨ Features

### 🔐 Login System
- User login interface
- Username and password authentication

### 👨‍🎓 Student Management
- Add new student
- View student details
- Search students by roll number
- Update student information
- Manage student leave
- View examination results
- Manage student fee details

### 👨‍🏫 Teacher Management
- Add new teacher
- View teacher details
- Search teachers by employee ID
- Update teacher information
- Manage teacher leave

### 📚 Examination Management
- Enter student marks
- View examination details
- Search results using roll number
- Display semester information

### 💰 Fee Management
- View fee structure
- Update student fee information
- Record fee payments

### 🖥️ Graphical User Interface
The application uses **Java Swing** components to provide a desktop-based graphical interface.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| **Java** | Core programming language |
| **Java Swing** | Graphical User Interface |
| **AWT** | GUI and event handling |
| **MySQL** | Database management |
| **JDBC** | Java-MySQL database connectivity |
| **NetBeans** | Development environment |
| **JCalendar** | Date selection |
| **rs2xml** | Displaying database results in tables |

## 📁 Project Structure

```text
University Management System/
│
├── src/
│   ├── icons/
│   │
│   └── university/
│       └── management/
│           └── system/
│               ├── About.java
│               ├── AddStudent.java
│               ├── AddTeacher.java
│               ├── Conn.java
│               ├── EnterMarks.java
│               ├── ExaminationDetails.java
│               ├── FeeStructure.java
│               ├── Login.java
│               ├── Marks.java
│               ├── Project.java
│               ├── Splash.java
│               ├── StudentDetails.java
│               ├── StudentFeeForm.java
│               ├── StudentLeave.java
│               ├── StudentLeaveDetails.java
│               ├── TeacherDetails.java
│               ├── TeacherLeave.java
│               ├── TeacherLeaveDetails.java
│               ├── UpdateStudent.java
│               └── UpdateTeacher.java
│
├── nbproject/
├── build.xml
└── manifest.mf
```

## ⚙️ Requirements

Before running the project, make sure you have:

- Java JDK installed
- NetBeans IDE (recommended)
- MySQL Server
- MySQL Connector/J
- Required Java libraries/dependencies

Check your Java installation:

```bash
java -version
```

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/university-management-system.git
```

### 2. Open the Project

Open **NetBeans IDE** and select:

```text
File → Open Project
```

Then select the project folder.

### 3. Configure MySQL

Create the required MySQL database and tables according to the queries used by the application.

Update the database connection details in:

```text
Conn.java
```

with your own MySQL username, password, database name, and connection settings.

### 4. Add Required Libraries

Make sure the required external libraries are available in the project, including libraries used for:

- MySQL JDBC connectivity
- `rs2xml`
- `JCalendar`

### 5. Run the Application

Run:

```text
Splash.java
```

The application will open with the splash screen and then display the login interface.

## 🧩 Main Modules

```text
                    University
                    Management
                      System
                         │
       ┌─────────────────┼─────────────────┐
       │                 │                 │
    Students          Teachers        Examination
       │                 │                 │
   ┌───┴───┐         ┌───┴───┐        ┌───┴───┐
   │       │         │       │        │       │
 Details  Fees     Details  Leave    Marks   Results
   │
 Leave
```

## 🗄️ Database

The application uses **MySQL** to store and retrieve information.

Database connectivity is handled using **JDBC**.

The `Conn.java` class is responsible for establishing the connection between the Java application and MySQL database.

## 🎯 Learning Objectives

This project demonstrates practical implementation of:

- Java programming
- Object-Oriented Programming
- Java Swing
- GUI design
- Event handling
- JDBC
- MySQL database connectivity
- CRUD operations
- Exception handling
- Form validation
- Searching and updating database records

## 🔮 Future Improvements

The project can be enhanced by adding:

- 📊 Admin dashboard with statistics
- 🔑 Role-based authentication
- 👨‍🎓 Student login portal
- 👨‍🏫 Teacher login portal
- 📱 Modern responsive interface
- 📧 Email notifications
- 📄 PDF report generation
- 📊 Attendance analytics
- 🔔 Automatic notifications
- ☁️ Cloud database integration
- 🔒 Improved password security

## 🤝 Contribution

Contributions and improvements are welcome.

To contribute:

```bash
git clone https://github.com/your-username/university-management-system.git
```

Create a new branch:

```bash
git checkout -b feature/new-feature
```

Make your changes, commit them, and create a pull request.

## 📜 License

If this project is based on or adapted from an existing project, please retain the original author's license and attribution requirements.

If you are the original author, add the license you want to use here.

## 👩‍💻 Author

**Sonal Agrawal**

B.Tech Computer Science Engineering (AI)

---

⭐ If you find this project useful, consider giving the repository a star!
