# Vehicle-Service-History-Management
A simple Python-based Vehicle Service History Management System that lets users store, update, and view service records easily. It organizes vehicle details, maintains repair logs, and generates clean summaries for better tracking and maintenance management.
#Features
1. Add Vehicle Service Records
Users can enter important service details like date, type of service, parts replaced, cost, and comments. This helps maintain a clean and organized history.
2. View Complete Service History
The system displays all previous service entries in an easy-to-read format, so users can quickly understand what work has been done on their vehicle.
3. Search Vehicle by Number
Users can search for a particular vehicle using the vehicle number and view all related service entries instantly.
4. Update Existing Records
If any service detail was entered incorrectly or needs changes later, the system allows updating the information easily.
5. Delete a Service Entry
Users can remove unwanted or duplicate service records to keep the history clean and accurate.
6. Simple Text-Based Console Interface
The project uses a beginner-friendly console menu that is easy to navigate and understand.
7. Data Storage Using Files
All service data is safely stored in a file so that information is not lost even after closing the program.
8. Error Handling
The system handles common errors like wrong inputs, missing records, or invalid search entries.
9. Organized and Modular Code
The program is divided into functions (modules) such as add_record(), view_records(), search_vehicle(), etc., to keep the code clean.
10. Future-Ready Structure
#Technologies/tools used
The project is built in a way that new features can be added later, like notifications or a GUI interface.
1. Python 3
The core programming language used to build the entire project.
Python handles:
User input
Processing service records
File reading and writing
Menu-driven interactions
2. CSV (Comma-Separated Values) File Format
Used for storing all vehicle service records.
CSV was chosen because:
It is simple to use
Easy to open with Excel or Notepad
Beginner-friendly for data storage
3. Python Built-in Modules
✔ csv
Used to read and write service records in a structured way.
✔ os
Used to check if the CSV file exists before loading data.
4. Text-Based Console Interface
A simple and clean command-line interface (CLI) is used for interaction.
This avoids complexity and makes the system easy for beginners.
5. File Handling
Python’s file I/O is used to:
Save records
Load records
Keep all data persistent
6. Modular Programming
The system is organized into multiple functions such as:
add_record()
view_all_records()
search_record()
save_to_file()
This makes the code easier to understand and maintain.
7. Git (Optional but Recommended)
Git can be used for:
Version control
Tracking changes
Backing up project code
Collaborating with others
#steps to install and run the project
1. Install Python
Make sure Python 3 is installed on your computer.
You can download it from the official Python website.
To check Python installation:
python --version
or
python3 --version
2. Download or Clone the Project
You can either:
Option A: Download ZIP
Download the project folder from the repository
Extract the ZIP file on your computer
Option B: Clone Using Git
If you are using Git:
git clone <your-repository-link>
3. Navigate to the Project Folder
Open your terminal or command prompt and move to the project directory.
Example:
cd vehicle-service-history-management
4. Check for the Main Python File
Make sure the file exists:
vehicle_service_history.py
5. Run the Program
Use the following command:
python vehicle_service_history.py
or for some systems:
python3 vehicle_service_history.py
6. Start Using the System
Once the program runs, you will see a menu like:
=== Vehicle Service History Management ===
1. Add Service Record
2. View All Records
3. Search Record
4. Exit
You can now interact with the system and perform all operations.
7. CSV File Auto-Creation
The file vehicle_service_history.csv will be created automatically after you add your first record.
#instructions for testing
1. Test Program Startup
Run the Python file.
Check if the main menu appears correctly.
Make sure no errors appear when starting the program.
2. Test Adding a Service Record
Choose option 1 from the menu.
Enter sample data:
Vehicle Number
Service Date
Service Type
Service Cost
Remarks
After entering values, check if:
A success message appears
The CSV file gets updated with the new entry
3. Test Viewing All Records
Choose option 2.
The program should display:
Every record stored in the CSV
All fields (vehicle number, date, type, cost, remarks)
Check if the formatting is readable and no errors appear.
4. Test Searching Records
Choose option 3.
Enter an existing vehicle number.
Verify:
The correct records appear
No unrelated records are shown
Now search for a number that does not exist.
Verify:
The program shows “No matching record found.”
5. Test CSV File Handling
Check if vehicle_service_history.csv is created automatically after adding a record.
Open the file manually and confirm:
All data is stored correctly
All columns are present
6. Test Invalid Inputs
Try typing:
Empty values
Wrong menu options
Numbers instead of text
Special symbols
The program should:
Not crash
Show a friendly error or re-prompt the user
7. Test Exit Option
Choose option 4.
The program should exit cleanly without errors.
