# Ex.No:3(b) POLYMORPHISM

## QUESTION:
Write a Java program that calculates the area of different shapes using method overloading. Create a class AreaCalculator with:

area(int side) for square

area(int length, int breadth) for rectangle

area(double radius) for circle



## AIM:
To write a Java program that demonstrates compile-time polymorphism (method overloading) by calculating the areas of a square, rectangle, and circle using methods with the same name but different parameter lists


## ALGORITHM :
1. Start the program.

2. Read input values for side, length, breadth, and radius.

3. Create an object of the AreaCalculator class.

4. Call area(side) to compute and print the square's area.

5. Call area(length, breadth) to compute and print the rectangle's area.

6. Call area(radius) to compute and print the circle's area and stop.





## PROGRAM:
 ```
/*
Program to implement a Polymorphism using Java
Developed by: Amruthavarshini Gopal
RegisterNumber: 212223230013 
*/
```

## SOURCE CODE:
```
import java.util.Scanner;

class AreaCalculator {

    int area(int side) {
        return side * side;
    }

    int area(int length, int breadth) {
        return length * breadth;
    }

    double area(double radius) {
        return Math.PI * radius * radius;
    }
}
public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        AreaCalculator obj = new AreaCalculator();

        int side = sc.nextInt();
        int length = sc.nextInt();
        int breadth = sc.nextInt();
        double radius = sc.nextDouble();

        System.out.println("Area of square: " + obj.area(side));
        System.out.println("Area of rectangle: " + obj.area(length, breadth));
        System.out.println("Area of circle: " + obj.area(radius));

        sc.close();
    }
}
```






## OUTPUT:

<img width="784" height="352" alt="image" src="https://github.com/user-attachments/assets/0fed80b1-e18d-49da-8666-ecea471d018d" />


## RESULT:
Thus the program to calculate the area of circle using overloading was executed successfully.
