# Ex.No:1(C) LOOPING STATEMENT

## QUESTION:
Write a Java program that takes an integer input from the user and then reverses its digits using a while loop.


## AIM:
To write a Java program that reverses a given integer using arithmetic operations (modulus and division) within a loop.

## ALGORITHM :
1.	Start the program.

2. Take an integer input from the user and store it in n.

3.	Set a variable rev to 0.

4. Loop while n is not 0:

5. Get the last digit of n (using n % 10).

6. Add this digit to the end of rev (using rev * 10 + digit).

7. Drop the last digit from n (using n / 10).

8. Print the rev number after the loop ends.

9. End the program.





## PROGRAM:
 ```
/*
Program to implement a Looping Statement using Java
Developed by: Amruthavarshini Gopal
RegisterNumber:  212223230013
*/
```

## SOURCE CODE:
```
import java.util.*;

public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();

        int rev = 0;

        while (n != 0) {
            int digit = n % 10;    
            rev = rev * 10 + digit; 
            n = n / 10;             
        }

        System.out.println("Reversed number: " + rev);
    }
}
```






## OUTPUT:

<img width="671" height="296" alt="image" src="https://github.com/user-attachments/assets/59b3361c-6465-415d-9f8e-0ab29932b855" />


## RESULT:
Thus the program to reverse a digit was executed successfully.
