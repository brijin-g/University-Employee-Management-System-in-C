🧾 Employee Management System – C with GTK
A simple GUI-based application developed in C using the GTK toolkit that allows you to manage employee records with ease. It supports adding new employees and saves their data into a CSV file.

📌 Features
Graphical User Interface (GUI) for easy interaction

Input fields for ID, Name, Age, and Salary

Adds employee details to a list and saves them in a CSV file (emp.csv)

Validation for empty input fields

Alerts for successful addition or errors

Limited to a maximum of 10 employees

🧰 Technologies Used
Language: C

Library: GTK 3 (GIMP Toolkit)

File Format: CSV (Comma-Separated Values)

▶️ How to Run
1. Install GTK+
For Ubuntu/Debian:
bash
Copy
Edit
sudo apt update
sudo apt install libgtk-3-dev
2. Compile the Code
bash
Copy
Edit
gcc employee_manager.c -o employee_manager `pkg-config --cflags --libs gtk+-3.0`
(Assuming your file is saved as employee_manager.c)

3. Run the Application
bash
Copy
Edit
./employee_manager
📂 Output File
emp.csv will be created (if not present) in the same directory.

It contains: ID, Name, Age, Salary

🧠 How It Works
Users enter employee details into the GUI.

When “Add Employee” is clicked:

Input is validated

Data is stored in memory and appended to emp.csv

Success or error dialog appears

The app supports up to 10 employees per session.

📄 File Structure
employee_manager.c – Main C source code

emp.csv – Output file with saved employee data
