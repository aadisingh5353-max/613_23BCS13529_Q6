# 613_23BCS13529_Q6
E-6: Student Information System using Abstraction and 
Inheritance 
 
Problem Statement 
Educational institutions often manage different types of individuals students, teachers, etc. They 
may share some basic information (like name and age), but also have role-specific attributes. 
You are asked to create a system that uses abstraction to generalize common behavior and 
inheritance to differentiate student and teacher details. 
Create an abstract class Person with the following attributes: 
name (String) 
age (int) 
And the method: 
displayDetails() abstract method 
Then create two derived classes: 
Student (with additional attribute: rollNumber - int) 
Teacher (with additional attribute: subjectCode - int) 
Override displayDetails() in both classes and display all relevant information. 
 
Input Format 
Person type (1 for Student, 2 for Teacher) 
Name (String, assume as a single word or hardcoded for simplicity) 
Age (int) 
Roll Number (int) for Student OR Subject Code (int) for Teacher 
 
Output Format 
Print details of Student or Teacher using the overridden method. 
 
Constraints 
Age must be a positive number 
Roll Number and Subject Code must be integers 
Name should be treated as a single-word string 
Sample Test Case 1 
Input: 
1 
Alice 
20 
1001 
Output: 
Student Details: 
Name: Alice 
Age: 20 
Roll Number: 1001 
Explanation: 
A student named Alice, aged 20, with roll number 1001 is created. 
The overridden method displays these details as student information.
