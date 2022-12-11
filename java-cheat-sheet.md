# Java Cheet Sheet

The basics hopefully in an easy way.

## Base Class 
```
public class Main {

}
```

## `main` syntax
```
public static void main(String[] args) {

}
```

## Simple print syntax
```
// Write text to the standard output (terminal)
System.out.println("Hello Pink!");
```

## All together
```
public class Main {
    public static void main(String[] args) {
        // Write text to the standard output (terminal)
        System.out.println("Hello Pink!");
    }
}
```

## Compile 
```
javac AmazingApplication.java
```
## Run
```
java AmazingApplication
```

## Types

`null` - Nothing!

```
int myNum = 5;               // Integer (whole number)
float myFloatNum = 5.99f;    // Floating point number
char myLetter = 'D';         // Character
boolean myBool = true;       // Boolean
String myText = "Hello";     // String
```

read more [here](https://www.w3schools.com/java/java_data_types.asp)

## Function definition
Function that returns nothing and prints something out
```
public static void saySomething(String something) {
    System.out.println(something);
}
```

Function that adds two numbers and returns the result
```
public static int addNumbers(int first, int second) {
    return first + second;
}
```

A function in the full class
```
public class Main {
    public static int addNumbers(int first, int second) {
        return first + second;
    }

    public static void main(String[] args) {
        // Write text to the standard output (terminal)
        System.out.println(addNumbers(40, 2));
    }
}
```

## Numeric operations
```
+ add two numbers 5 + 2 = 7
- substract numbers 3 - 1 = 2
/ divide 12 / 2 = 6 
* multiply 2 * 5 = 10
% rest from division 7 % 5 = 2
```
read more [here](https://www.w3schools.com/java/java_operators.asp)

## Strings
```
String txt = "ABCDEFGHIJKLMNOPQRSTUVWXYZ";
System.out.println("The length of the txt string is: " + txt.length());
```

read more [here](https://www.w3schools.com/java/java_strings.asp)


## Arrays
```
String[] cars = {"Volvo", "BMW", "Ford", "Mazda"};
System.out.println(cars[0]);
// Outputs Volvo

int[] myNum = {10, 20, 30, 40};
```

read more [here](https://www.w3schools.com/java/java_arrays.asp)
