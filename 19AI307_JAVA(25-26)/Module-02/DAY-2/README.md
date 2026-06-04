# Ex.No:2(B) METHODS

## QUESTION:
Write a method named displayMessage() that prints "Welcome to Java Methods!". Call this method from the main() method.

## AIM:
To write a Java program that defines a user-defined method named displayMessage() to print a greeting and calls it from the main() method using an object.

## ALGORITHM :
1. Start the program.

2. Define a class named Message.

3. Create a method displayMessage() inside the class that prints the text "Welcome to Java Methods!".

4. Create the main() method as the entry point of the program.

5. Instantiate an object obj of the Message class.

6. Call the displayMessage() method using the created object (obj.displayMessage()).

7. End the program.





## PROGRAM:
 ```
/*
Program to implement a Methods using Java
Developed by: Amruthavarshini Gopal
RegisterNumber:  212223230013
*/
```

## SOURCE CODE:

```
import java.util.*;
public class Message{
    public void displayMessage(){
        System.out.println("Welcome to Java Methods!");
    }
    public static void main(String[] args){
        Message obj=new Message();
        obj.displayMessage();
    }
}
```





## OUTPUT:

<img width="599" height="168" alt="image" src="https://github.com/user-attachments/assets/97b31611-2dba-41fe-b06a-934bb9b843a3" />


## RESULT:
Thus the program to display the message using method was executed successfully.
