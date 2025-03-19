Project Overview
This is a console based application which is written in x86 assembly language. It
pretends to be a basic e-commerce site where end-users can browse a list of books, pick
a genre, select a book, and specify the number of copies they want to buy. Based on the
selected book and number of copies, the program computes the total price and gives a
rudimentary exposure to user interaction and data and interrupt handling in assembly
language.
Objectives
 Develop a friendly look of book browsing.
 To exploratory works for selecting books and total prices.
 For helping to understand assembly language programming, especially with how
to deal with user input and output.
 For procedural modular programming demonstration.
Key Features
 Welcome: Shows a greeting to the user.
 20 Book Categories: Users can explore categories like English Novels, Urdu
Novels, and Islamic Books.
 Book Selection: Each category includes all the available books and their prices.
Users can specify how many copies of the selected book they would like to
purchase.
 Total Price: The program also calculates and displays the total price based on
the selected book and quantity.
 Specifications: The basic specifications and output features are as follows:
Technical Details
 ASSEMBLER Program Source: The program is written in x86 assembly language.
 Data Structures: The program utilizes data segments to store strings used for
messages, book titles, and prices.
Code Structure
The program consists of several major sections:
 Data Segment: All the strings used for messages, book titles, and prices are
contained herein.
 Main Routine: The program entry point that initializes the data segment and
controls the flow of the program.
 Routines
 condition3: Controls the selection of English novels.
 condition: Controls the selection of Urdu novels.
 condition1: Controls the selection of Islamic books.
 Fifty, Hundred, Two Hundred: Calculate the total price according to the
selected book's price.
 Invalid: Shows an error message for invalid inputs.
 Exit: Terminate the program.
User Interaction Flow
 The program begins with a welcome message.
 The user is asked to enter 1 to view the book list or 2 to exit.
 If the user selects 1, they are presented with three book categories.
 Once a category is selected, the user can select a specific book and enter the
desired quantity.
 The program calculates the total price and displays it.The user is provided with
the choice of returning to the book list or exiting the program.
Problems Encountered
 Input Validation: Validating user inputs and handling errors in a graceful
manner was a challenge, especially in a low-level language where error handling
is not very intuitive.
 Data Management: The management of book titles and prices in an efficient
manner required careful structuring of data segments and procedures.
Future Enhancements
 Database Integration: A database should be implemented that can store the book
information dynamically.
 Graphical User Interface is changed from a console application for better user
experience.
 Payment Processing function has been added to simulate a full-scale e-commerce
experience
 User Accounts: This component allows customer accounts management that
enhances experience
Conclusion
The Online Book Shop program is an excellent learning tool in understanding assembly
language programming and basic user interaction concepts in software applications. It
teaches how to manage user input, calculate values, and control the flow of the program
using procedures. This project not only reiterates concepts of programming but also
gives one practical experience at developing a simple console application.
