# Ex.No:2(D) VARIABLE SCOPE AND CONSTRUCTOR

## QUESTION:
Write a program to access a static variable using both class name and object.

## AIM:
To write a Java program that demonstrates how to declare a static variable and access it using both the class name and an object instance of that class.

## ALGORITHM :
1.	Start the program.

2. Read an integer value from the user.

3. Assign this value to the static variable (number) inside the Test class using the class name: Test.number.

4. Create an object named obj for the Test class.

5. Print the static variable by referencing the class name (Test.number).

6. Print the same static variable by referencing the object (obj.number).

7. End the program.





## PROGRAM:
 ```
/*
Program to implement a Variable scope and Constructor using Java
Developed by: Amruthavarshini Gopal
RegisterNumber: 212223230013
*/
```

## SOURCE CODE:
```
import java.util.Scanner;

class Test {

    static int number;
}

class prog {

    public static void main(String[] args) {

        Scanner sc = new Scanner(System.in);

        // Input
        Test.number = sc.nextInt();

        // Object creation
        Test obj = new Test();

        // Access using class name
        System.out.println("Accessing using class name: " + Test.number);

        // Access using object
        System.out.println("Accessing using object: " + obj.number);

        sc.close();
    }
}
```






## OUTPUT:
<img width="733" height="354" alt="image" src="https://github.com/user-attachments/assets/b4bed7ca-ee2b-476a-9578-8fe40c17c1e1" />



## RESULT:
Thus the program to access a static variable using both class name and object was executed successfully.
