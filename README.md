# Journal
# Corner Grocer Item Tracker

## Project Summary
The Corner Grocer Item Tracker is a C++ program designed to help a small grocery store keep track of the frequency of items sold. It reads item names from an input file, stores their occurrences in a map, and provides multiple functionalities, including searching for an item's frequency, displaying all items with their frequencies, and generating a histogram representation. Additionally, it saves a backup file to persist item frequency data.

## Strengths in Development
One of the aspects I did particularly well in this project was implementing a structured and organized approach using object-oriented programming. The class `ItemTracker` effectively encapsulates data and methods related to item tracking, making the code modular and easy to maintain. Additionally, the use of the C++ Standard Library (`map`, `ifstream`, `ofstream`, and `string`) ensured efficiency and readability.

## Areas for Improvement
While the program functions correctly, there are several areas for enhancement:
- **Error Handling:** More detailed error messages can be added for file operations to make debugging easier.
- **Input Validation:** When taking user input, validation should be improved to handle invalid or unexpected inputs more gracefully.
- **Case Insensitivity:** Converting item names to lowercase before storing or searching them would improve accuracy in item lookups.
- **Efficiency:** If the dataset were large, using a more optimized data structure (such as unordered_map for faster lookups) could improve performance.

## Challenges and Overcoming Them
One of the most challenging aspects of the project was handling file operations correctly. Ensuring the input file was read properly and writing a backup file required careful management of file streams. To overcome this, I used detailed debugging techniques such as printing output at different points and verifying file contents.

Another challenge was ensuring that the menu-driven interface functioned smoothly without unexpected crashes. I addressed this by implementing a loop that validates user input and clears any errors in the input stream before proceeding.

To support my work, I relied on resources such as the C++ documentation, Stack Overflow, and discussions with peers.

## Transferable Skills
This project strengthened my abilities in:
- Object-oriented programming principles (encapsulation, modular design)
- File handling and data persistence
- Using STL containers (`map`) for data storage and retrieval
- Writing readable and maintainable code
- Implementing a command-line user interface
These skills will be beneficial in future coursework and real-world programming tasks that involve handling and processing large amounts of structured data.

## Code Maintainability and Readability
To ensure that the program is maintainable, readable, and adaptable, I:
- Used meaningful variable and function names
- Followed consistent indentation and formatting
- Documented key parts of the code with comments
- Encapsulated functionality within a class to allow for easy modifications and extensions

By adhering to these principles, the program remains easy to understand and modify, making future updates and improvements seamless.

