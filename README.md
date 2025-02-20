# Timetable Management System

## Introduction
The **Timetable Management System** is a Python project designed to manage and organize class schedules. This project demonstrates a variety of Python concepts including Data Structure, functions, Object-Oriented Programming (OOP), and the use of external libraries such as Pandas and NumPy.

## Features
* **User Authentication:** Secure login system validating user section and role.
* **Timetable Generation:** Automatically generates and manages timetables.
* **Class Management:** Assign and remove classes from the timetable.
* **User Roles:** Different access levels for Teachers, Teaching Assistants, and Students.
* **Data Manipulation:** Utilizes Pandas and NumPy for efficient data handling.
* **Iterative Display:** Displays timetable iteratively and converts it to a pandas DataFrame.

## Concepts Covered
The project covers the following Python concepts:

1. **Lists:** Used to store days and time slots.
2. **Tuples:** Used in timetable schedules.
3. **Sets:** Used to manage unique class codes and titles.
4. **Dictionaries:** Used extensively for timetable management.
5. **If-Else Statements:** Used for conditional logic.
6. **Loops:** Used for iterating over collections.
7. **Map Functions:** Used for mapping timetable slots to statuses.
8. **Lambda Functions:** Used for concise functions in `TimetableLambda`.
9. **Inheritance:** Demonstrates single, multiple, and multilevel inheritance.
10. **Iterators:** Implements an iterator for the timetable.
11. **Polymorphism:** Demonstrates through method overriding.
12. **Abstraction:** Uses abstract base classes and methods.
13. **Encapsulation:** Encapsulates attributes and methods within classes.
14. **Date Handling:** Utilizes the `datetime` module.
15. **Exception Handling:** Uses try-except blocks.
16. **Pandas Module:** Converts timetable data to a DataFrame.
17. **NumPy Module:** Used for data manipulation.

## Installation
To run this project, you'll need to have Python installed on your system along with the following libraries:
1. `numpy`
2. `pandas`
3. `tabulate`
4. `datetime`

You can install the required libraries using pip:
```
pip install numpy
pip install pandas
pip install tabulate
pip install datetime
```
## Usage
Clone the reporsitory:
```
git clone https://github.com/kamrujjamant66/Timetable-Management-System.git
```
Navigate to the repository:
```
cd Timetable-Management-System
```
Follow these prompts to log in, manage classes, and view the timetable.

### `TimetableGenerator`
`generate_timetable()`: Initializes the timetable with "Free" slots.
`timeTable_for_63_M()`: Sets a predefined schedule for section 63_M.
`display_day_routine(day)`: Displays the routine for a specific day.
`print_timetable()`: Prints the full timetable.
`display_timetable()`: Displays the timetable in a formatted table.
`convert_to_dataframe()`: Converts the timetable to a pandas DataFrame.

### `ClassSchedule`
`set_class(timetable, day, time_slot, course_code, course_title, teacher_name)`: Assigns a class to the timetable.

### `OnlineClass` (Inherits from `ClassSchedule`)
`get_class_info()`: Gets information about the class.

### `DateHelper`
`get_current_date()`: Returns the current date.
`ClassInfo` (inherits from `TimetableGenerator`, `Day`, `DateHelper`)
`display_info()`: Displays the timetable based on user choice.

### `TimetableIterator`
`__iter__()`: Returns the iterator object.
`__next__()`: Returns the next item from the timetable.

### `TimetableAnalysis`
`count_free_slots()`: Counts free slots in the timetable.
`free_slots_withNumpy()`: Uses NumPy to count free slots.

### `TimetableLambda`
`is_slot_available(day, slot)`: Checks if a slot is available using a lambda function.

### `ClassCodes`
`add_class(code, title)`: Adds a class code and title.
`get_all_classes()`: Returns all class codes and titles.
`update_class_codes(timetable)`: Updates class codes based on the timetable.

### `LoginSystem`
`validate_section(section)`: Validates the section format.
`ask_for_section()`: Prompts the user to enter their section.
`ask_for_role()`: Prompts the user to enter their role.

## Contributing
Feel free to contribute to this project by opening issues or submitting pull requests. Please ensure your contributions align with the project's overall goals and coding standards.

## Contact
For any inquiries or feedback, you can reach out to me at kamrujjamant.kt66@gmail.com.