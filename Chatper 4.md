Chapter 4 OER
Introduction C++ Programming

OER Group-5 Chapter #4

After completing this chapter students will be able to:
1. Use control structures
2. Use selection syntax
3. Identifying bugs and how to avoid them
4. Use Boolean expressions effectively.
   
Introduction: 
In this Chapter, we read how to tell a computer it is incorrect regarding its sequential order; along with making decisions until specified conditions are met. 


A section per topic:
 
4.1 Control Structures: 
Control structures provide alternatives to sequential program execution and are used to alter the sequential flow of execution. The two most common control structures are selection and repetition. In selection, the program executes particular statements depending on some condition(s). In repetition, the program repeats particular statements a certain number of times based on some condition(s).

4.1a) Selection if and if-else, expressions using these operators always evaluate to true or false.

Relational Operations 
![image](https://github.com/cis-famu/oer-assignment-group-5-1/assets/156130748/f8274f5d-0215-4565-a593-b6f7047ecedb)

4.1b) Relational Operators and Simple Data Type 


![image](https://github.com/cis-famu/oer-assignment-group-5-1/assets/156130748/f1fa77f9-c992-40ec-b08c-537c5fb92095)

4.1c) Comparing Characters

For char values, whether an expression using relational operators evaluates to true or false depends on a machine’s collating sequence. 

Now that we know how relational operators work, we can start learning how to implement decisions in a C++ program. Although there are only two logical values, true and false, they turn out to be extremely useful because they permit programs to incorporate decision making that alters the processing flow. The remainder of this chapter discusses ways to incorporate decisions into a program. In C++, there are two selections, or branch control structures: if statements and the switch structure. This section discusses how if and if. . .else statements can be used to create one-way selection, two-way selection, and multiple selections. The switch structure is discussed later in this chapter.

4.1d) One Way Selection

In C++, one-way selections are incorporated using the if statement. The syntax of one-way selection is:


![image](https://github.com/cis-famu/oer-assignment-group-5-1/assets/156130748/223d9b50-938b-4f6e-91aa-e827ac9ee3b7)

The expression is usually a logical expression. If the value of the expression is true, the statement executes. If the value is false, the statement does not execute.

4.1e) Two Way Selection

To choose between two alternatives—that is, to implement two-way selections—C++ provides the if. . .else statement. Two-way selection uses the following syntax:


![image](https://github.com/cis-famu/oer-assignment-group-5-1/assets/156130748/c873f989-c735-42ed-8ee5-5c5e7b7bbc2b)

In a two-way selection, if the value of the expression is true, statement1 executes. If the value of the expression is false, statement2 executes.

4.1f) Data Type and Logical(Boolean) Expressions

Earlier versions of C++ did not provide built-in data types that had logical (or Boolean) values true and false . Because logical expressions evaluate to either 1 or 0, the value of a logical expression was stored in a variable of the data type int . Therefore, you can use the int data type to manipulate logical (Boolean) expressions.

4.1g) bool Data Type and Logical(Boolean) Expressions

More recent versions of C++ contain a built-in data type, bool, that has the logical (Boolean) values true and false. Therefore, you can manipulate logical (Boolean) expressions using the bool data type. Recall that in C++, bool, true, and false are reserved words. In addition, the identifier true has the value 1, and the identifier false has the value 0.

4.1h) Logical(Boolean) Operators and Logical Expressions

![image](https://github.com/cis-famu/oer-assignment-group-5-1/assets/156130748/3e730219-ed82-42e9-b1f7-615fa222aef9)

4.1i) Order of Precedence 

![image](https://github.com/cis-famu/oer-assignment-group-5-1/assets/156130748/4b3abcc2-22ef-453d-987e-ee63ef1c63e1)

Using the precedence rules in an expression, relational and logical operators are evaluated from left to right. Because relational and logical operators are evaluated from left to right, the associativity of these operators is said to be from left to right.

4.2 Relational Operators and s t r i n g Type
Compund statements or blocks of statements are used to permit more complex statements. These statements consist of one or more statements enclosed in curly braces, { and }. One control statement located inside another is defined as nested. An else statement is paired with the last incomplete if statement. Short-circuit evalution is a process in which the computer evaluates a logical expression from left to right and stops as soon as the final value of the expression is known.
![image](https://github.com/cis-famu/oer-assignment-group-5-1/assets/156258551/f26959ec-212a-47fe-9696-b218668fb35e)

4.3 Using Psuedocode to Develop, Test, and Debug a Program

4.3 Using Psuedocode to Develop, Test, and Debug a Program
 In the development process, we commence with an initial concept outlined through pseudocode, akin to a rough sketch. We refine the code using C++, meticulously addressing variable declaration, error rectification, and comprehensive testing across various scenarios. Using iterative refinement guided by testing outcomes, we ultimately arrive at a finalized program complemented by documentation for future maintenance. This structured methodology underscores the importance of methodical planning, rigorous testing, and continual software development improvement, with pseudocode as a vital tool in conceptualization and refinement.

https://www.wikihow.com/images/thumb/a/a8/1494423-2.jpg/v4-460px-1494423-2.jpg.webp


4.4 Structures 
In C++, switch, case, break, and default are reserved words. In a switch structure, first the expression is researched. The expression is sometimes called the selector. Its value determines which statement is selected for execution. A case value should only appear once. You can use a switch statement only under these conditions: when value expression is matched againts a case value, the exrpession value does not match any case values, and a break statement causing an immediate exit from the switch structure. 

![image](https://github.com/cis-famu/oer-assignment-group-5-1/assets/98242052/93fa5604-ca16-410c-ad35-69cf7efd4824)


4.5 Terminating a Program with the a s s e r t Function 

In C++, certain types of errors, like division by zero, can be difficult to catch. To help with this, C++ have a function named assert. Assert is used to identify and stop an error in a code. If necessary, it can also be used to delete the code. The assert statement is very useful for enforcing programming constraints. Although assert statements are useful during program development, after a program has been developed and put into use, if an assert statement fails for some reason, an end user would have no idea what the error means. Therefore, after you have developed and tested a program, you might want to remove or disable the assert statements. 

![image](https://github.com/cis-famu/oer-assignment-group-5-1/assets/98242052/6c299a2e-dceb-4441-9367-e6ffd423b1ce)


Review Questions:
* What do control structures do? ans: They alter the normal flow of execution.
* How many selection structures are there in C++? ans: 2
* What is s w i t c h? ans: It is a structure used to handle multiple selections 

Summary:
* Including a space within relational operators can cause syntax errors.
* Characters are compared using a machine's collating sequence.
* Logical expressions evaluate to 1 (true) or 0 (false).
* Selection structures in C++ include one-way and two-way selections.
* Programs can be terminated using the a s s e r t fumnction if conditions are not met in a program. 

Key Terms:
* Logical expression: An expression that evaluates to true or false is called a logical expression.
* Logical (Boolean) expressions: an expression that has a value of either true or false
* Decision maker: the expression in an if statement which determines whether to execute the statement that follows it
* Action statement: the statement following the expression in an if statement
* Associativity: the order in which operators are grouped and evaluated

* !=: Not equal to 
* Semantic error: Error due to invalid user writing
* a s s e r t: used to terminate functions

Programming excercises: 

Evaluate 6 * 6 == 90/7

'9' <= '8'

References:
MindTap - Cengage Learning. (n.d.). https://ng.cengage.com/static/nb/ui/evo/index.html?deploymentId=5999972473086198315902738132&eISBN=9780357425220&snapshotId=3814784&id=1997462745& Visited 3/8/24

Editor: Wren King, Cameron Smith, Xavier Blake, Channing Wyatt
