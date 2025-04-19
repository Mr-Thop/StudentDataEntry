// README.md
# Student Data Entry System (Java)

## Description
This Java application manages student records with the help of OOP concepts. It supports adding, displaying, searching, updating, and deleting students.

## Files & Classes
- `Main.java`: Main driver with menu
- `Student.java`: Student class with fields like PRN, name, DOB, and marks
- `Operations.java`: All operations as static methods
- `CustomException.java`: Base class for all custom exceptions
- `StudentNotFoundException.java`, `DuplicateStudentException.java`, etc.: Specific exceptions

## Functionalities
1. **Add Student** - Prevents duplicate PRNs
2. **Display Students** - Shows all students
3. **Search Student**
   - By PRN
   - By Name
   - By Position
4. **Update Student** - Update name, DOB, and marks
5. **Delete Student** - Delete by PRN

## Exception Handling
Each function uses custom exceptions for robust control flow.
