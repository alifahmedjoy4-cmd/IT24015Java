# Code
```java
class Vehicle {

    // Private data members (encapsulation)
    private String brand;
    private String color;

    // Constructor to initialize values
    public Vehicle(String brand, String color) {
        this.brand = brand;   // assign brand
        this.color = color;   // assign color
    }

    // Public method to display information
    public void start() {
        System.out.println("Vehicle Brand: " + brand);   // print brand
        System.out.println("Vehicle Color: " + color);   // print color
        System.out.println("Vehicle is starting...");    // status message
        System.out.println(); // empty line for spacing
    }
}
class IT24015 {
    public static void main(String[] args) {

        // Creating first object using first two arguments
        Vehicle v1 = new Vehicle(args[0], args[1]);

        // Calling method for first vehicle
        v1.start();

        // Creating second object using next two arguments
        Vehicle v2 = new Vehicle(args[2], args[3]);

        // Calling method for second vehicle
        v2.start();
    }
}
```
