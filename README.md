# FILE-MANAGEMENT-TOOL

COMPANY : CODTECH IT SOLUTION

NAME : PRASHANT KUMAR SINGH

INTERN ID : CT04DF551

DOMAIN :  C++ PROGRAMMING

DURATION : 4 WEEKS

MENTOR : NEELA SANTHOSH

Task Overview:

This project has been developed as part of CodTech Internship Task-1. The goal of this task is to build a simple file management tool using the C++ programming language. The primary focus is to implement core file handling operations such as reading from a file, writing to a file, and appending data to a file. These are fundamental skills for any C++ developer and are often used in real-world applications like logging, configuration management, data persistence, and more.

In this task, the user interacts with a console-based application that presents a menu-driven system. The user can select whether they want to write data to a file (which replaces existing content), append data (which adds to the existing content), or read the current content of the file. The program uses standard C++ file handling classes like ifstream, ofstream, and fstream to achieve these functionalities.

Objectives of the Task:

The main objectives of this internship task are:

To understand and apply basic file handling concepts in C++.

To create an interactive C++ console application capable of managing file data.

To demonstrate the ability to work with input/output streams.

To enhance understanding of how data can be stored and retrieved from files in real time.

To build a working program that mimics real-world use cases such as text editors or log processors.

Features of the Application:

Write to File:
This option allows the user to write new content to the file. If the file already has data, it will be overwritten. This uses ofstream in write mode.

Append to File:
In this mode, the user can add new content to the end of the file without deleting existing data. This uses ofstream with ios::app mode.

Read from File:
This feature reads and displays the entire content of the file line by line using ifstream.

Exit:
Ends the program safely.

Technologies Used:

Language: C++

Compiler: g++ (GNU Compiler)

Platform: VS Code (Visual Studio Code)

Libraries: iostream, fstream, string

How to Run the Program:

Save the code file as file_manager.cpp.

Open a terminal in the same folder.

Compile the program with the command: g++ file_manager.cpp -o file_manager

Run the compiled program with: ./file_manager

Follow the on-screen menu to perform file operations.

Sample Output:

File Management Menu:

Write to file

Append to file

Read from file

Exit
Enter your choice: 1
Enter data to write to the file: Hello, this is CodTech Task-1.
Data written successfully.

Learning Outcome:

This project provided a practical and hands-on learning experience in C++. It improved my understanding of how data is stored and processed using files. I learned how to create, open, modify, and close files using file streams. It also helped me understand the importance of data flow between storage devices and application logic. Such knowledge is crucial in building larger applications such as databases, configuration handlers, or file processors.

I now feel more confident in working with C++ file operations and in applying this knowledge to future projects that require data persistence. This task was an essential step in my journey of mastering C++ programming and backend logic.

Task Status:

This internship task has been successfully completed. The code was tested for correctness and submitted as per CodTech's guidelines. The GitHub repository includes all relevant files, including source code and documentation.
