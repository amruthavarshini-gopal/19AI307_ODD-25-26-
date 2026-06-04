# Ex.No:1(D) ARRAYS

## QUESTION:
Write a Java Program to count Even and Odd Numbers in an Array.

## AIM:
To write a Java program that reads a list of numbers from the user and counts how many of them are even and how many are odd.


## ALGORITHM :
1.	Start the program.

2. Take an integer n from the user to decide how many numbers they want to enter.

3. Set two counters, even and odd, to 0.

4. Loop n times to read each number:

5. Take a number input (num).If num is divisible by 2 (num % 2 == 0), increase the even counter by 1.Otherwise, increase the odd counter by 1.

6. Print the final counts of even and odd numbers.

7. End the program.






## PROGRAM:
 ```
/*
Program to implement a Array concept using Java
Developed by: Amruthavarshini Gopal
RegisterNumber: 212223230013
*/
```

## SOURCE CODE:

```
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        int n = sc.nextInt();
        int even = 0, odd = 0;

        for (int i = 0; i < n; i++) {
            int num = sc.nextInt();
            if (num % 2 == 0) {
                even++;
            } else {
                odd++;
            }
        }

        System.out.println("Number of even elements: " + even);
        System.out.println("Number of odd elements: " + odd);
    }
}
```



## OUTPUT:

<img width="735" height="582" alt="image" src="https://github.com/user-attachments/assets/2edc1549-9a07-4a24-ae5e-9e4f9711b67d" />


## RESULT:
Thus the program to count even and odd number using arrays was executed successfully.
