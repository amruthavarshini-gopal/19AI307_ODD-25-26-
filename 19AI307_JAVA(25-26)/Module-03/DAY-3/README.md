# Ex.No:3(C) ABSTRACTION

## QUESTION:
Create abstract class BankAccount with method calculateInterest(). Extend it in SavingsAccount and FixedDepositAccount.

## AIM:
To implement runtime polymorphism and data abstraction in Java by creating an abstract class BankAccount and overriding its calculateInterest() method in the SavingsAccount and FixedDepositAccount subclasses.

## ALGORITHM :
1. Start the program and initialize a Scanner object for taking input.

2. Define an abstract class BankAccount with an abstract method calculateInterest().

3. Extend subclasses SavingsAccount and FixedDepositAccount to implement the specific interest formulas.

4. Read the choice from the user to determine the account type (1 for Savings, 2 for Fixed Deposit).

5. Instantiate the selected class, read its unique financial inputs, and call calculateInterest().

6. Print the calculated interest formatted to two decimal places and stop.	





## PROGRAM:
 ```
/*
Program to implement a Abstraction using Java
Developed by: Amruthavarshini Gopal
RegisterNumber: 212223230013
*/
```

## SOURCE CODE:
```
import java.util.*;

abstract class BankAccount {
    abstract void calculateInterest();
}

class SavingsAccount extends BankAccount {

    double balance;

    void calculateInterest() {
        System.out.printf("%.2f", balance * 0.04);
    }
}

class FixedDepositAccount extends BankAccount {

    double amount;
    int years;

    void calculateInterest() {
        System.out.printf("%.2f", amount * 0.07 * years);
    }
}

class prog {

    public static void main(String[] args) {

        Scanner sc = new Scanner(System.in);

        int choice = sc.nextInt();

        if (choice == 1) {

            SavingsAccount s = new SavingsAccount();

            s.balance = sc.nextDouble();

            s.calculateInterest();

        } else if (choice == 2) {

            FixedDepositAccount f = new FixedDepositAccount();

            f.amount = sc.nextDouble();
            f.years = sc.nextInt();

            f.calculateInterest();
        }
    }
}
```






## OUTPUT:

<img width="327" height="332" alt="image" src="https://github.com/user-attachments/assets/86fa6cd7-ba56-452f-8c1c-61ba02544d1c" />


## RESULT:
Thus the program to create an abstract class was executed successfully.
