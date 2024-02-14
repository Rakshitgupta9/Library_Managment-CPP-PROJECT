# Library-management-with-c++

This is a C++ program for a simple Library Management Software. The program allows users to perform various operations such as entering book details, searching for book details, managing the library inventory, issuing and returning books, and accessing an administrator menu.

## Features

- **Book Details Entry:** Users can enter details for new books, including book ID, name, and author. The information is stored in a file named "lib_book_details.dat".

- **Search Book Details:** Users can search for books using different criteria. They can display all books or search for a specific book by name. The search results are displayed on the console.

- **Administrator Menu:** Administrators can access a password-protected menu to perform additional operations. This includes deleting book data and resetting the program to defaults.

- **Issue and Return Section:** Users can issue books to individuals by providing the serial number and user details. The program also allows returning books either by serial number or by the full book name. Issued and returned book details are stored in "lib_issue_return.dat".

- **Password Protection:** The program has a password system to ensure secure access to certain functionalities.

- **About Section:** Provides information about the project and the developer.

## How to Use

1. **Run the Program:** Execute the program and enter the password to access the main menu.

2. **Main Menu Options:**
   - Option 1: Enter new book details.
   - Option 2: Search for book details.
   - Option 3: Access the administrator menu.
   - Option 4: Use the issue and return section.
   - Option 5: Learn more about the project and the developer.
   - Option 6: Exit the program.

3. **Administrator Menu:**
   - Option 1: Delete book data.
   - Option 2: Reset the program to defaults.
   - Option 3: Exit the program.

4. **Issue and Return Section:**
   - Option 1: Issue a book by providing serial number and user details.
   - Option 2: Return a book by serial number or full book name.
   - Option 3: View the status of issued and returned books.
   - Option 4: Exit the program.

5. **About Section:** Provides information about the project and the developer.

## Important Notes

- The program includes password protection. The default password is "project."

- Administrators can access the administrator menu using the password "admin."

- The program stores data in various files, including "lib_book_details.dat," "lib_issue_return.dat," and temporary files for processing.

- Use the program responsibly and follow the prompts to ensure accurate data entry and retrieval.

## Developer

- **Name:** Rakshit Gupta
- **Email:** 2021a1r050@mietjammu.in

Feel free to explore the code and contribute to its improvement. If you encounter any issues or have suggestions, please create an issue on GitHub.
