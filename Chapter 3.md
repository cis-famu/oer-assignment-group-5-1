Introduction C++ Programming

OER Group-5 Chapter #3

After completing this chapter students will be able to:
Identify and use control structures
Identify logical and relational operators, how they work, and order of precedence
Distinguish the relationship of relational operators and simple data types
Identify how to form and evaluate logical (Boolean) expressions
Use one-way and/or two-way selection syntax
Demonstrate a switch statement in a program

Introduction: 
Upon completion of this unit, students will be able to:

Identify input and output streams
Read data from the standard input device
Define the use predefined functions in a program
Describe input stream functions get, ignore, putback, and peek
Write data to the standard output device
Use manipulators in a program to format output
Perform input and output operations using the string data type
Distinguish how to use debug logic errors

A section per topic:

3.1 I/O Streams and Standard I/O Devices

3.2 Using Predefined Functions in a Program

3.3 Input Failure

3.4 Output and Formatting Output

3.5 Additional Output Formatting Tools
When working with C++ and formatting output, the setfill manipulator becomes essential. It lets you choose the character you want to use to fill up extra space in your output. When you combine it with setw, which sets the width of your output fields, and other manipulators like left and right for aligning text, you gain much control over how your output looks. By including the <iomanip> header and using cout << setfill(character) along with setw, left, or right, you can customize your output to look just the way you want it. This means you can create polished output that fits your needs perfectly, giving your C++ programs a more professional and flexible appearance.

3.6 Input/Output and the string type 
You can use input stream variables like cin and the extraction operator >> to read strings into string variables. However, this method has limitations, as it stops at whitespace characters, making it unsuitable for strings containing spaces. To handle such cases, you can employ the getline function, which reads until the end of the current line, effectively capturing strings with spaces. For outputting string variables, you can utilize an output stream variable such as cout paired with the insertion operator <<, enabling you to display the string variable’s contents on the output stream. You can effectively manage string inputs and outputs in your programs using these techniques.
![image](https://github.com/cis-famu/oer-assignment-group-5-1/assets/156258733/1a7877ea-71c5-45ae-a5f6-536a7b6a0b78)
3.7 Debugging: Understanding Logic Errors and Debugging with cout Statements

3.8 File Input/Output 

Review Questions:


Summary:
* A stream in C++ is an infinite sequence of characters from a source to a destination.

* An input stream is a stream from a source to a computer.

* An output stream is a stream from a computer to a destination.

* When inputting data into a variable, the operator >> skips all leading whitespace characters.

* When inputting data into a variable, the operator >> skips all leading whitespace characters.

Key Terms:

Ignore: used to kip data in a line 

cin (common input): used to initialize the standard output device 

Output stream: a stream from the computer to a destination. 

References:

Editor: Wren King, Cameron Smith, Xavier Blake, Channing Wyatt
