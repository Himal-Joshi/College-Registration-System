# College-Registration-System
## Overview

The College Registration System is a C++ application designed to manage student and module records. It provides functionality to add, update, and display records, catering to both undergraduate and postgraduate students. The system tracks student modules and marks, calculates grades, and uses text files for data storage.

## Features

1. **Add Student Record**
   - Input student number, name, and type (undergraduate or postgraduate).
   - Record modules and optional marks.
   - Undergraduate: 6 modules, Postgraduate: 4 modules.

2. **Update Student Record**
   - Search and update existing student records by student number.

3. **Display Student Record**
   - Retrieve and display a specific student's record by their student number.

4. **Display All Student Records**
   - List all student records stored in the database.

5. **Add Module**
   - Add a new module with number, title, and level (undergraduate or graduate).

6. **Display Module Information**
   - Retrieve and display details of a specific module by its module number.

7. **Display All Modules**
   - List all modules stored in the database.

8. **Update Module Information**
   - Search and update existing module information by module number.

9. **Find Student Marks**
   - Calculate and display a student's average marks.
   - Assign grades based on the average marks.

## Files

- `stdtRecord.txt`: Stores student records.
- `modRecord.txt`: Stores module records.
- `tempFile.txt`: Temporary file used during updates.

## Implementation

- **Classes**:
  - `Std`: Manages student records.
  - `Module`: Manages module records.

- **Main Function**: 
  - Provides a menu-based interface for user interaction.

## Usage

1. **Compile the Code**:
   ```sh
   g++ -o CollegeRegistrationSystem main.cpp

2. **Run the executable**:
   ./CollegeRegistrationSystem

3. **Follow The Menu**
   Use the on-screen menu to interact with the system.

4. ## Menu Options
	Add Record
	Update Record
	Get any record
	Get all records
	Add Module
	Get Any Module details
	Get All Modules details
	Update Module
	Find Student Marks
	Exit


## License
This project is licensed under the MIT License.
