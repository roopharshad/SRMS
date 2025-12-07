Student Record Management System (SRMS)

A modular C-based Student Record Management System designed for learning, portfolio building, and academic projects.
The system includes file handling, login authentication, sorting, searching, CSV exporting, and login history tracking.

This project is structured professionally with separate header, source, and data files—making it ideal for a GitHub coding-skills portfolio.

🚀 Features
🔐 1. Login System

Credentials stored in data/credentials.txt

Username, password, and role support

Every successful login is recorded with timestamp in:

data/login_history.txt

📚 2. Student Data Management

Student records stored persistently in:

data/students.txt


Supports adding, editing, and saving records

🔍 3. Search Students (Feature #1)

Search by:

ID

Name

Example:

Enter ID or Name to search: John

🔢 4. Sort Students (Feature #4)

Sort student records by:

ID

Name

Marks

📤 5. Export to CSV (Feature #7)

Exports all students into a CSV file:

output/exported_students.csv


Useful for Excel, Google Sheets, and data analysis.

📅 6. Login History (Feature #11)

Every login is recorded automatically with:

Username

Date

Time

Stored in:

data/login_history.txt

📂 Project Structure
SRMS/
│
├── include/
│   ├── students.h
│   ├── auth.h
│   ├── utils.h
│
├── src/
│   ├── main.c
│   ├── students.c
│   ├── auth.c
│   ├── utils.c
│
├── data/
│   ├── credentials.txt
│   ├── students.txt
│   ├── login_history.txt
│
├── output/
│   ├── exported_students.csv
│
├── Makefile
└── README.md

🛠 Compilation & Execution
🔧 Using Makefile
make


This creates:

./srms.exe

▶ Run the program
./srms.exe

📝 Default Credentials
Username	Password	Role
admin	admin123	admin
staff	staff123	staff
user	user123	user
📌 Sample Student Data (students.txt)
1 Ravi 85.00
2 Raju 75.00
3 John 66.00
4 Dev 78.00
5 Hari 90.00

🧱 Technologies Used

C Programming

File Handling

Modular Programming

Makefile

CSV Exporting

Timestamps (ctime)

🎯 Learning Outcomes

By studying this project, you’ll learn:

✔ How to build modular C applications
✔ File handling & persistence
✔ Authentication system
✔ Searching & sorting algorithms
✔ CSV export formatting
✔ GitHub project structuring

🤝 Contributing

Feel free to fork this repo, create a branch and submit a pull request.

📜 License

This project is open-source under the MIT License.