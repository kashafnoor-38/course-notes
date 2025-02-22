## Object-Oriented Programming (OOP)
Object-Oriented Programming (OOP) is a programming paradigm that focuses on organizing code using objects and classes. It enhances code modularity, reusability, and maintainability by structuring programs around real-world entities.

## Core Concepts of OOP
 Class  – A blueprint for creating objects. It defines properties (attributes) and behaviors (methods).
 ```cpp
#include <iostream>
using namespace std;

class Car {
private:
    string brand;
    string model;
    int year;

public:
    // Constructor
    Car(string b, string m, int y) {
        brand = b;
        model = m;
        year = y;
    }

    // Method to display car details
    void displayInfo() {
        cout << "Car: " << year << " " << brand << " " << model << endl;
    }
};

int main() {
    // Creating an object of Car class
    Car myCar("Toyota", "Corolla", 2022);
    
    // Displaying car details
    myCar.displayInfo();

    return 0;
}
```

Object – An instance of a class that contains specific data and can perform actions.

Encapsulation – Hiding internal details of an object and restricting direct access to some attributes for data security.

Inheritance – Allowing a class to derive properties and behaviors from another class, promoting reusability.

Polymorphism – Enabling a single interface to be used for different data types or classes, making code more flexible.

Abstraction – Hiding complex implementation details and exposing only the necessary functionality to the user.

## Benefits of OOP
✔ Code Reusability – Reduces redundancy by using classes and objects multiple times.
<br>
✔ Modularity – Organizes code into separate entities, making it easy to manage.
<br>
✔ Scalability – Supports easy modification and extension of code.
<br>
✔ Security – Protects sensitive data using encapsulation.
<br>

OOP is widely used in languages like Java, Python, C++, and C# for building scalable and efficient applications.
