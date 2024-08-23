# 22CFinalProject

# Antique Car Data Management System

## Description

This project manages antique car data using Binary Search Tree (BST) and Hash Table data structures. It handles file operations, user input, and functionalities such as adding, deleting, and searching for cars. Additional features include undoing deletions, displaying data structures, and saving to files. The project integrates various modules for comprehensive data management.

## Program Functionality

The system supports the following operations:

- Load antique car data from files
- Insert new car data
- Delete car entries and manage undo operations
- Search for cars by ID using a hash table
- Display data either in an indented binary tree format or via an in-order traversal
- Save car data to a file
- Display hash table statistics such as longest collision chain, total collisions, and load factor

## Menu Options

- `INS`: Insert data from a file
- `I`: Add a new car manually
- `D`: Delete a car from the system
- `F`: Search for a car by ID
- `DIS`: Display the current tree of cars
- `U`: Undo the last deletion
- `S`: Save the current state to a file
- `ST`: Show hash table statistics
- `T`: Display team member details (hidden option)
- `E`: Exit the program
- `H`: Display the help menu

## My Contribution

### Role: Team Leader

I, Ferit Kabil, was responsible for leading the project and coordinating my team. My contributions include:

- Designing the overall architecture of the data structures (BST and Hash Table)
- Implementing key features such as the main menu and related functions
- Creating the logic for inserting, deleting, and searching cars within the system
- Coordinating the weekly reports, setting deadlines, and ensuring that everyone contributed to the project
- Integrating all project components and thoroughly testing the final solution
- Writing and submitting the final reports, presentations, and poster for the project
- Providing feedback and assisting team members with their code challenges

### Key Code Contributions

- **loadCarsFromFile:** Managed the functionality for loading data from files into the binary search tree and hash table.
- **addNewCar:** Handled the addition of new car entries while preventing duplicates.
- **deleteCar:** Enabled car deletion with an option to undo the operation.
- **searchManager:** Facilitated searching for cars by ID in the hash table.
- **displayManager:** Displayed the tree structure of the cars in multiple formats.

## Usage Instructions

1. Compile and run the program.
2. Choose an option from the main menu to perform operations on the antique car data.
3. Make use of the undo feature for accidental deletions.
4. Save the current state to a file before exiting to preserve data.

##Data Files

- Input File: antique_cars.txt - contains car data in a structured format.
- Output File: output.txt - saves the current state of the car data.

## Note

- Input files should be formatted correctly for the program to parse them properly.
- The hash table size is set dynamically based on the number of entries.

## Conclusion

This project highlights the successful collaboration of the team in developing a sophisticated system that integrates various data structures and file management techniques. Through effective teamwork and coordination, each component was seamlessly integrated, meeting all project requirements.
