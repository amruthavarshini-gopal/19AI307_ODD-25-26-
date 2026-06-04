# Ex.No:3(A) INHERITANCE AND AGGREGATION

## QUESTION:
```
Create a Super class Person with fields name and age. Create a subclass Student that inherits from Person and adds a field marks (integer). Implement a method in Student called calculateGrade() which returns the grade based on the marks:

Marks ≥ 90: Grade A

Marks ≥ 75 and < 90: Grade B

Marks ≥ 50 and < 75: Grade C

Marks < 50: Grade F
```
## AIM:
To implement single inheritance in Java by creating a superclass Person and a subclass Student to calculate and display a student's grade based on their marks.

## ALGORITHM :
1. Start the program and initialize a Scanner object for input.

2. Define a superclass Person with attributes name and age.

3. Define a subclass Student that extends Person and adds a marks attribute.

4. Implement a method calculateGrade() in Student to check the marks using conditional statements (if-else if) and print the corresponding grade (A, B, C, or F).

5. Create an instance of the Student class in the main method.

6. Read the name, age, and marks from the user.

7. Display the input details and call the calculateGrade() method to print the final grade.

8. End the program.





## PROGRAM:
 ```
/*
Program to implement a Inheritance and Aggregation using Java
Developed by: Amruthavarshini Gopal
RegisterNumber:  212223230013
*/
```

## SOURCE CODE:
```
import java.util.*;
class Person{
    String name;
    int age;
    
}
class Student extends Person{
    int marks;
    void calculateGrade(){
        if(marks>=90){
            System.out.println("Grade: A");
        }
        else if(marks>=75 && marks<90){
            System.out.println("Grade: B");
        }
        else if(marks >=50 && marks <=75){
            System.out.println("Grade: C");
        }
        else{
            System.out.println("Grade: F");
        }
    }
}
class prog{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        Student s=new Student();
        s.name=sc.next();
        s.age=sc.nextInt();
        s.marks=sc.nextInt();
        System.out.println("Name: " +s.name);
        System.out.println("Age: " +s.age);
        System.out.println("Marks: "+s.marks);
        s.calculateGrade();
    }
}
```




## OUTPUT:

<img width="558" height="515" alt="image" src="https://github.com/user-attachments/assets/40fb1b0c-7753-4bd7-acb3-2d75a56ec046" />


## RESULT:
Thus the program to create a inheritance was executed successfully.
