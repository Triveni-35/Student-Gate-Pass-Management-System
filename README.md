You can view working of code and its output in PDF given <br>
Project Overview: Gate Pass Management System
The Gate Pass Management System is a command-line application designed to streamline the process of applying for, approving, and managing gate passes for students and administrators in an educational institution. The project employs object-oriented programming principles in Python and utilizes JSON files for data storage, allowing for easy management and retrieval of student, admin, and gate pass request information.

Key Features:
User Management:

Student Registration: Students can register with their roll number, name, password, and class. This information is stored in a JSON file (students.json).
Admin Registration: Administrators can register with a username and password, with their details stored in admins.json.
Authentication:

Students and admins can log in using their credentials. The application checks for valid user data against the JSON files to ensure security.
Gate Pass Requests:

Apply for Gate Pass: After logging in, students can submit gate pass requests that include their roll number, name, class, reason, and status. These requests are stored in gate_pass_requests.json.
Check Status: Students can check the status of their submitted gate pass requests.
Withdraw Requests: Students have the option to withdraw their gate pass requests if needed.
Admin Management:

After logging in, admins can view all gate pass requests submitted by students. They have the authority to approve or reject these requests. The status changes reflect in the students' records when they check their gate pass status.
Data Persistence:

The application uses JSON files to persist user and gate pass request data, ensuring that information is retained between program runs.
Technical Stack:
Programming Language: Python
Data Storage: JSON files for storing user information and gate pass requests
Structure: Object-oriented design with classes for managing students, admins, and gate pass requests.
Benefits:
Simplifies the gate pass management process for educational institutions.
Provides a user-friendly command-line interface for easy access.
Ensures data integrity and security through authentication mechanisms.
