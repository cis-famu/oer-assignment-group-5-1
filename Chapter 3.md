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
In C++, I/O is a sequence of bytes, called a stream, from the source to the destination.
Recall that the standard input device is usually the keyboard, and the standard output device is usually the screen. To receive data from the keyboard and send output to the screen, every C++ program must use the header file iostream. This header file contains, among other things, the definitions of two data types, istream (input stream) and ostream (output stream). 
#include <iostream>

ifstream cin;
ofstream cout;
3-1a. cin and the Extraction Operator>>
![image](https://github.com/cis-famu/oer-assignment-group-5-1/assets/156130748/7f3ac1af-2e3f-41c2-a6ac-e4e238b1f5c8)

3.2 Using Predefined Functions in a Program

3.3 Input Failure

3.4 Output and Formatting Output

3.5 Additional Output Formatting Tools
When working with C++ and formatting output, the setfill manipulator becomes essential. It lets you choose the character you want to use to fill up extra space in your output. When you combine it with setw, which sets the width of your output fields, and other manipulators like left and right for aligning text, you gain much control over how your output looks. By including the <iomanip> header and using cout << setfill(character) along with setw, left, or right, you can customize your output to look just the way you want it. This means you can create polished output that fits your needs perfectly, giving your C++ programs a more professional and flexible appearance.

3.6 Input/Output and the string type 
You can use input stream variables like cin and the extraction operator >> to read strings into string variables. However, this method has limitations, as it stops at whitespace characters, making it unsuitable for strings containing spaces. To handle such cases, you can employ the getline function, which reads until the end of the current line, effectively capturing strings with spaces. For outputting string variables, you can utilize an output stream variable such as cout paired with the insertion operator <<, enabling you to display the string variable’s contents on the output stream. You can effectively manage string inputs and outputs in your programs using these techniques.
![image](https://github.com/cis-famu/oer-assignment-group-5-1/assets/156258733/1a7877ea-71c5-45ae-a5f6-536a7b6a0b78)

3.7 Debugging: Understanding Logic Errors and Debugging with cout Statements
Syntax errors are reported by the compiler, and the compiler not only reports syntax errors, but also gives some explanation about the errors. On the other hand, logic errors are typically not caught by the compiler except for the trivial ones such as using a variable without properly initializing it.
![image](https://github.com/cis-famu/oer-assignment-group-5-1/assets/98242052/89b82278-dec0-4c4f-8721-6574dca4bd69)

3.8 File Input/Output 
If the amount of input data is large, however, it is inefficient to type it at the keyboard each time you run a program. In addition to the inconvenience of typing large amounts of data, typing can generate errors, and unintentional typos cause erroneous results. You must have some way to get data into the program from other sources. By using alternative sources of data, you can prepare the data before running a program, and the program can access the data each time it runs. This section discusses how to obtain data from other input devices, such as a flash drive (that is, secondary storage), and how to save the output to a flash drive.
![image](https://github.com/cis-famu/oer-assignment-group-5-1/assets/98242052/5325b244-2599-4ef5-ab0b-18fde5e7a4c1)

Review Questions:
* To use cin and cout, which prorgram must be included in the header?; Ans: iostream
* What does the function peek do?; Ans: it returns the character from the next input stream but does not remove the character from the input stream.
* Define what ignore does; Ans: it is used to skip data in a line 

Summary:
* A stream in C++ is an infinite sequence of characters from a source to a destination.

* An input stream is a stream from a source to a computer.

* An output stream is a stream from a computer to a destination.

* When inputting data into a variable, the operator >> skips all leading whitespace characters.

* When inputting data into a variable, the operator >> skips all leading whitespace characters.

Key Terms:
stream: a sequence of characters from the source to the destination
input stream: A sequence of characters from an input device to the computer.
output stream: A sequence of characters from the computer to an output device.
common input: the variable cin is named after this
common output: the variable cout is named after this
input stream variables: variables of the type istream
output stream variables:variables of the type ostream
stream variable: either an input stream variable or an output stream variable

Ignore: used to kip data in a line 

cin (common input): used to initialize the standard output device 

Output stream: a stream from the computer to a destination. 

Programming excercises: 
![image](https://github.com/cis-famu/oer-assignment-group-5-1/assets/98242052/86dd4684-f88f-4b73-9842-ba4139ff594d)

References:
Input/Output . (n.d.). https://ng.cengage.com/static/nb/ui/evo/index.html?deploymentId=5999972473086198315902738132&eISBN=9780357425220&snapshotId=3814784&id=1997462715& 

Input/Output . (n.d.). https://ng.cengage.com/static/nb/ui/evo/index.html?deploymentId=5999972473086198315902738132&eISBN=9780357425220&id=1997462715&snapshotId=3814784&

Editor: Wren King, Cameron Smith, Xavier Blake, Channing Wyatt
