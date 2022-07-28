## Record of  learning Java with English tutorial

Day  42/Infinity(coding) ~~ July 12, 2022

-----

### Java syntax

1. A constructor in Java is a **special method** that is used to initialize objects

   ```java
   // Create a Main class
   public class Main {
     int x;  // Create a class attribute
   
     // Create a class constructor for the Main class
     public Main() {
       x = 5;  // Set the initial value for the class attribute x
     }
   
     public static void main(String[] args) {
       Main myObj = new Main(); // Create an object of class Main (This will call the constructor)
       System.out.println(myObj.x); // Print the value of x
     }
   }
   
   // Outputs 5
   ```

   Constructors can also take parameters, which is used to initialize attributes.

   ```java
   public class Main {
     int x;
   
     public Main(int y) {
       x = y;
     }
   
     public static void main(String[] args) {
       Main myObj = new Main(5);
       System.out.println(myObj.x);
     }
   }
   
   // Outputs 5
   ```

   

   

2. wild card character ***?***

3. collections framework

### Unfamiliar words & terms:

1. derivative 
