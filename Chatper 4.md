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

4.2 Relational Operators and s t r i n g Type

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
* !=: Not equal to 
* Semantic error: Error due to invalid user writing
* a s s e r t: used to terminate functions

Programming excercises: 

Evaluate 6 * 6 == 90/7

'9' <= '8'

References:
MindTap - Cengage Learning. (n.d.). https://ng.cengage.com/static/nb/ui/evo/index.html?deploymentId=5999972473086198315902738132&eISBN=9780357425220&snapshotId=3814784&id=1997462745& Visited 3/8/24

Editor: Wren King, Cameron Smith, Xavier Blake, Channing Wyatt
