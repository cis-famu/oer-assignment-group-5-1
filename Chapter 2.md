Introduction C++ Programming

OER Group-5 Chapter #2

Objective: After completing this chapter students will be able to:
Identify input and output streams
Read data from the standard input device
Describe input stream functions get, ignore, putback, and peek
Write data to the standard output device
Use manipulators in a program to format output
Perform input and output operations using the string data type
Read data from a file (include examples)
Write data to a file (include examples)


Introduction: 

A section per topic:

2.1 A Quick Look at a C++ Program

2.2 The Basics of a C++ Program

2.3 Data Types

2.4 Data Types, Variables, and Assignment Statements

2.5 Arithmetic Operators, Operator Precedence, and Expressions
Standard arithmetic operators allow us to manipulate integral and floating number data types, allowing the computer to calculate. The operators +, -, *, / can be used with both integral and floating number data types. Operands are numbers used to evaluate an operator. Unary operators have one operand while binary operators have two operands. When there are multiple arithmetic operators in an expression, C++ uses precedence rules to evaluate the expression. The operators * and / have a higher precedence than + and -. The three types of arithmetic expressions are integral expressions, floating-point expressions, and mixed expressions.  
2.6 Type Conversion (Casting)
Implicit type coercion occurs when a value of one data type is automatically changed to another data type. Cast operators are used to avoid implicit type coercion. The expression is evaluated, then its value is converted to the value type specified by dataTypeName. To convert a floating-point number to an integer, you must drop the decimal part of the floating number. Cast operators are also used to convert char data values into int data values and int data values into char data values. 

2.7 string Type
String is a program-defined data type not directly available for use in a program like simpler data types. In order to use this data type, you must access program components from the library. A string is also defined as a sequence of zero or more characters and is enclosed in double quotation marks. A null/empthy string is a string containing no characters. Each character in a string has a relative position with the first character being 0. 
2.8 Variables, Assignment Statements, and Input Statements

When you instruct the computer to allocate memory, you tell it not only what names to use for each memory location, but also what type of data to store in those memory locations. 
Some data must stay the same throughout a program. For example, the conversion formula that converts inches into centimeters is fixed, because 1 inch is always equal to 2.54 centimeters. When stored in memory, this type of data needs to be protected from accidental changes during program execution.
When a variable is declared, C++ may not automatically put a meaningful value in it. In other words, C++ may not automatically initialize variables. For example, the int and double variables may not be initialized to 0, as happens in some programming languages. 

<img width="210" alt="Screenshot 2024-02-02 at 7 13 13 PM" src="https://github.com/cis-famu/oer-assignment-group-5-1/assets/98242052/c05c7266-2029-4e92-9b9a-8276bf82773e">

2.9 Increment and Decrement Operators

 In C++, we have these little tools called increment (++) and decrement (--) operators. They are great for quickly adding or subtracting one from a variable. These operators have two versions: pre-increment/post-increment and pre-decrement/post-decrement. The pre-increment (++variable) bumps up the variable before using its value in an expression, while the post-increment (variable++) uses the current value and then increments it afterward. Similar rules apply to pre-decrement (--variable) and post-decrement (variable--). The critical thing to grasp is when the variable gets modified about its expression. These operators are handy for tasks like counting or tweaking variable values in C++ programs.
 ![image](https://github.com/cis-famu/oer-assignment-group-5-1/assets/156258733/e1b934ce-38f9-4a83-8039-0b3a5331ae30)

2.10 Output

In C++ programming, output facilitation is realized through cout and the stream insertion operator (<<). cout is the conduit for displaying content on the standard output device, typically the screen. Employing << allows for incorporating values and manipulators in output statements, shaping the presentation format.
Manipulators, exemplified by endl for line breaks, contribute to the structured formatting of outputs. In the output, C++ accommodates a diverse range of entities, spanning numerical values, strings, and the outcomes of expressions. The judicious use of newline characters (\n) and escape sequences, such as \t for tabulation, empowers developers to exercise precision over the spatial arrangement of output elements.
In essence, mastery of cout, <<, and associated manipulators provides a nuanced command over the communicative aspect of C++ programming, enabling meticulous control over the visual representation of program outputs. Real-world examples elucidate the practical application of these principles within the coding domain.

![image](https://github.com/cis-famu/oer-assignment-group-5-1/assets/156258733/1a2558ea-fe87-479c-a46b-39b773ab1dc9)
2.11 Preprocessor Directives

In C++ development, achieving organized and readable code is crucial, made possible by leveraging preprocessor directives and header files. Since C++ has limited explicitly defined operations, libraries containing essential functionalities use headers. Preprocessor directives, signaled by #, guide a preprocessor program in modifying code before compilation. For instance, the directive #include <iostream> connects the iostream header, introducing vital components like cin and cout for input/output tasks. These directives are strategically placed at the start of a program, ensuring that identifiers are available throughout the code. Additionally, developers can create their header files to facilitate modular code design.
Understanding the role of the std namespace is crucial, mainly when working with identifiers such as cin and cout. Initially declared within this namespace, these identifiers can be accessed by explicitly referencing them as std::cin and std::cout or using the namespace std; statement after including the corresponding header file. This declaration eliminates the need for the std:: prefix in subsequent references, contributing to improved code readability. Embracing preprocessor directives and leveraging namespaces optimizes code structure and enhances accessibility to essential features.
![image](https://github.com/cis-famu/oer-assignment-group-5-1/assets/156258733/0fc0ed79-838a-4add-9fc9-d556824d93e6)


2.12 Creating a C++ Program

A C++ program is a collection of functions, one of which is the function main. Therefore, if a C++ program consists of only one function, then it must be the function main. 
You can divide a C++ program into two parts: preprocessor directives and the program. The basic parts of the function main are the heading and the body. The first line of the function main, that is int main()

<img width="220" alt="Screenshot 2024-02-02 at 7 22 07 PM" src="https://github.com/cis-famu/oer-assignment-group-5-1/assets/98242052/6be19fa4-1fca-46ed-b7c0-ee458318f7fc">


2.13 Debugging: Understanding and Fixing Syntax Errors

When you type a program, typos and unintentional syntax errors are likely to occur. Therefore, when you compile a program, the compiler will identify the syntax error. In this section, we show how to identify and fix syntax errors. It is best to try to correct the errors in top-down fashion because the first error may confuse the compiler and cause it to flag multiple subsequent errors when actually there was only one error on an earlier line. So, let’s first consider the following error:

![image](https://github.com/cis-famu/oer-assignment-group-5-1/assets/98242052/7b54eedd-e215-4019-b349-283fa24c5613)

2.14 Program Style and Form

In C++, you use one or more blanks to separate numbers when data is input. Blanks are also used to separate reserved words and identifiers from each other and from other symbols. Blanks must never appear within a reserved word or identifier. It is very common for the omission of a single character to cause four or five error messages. However, when the first syntax error is removed and the program is recompiled, subsequent syntax errors caused by this syntax error may disappear.

<img width="392" alt="Screenshot 2024-02-02 at 7 45 51 PM" src="https://github.com/cis-famu/oer-assignment-group-5-1/assets/98242052/8789dd05-8f4a-4d66-880b-18e6a2a017b6">

Review Questions:
What function does every C++ program have? ans main

WHat does the compiler ignore: ans commas

Which version of the decrement operator decreases the variable after using its value in an expression? Post-decrement 

What does the pre-increment operator (++variable) do in C++? Increments the variable before using its value in an expression

What is the purpose of the stream insertion operator (<<) in C++? Facilitates output with court

Which manipulator is commonly used for introducing line breaks in C++ output statements?endl

In C++, what is the role of using namespace std; in relation to cout and cin?It eliminates the need for the std:: prefix in subsequent references

How do preprocessor directives enhance code organization in C++ development?They modify code before compilation

What is the purpose of the #include directive in C++?t connects header files, introducing essential functionalities

Where is it recommended to place preprocessor directives for optimal usage in a C++ program?At the start of the program

Summary:
* Reserved words cannot be used as identifiers in a program.

* All reserved words in C++ consist of lowercase letters (see Appendix A).

* In C++, identifiers are names of things.

* A C++ identifier consists of letters, digits, and underscores and must begin with a letter or underscore.

* Whitespaces include blanks, tabs, and newline characters.

* A data type is a set of values together with a set of allowed operations.

* C++ data types fall into the following three categories: simple, structured, and pointers.

* There are three categories of simple data: integral, floating point, and enumeration.

Key Terms:

Data type double, float, long double: used to manuoulate decimal numbers

Mixed expression: an expression that consist of both integers and decimal numbers

" \ ": escape character


References:

Chapter 2 Section 12 . (n.d.). https://ng.cengage.com/static/nb/ui/evo/index.html?snapshotId=3814784&id=1997462638&deploymentId=5999972473086198315902738132&eISBN=9780357425220 Accessed 2-2-2024

Editor: Wren King, Cameron Smith, Xavier Blake, Channing Wyatt
