# Ex.No:1(E) STRINGS AND MATH FUNCTION

## QUESTION:
Write a Java program to calculate the power of a given number.

## AIM:
To write a Java program that calculates the result of a base number raised to the power of an exponent using the Math.pow() method.

## ALGORITHM :

1.	Start the program.

2. Create a Scanner object to read inputs from the user.

3. Take a decimal number for the base and store it in b.

4. Take another decimal number for the power (exponent) and store it in p.

5. Calculate the result by raising b to the power of p using Math.pow(b, p) and store it in res.

6. Print the final message showing the base, the power, and the calculated result.

7. End the program.





## PROGRAM:
 ```
/*
Program to implement a Strings and Math Function using Java
Developed by: Amruthavarshini Gopal
RegisterNumber: 212223230013
*/
```

## SOURCE CODE:

```
import java.util.*;
public class Main{
    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        double b=sc.nextDouble();
        double p=sc.nextDouble();
        double res=Math.pow(b,p);
        System.out.println(b + " raised to the power of " + p + " is: " + res); 
    }
}
```





## OUTPUT:

<img width="934" height="294" alt="image" src="https://github.com/user-attachments/assets/f71ac8ce-bf0d-42de-842e-889d8eec4e6c" />


## RESULT:
Thus the program to calculate the power of the given number was executed successfully.
