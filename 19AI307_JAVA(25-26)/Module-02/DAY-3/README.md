# Ex.No:2(C) ACCESS SPECIFIERS

## QUESTION:
 Write a Java program to create a class called “Book” with private instance variables title, author, and price. Provide public getter and setter methods to access and modify these variables. Add a method called applyDiscount() that takes a percentage as a parameter and reduces the price by that percentage.

## AIM:
To write a Java program implementing encapsulation using a Book class with private variables, public getters/setters, and a method to calculate a discounted price.

## ALGORITHM :
1.	Start the program.

2. Define a Book class with private fields (title, author, price) and public getter/setter methods.

3. Add an applyDiscount() method inside Book to reduce the price by a given percentage.

4. Create a main method to take inputs for the book's title, author, price, and discount percentage using Scanner.

5. Use setter methods to assign values to the book object and call applyDiscount().

6. Print the final details using the display() method.

7. End the program.





## PROGRAM:
 ```
/*
Program to implement a Access Specifiers using Java
Developed by: Amruthavarshini Gopal
RegisterNumber: 212223230013
*/
```

## SOURCE CODE:

```
import java.util.Scanner;

class Book {
    private String title;
    private String author;
    private double price;

    // Getter methods
    public String getTitle() {
        return title;
    }

    public String getAuthor() {
        return author;
    }

    public double getPrice() {
        return price;
    }

    // Setter methods
    public void setTitle(String title) {
        this.title = title;
    }

    public void setAuthor(String author) {
        this.author = author;
    }

    public void setPrice(double price) {
        this.price = price;
    }

    // Method to apply discount
    public void applyDiscount(double percentage) {
        if (percentage > 0 && percentage <= 100) {
            price = price - (price * (percentage / 100));
        }
    }

    // Method to display details
    public void display() {
        System.out.println("Title: " + title);
        System.out.println("Author: " + author);
        System.out.printf("Discounted Price: %.2f\n", price);
        System.out.println("-------------------------");
    }
}

class prog {

    public static void main(String[] args) {

        Scanner sc = new Scanner(System.in);

        Book b = new Book();

        // Input
        b.setTitle(sc.nextLine());
        b.setAuthor(sc.nextLine());
        b.setPrice(sc.nextDouble());

        double discount = sc.nextDouble();

        // Apply discount
        b.applyDiscount(discount);

        // Display output
        b.display();

        sc.close();
    }
}
```





## OUTPUT:
<img width="865" height="525" alt="image" src="https://github.com/user-attachments/assets/d48e4196-24c7-4151-88f4-1a92183213c5" />



## RESULT:
Thus the program to write the acess specifier for the given program was executed successfully.
