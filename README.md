# Student Data Entry System (Java)

This project is a **Java-based student data entry system** designed to handle basic operations while demonstrating custom exception handling. It's clean, modular, and built with learning in mind!

## Features

- Adds student data (with uniqueness check)
- Handles duplicates with a custom `DuplicateStudentException`
- Searches for student data (with not-found handling)
- Handles missing students with a `StudentNotFoundException`
- Outputs appropriate error messages for better UX

## Tech Stack

- Java (OOP, custom exceptions, user input)
- Exception handling (custom + built-in)
- Console-based interface

## Custom Exceptions

- `DuplicateStudentException` – Thrown when a student with the same ID is already added.
- `StudentNotFoundException` – Thrown when trying to access a student who doesn’t exist in the records.

## Sample Output

```text
Duplicate Student Exception
Student not found Exception
