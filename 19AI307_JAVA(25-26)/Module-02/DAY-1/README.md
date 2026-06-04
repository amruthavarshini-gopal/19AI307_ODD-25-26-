# Ex.No:2(A) CLASS AND OBJECT

## QUESTION:
Create a class Car with attributes brand, model, year. Create 2 objects and print their details.

## AIM:
To write a Java program that defines a Car class with custom attributes, creates two instances (objects) of the class, assigns values to their attributes, and prints their details.

## ALGORITHM :
1.	Start the program.

2. Define a class Car with three attributes: brand (String), model (String), and year (integer).

3. Create the main class prog and add the execution entry point (main method).

4. Instantiate the first object car1 from the Car class and assign its brand, model, and year values.

5. Instantiate the second object car2 from the Car class and assign its brand, model, and year values.

6. Print the details of car1 and car2 by accessing their attributes using the dot (.) operator.

7. End the program.






## PROGRAM:
 ```
/*
Program to implement a Class and Objects using Java
Developed by: Amruthavarshini Gopal
RegisterNumber: 212223230013
*/
```

## SOURCE CODE:

```
public class prog {
    public static void main(String[] args) {
        Car car1 = new Car();
        car1.brand = "Toyota";
        car1.model = "Innova";
        car1.year = 2022;

        Car car2 = new Car();
        car2.brand = "Hyundai";
        car2.model = "i20";
        car2.year = 2021;

        System.out.println("Car 1: " + car1.brand + " " + car1.model + " " + car1.year);
        System.out.println("Car 2: " + car2.brand + " " + car2.model + " " + car2.year);
    }
}
class Car{
    String brand;
    String model;
    int year;
    
}


```





## OUTPUT:

<img width="635" height="234" alt="image" src="https://github.com/user-attachments/assets/9ea078e7-dd6e-4178-b1e8-33e77a84c453" />


## RESULT:
Thus the program to create a class and print their details was executed successfully.
