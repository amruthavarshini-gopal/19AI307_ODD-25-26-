# Ex.No:2(E) ACCESS MODIFIERS

## QUESTION:
Create a class College with a final variable universityName = "Saveetha University". Create objects and print the name.

## AIM:
To write a Java program that demonstrates the usage of a final variable inside a class by creating an object and printing its value.

## ALGORITHM :
1. Start the program.

2. Create a class named College containing a final String variable universityName initialized to "Saveetha University".

3. Create the main class prog with a main method.

4. Instantiate an object c of the College class.

5. Print the value of universityName by accessing it through the object (c.universityName).

6. End the program.





## PROGRAM:
 ```
/*
Program to implement a Access Modifiers using Java
Developed by: Amruthavarshini Gopal
RegisterNumber: 212223230013
*/
```

## SOURCE CODE:


```
class College {

    final String universityName = "Saveetha University";
}

class prog {

    public static void main(String[] args) {

        // Creating object
        College c = new College();

        // Printing final variable
        System.out.println(c.universityName);
    }
}
```




## OUTPUT:
<img width="458" height="151" alt="image" src="https://github.com/user-attachments/assets/8520eb83-5840-4f72-b9b0-e5fb95ad6793" />



## RESULT:
Thus the program to create a class using final variable was executed successfully.
