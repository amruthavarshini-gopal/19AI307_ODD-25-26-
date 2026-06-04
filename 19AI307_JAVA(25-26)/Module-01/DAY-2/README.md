# Ex.No:1(B) CONDITIONAL STATEMENT

## QUESTION:

A pirate ship has a code lock that only opens if:

The input code is even, and

If it is less than 100, say "Weak Code".

If it is between 100 and 999, say "Strong Code".

If the code is odd, deny access -"Access Denied".


## AIM:
To write a Java program that simulates a pirate ship's code lock by validating an input code based on even/odd conditions and range checks.

## ALGORITHM :
1.	Start the program.

2.	Create a Scanner object to read input from the console.

3.	Read an integer from the user and store it in the variable code.

4.	Check if code is even using the condition code % 2 == 0.

5.	If the code is even, check its range:
   If code < 100, print "Weak Code".
   Else if code is between 100 and 999 (inclusive), print "Strong Code".
   Otherwise (if it is 1000 or greater), print "Access Denied".

6. If the code is odd, immediately print "Access Denied".

7. Close the Scanner object to free system resources.

8. End the program.

## PROGRAM:
 ```
/*
Program to implement a conditional statement using Java
Developed by: Amruthavarshini Gopal
RegisterNumber:  212223230013
*/
```

## SOURCE CODE:


```
import java.util.Scanner;

public class PirateLock {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int code = scanner.nextInt();

        if (code % 2 == 0) {
            if (code < 100) {
                System.out.println("Weak Code");
            } else if (code >= 100 && code <= 999) {
                System.out.println("Strong Code");
            } else {
                System.out.println("Access Denied");
            }
        } else {
            System.out.println("Access Denied");
        }
        
        scanner.close();
    }
}

```




## OUTPUT:
<img width="496" height="378" alt="image" src="https://github.com/user-attachments/assets/73f79186-0f67-4b9f-bb44-56b7b26278dc" />



## RESULT:
Thus the program to simulates a pirate ship's code lock by validating an input code based on even/odd conditions and range check was done successfully.
