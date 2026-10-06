# Job Posting System

A Python-based job posting and application management system with a graphical user interface, user authentication, employer tools, and database integration.

## About the Project

Job Posting System is a desktop application designed to simulate a job recruitment platform.

The system supports different user roles such as **job seekers, employers, and administrators**. Employers can manage job postings, job seekers can browse available positions and submit applications, and administrators can manage the overall system.

The project was developed to practice object-oriented programming, GUI development, database operations, authentication, and modular software design in Python.

## Technologies Used

- Python
- PyQt
- Qt Designer
- SQLite
- Object-Oriented Programming (OOP)
- Database Management
- GUI Development

## Features

### User Authentication
- User registration
- User login
- Role-based access
- Authentication management

### Job Seekers
- Browse available job postings
- View job details
- Search and filter jobs
- Submit job applications

### Employers
- Employer dashboard
- Create and manage job postings
- Review application-related information
- Manage job information

### Administration
- Administrative panel
- System management
- User and platform-related operations

### Additional Features
- Graphical user interface
- Search and filtering system
- Database integration
- Report generation
- Modular application structure

## Project Structure

Some of the main components of the project are:

- `main.py` - Entry point of the application
- `database.py` - Handles database-related operations
- `auth_manager.py` - Handles authentication
- `user.py` - Base user structure
- `job_seeker.py` - Job seeker functionality
- `employer.py` - Employer functionality
- `job.py` - Represents job postings
- `application.py` - Represents job applications
- `admin_panel.py` - Administrative functionality
- `report_generator.py` - Handles report generation
- `search_filter_widget.py` - Search and filtering functionality
- `main_window.py` - Main application window

The project also contains separate screen classes and Qt `.ui` files for the graphical user interface.

## User Interface

The application contains multiple interfaces, including:

- Login and registration screens
- Main window
- Job listing screen
- Job detail screen
- Application screen
- Employer dashboard
- Admin panel
- Search and filtering interface

The `.ui` files were created for the graphical interface and are used together with the generated Python UI files.

## Installation

Install the required Python dependencies:

```bash
pip install -r requirements.txt
```

## Running the Application

Run the main Python file:

```bash
python main.py
```

On systems where Python 3 is accessed using `python3`:

```bash
python3 main.py
```

## Project Report

The repository includes:

`JobPostingSystem_report.pdf`

The report contains additional information about the project's analysis, design, implementation, and system structure.

## Author

**Tarık Emir Yılmaz**
