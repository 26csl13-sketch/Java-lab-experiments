## CODE
class Book {
    int id;
    String name, title, author, category;
    double price;
    boolean available;

    Book(int i, String n, String t, String a, String c, double p, boolean av) {
        id=i; name=n; title=t; author=a;
        category=c; price=p; available=av;
    }

    void display() {
        System.out.println(id+" "+name+" "+title+" "+author+" "+category+" "+price+" "+available);
    }
}

public class Main {
    public static void main(String[] args) {
        Book b1 = new Book(101,"Nandha","Java Programming","James Gosling","Programming",550,true);
        b1.display();
    }
}


## Aim
To design and implement a Java program demonstrating classes,
objects, constructors and methods.

## Procedure
1. Create a class named Book.
2. Declare book details.
3. Create a constructor to initialize the details.
4. Create a display method.
5. Create an object in the main method.
6. Display the book details.


## Result
Thus, the Java program using classes, objects, constructors
and methods was executed successfully.


