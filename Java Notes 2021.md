Definitions
Package - a way to organize your java projects, for now consider them as folders with learnprogramming in our example being a subfolder of academy. Companies use their domain names reversed.

Data types are divided into two groups:

    Primitive data types - includes byte, short, int, long, float, double, boolean and char
    Non-primitive data types - such as String, Arrays and Classes (you will learn more about these in a later chapter)

Even though there are many numeric types in Java, the most used for numbers are int (for whole numbers) and double (for floating point numbers). However, we will describe them all as you continue to read.

Non-primitive data types are called reference types because they refer to objects.

The main difference between primitive and non-primitive data types are:

    Primitive types are predefined (already defined) in Java. Non-primitive types are created by the programmer and is not defined by Java (except for String).
    Non-primitive types can be used to call methods to perform certain operations, while primitive types cannot.
    A primitive type has always a value, while non-primitive types can be null.
    A primitive type starts with a lowercase letter, while non-primitive types starts with an uppercase letter.
    The size of a primitive type depends on the data type, while non-primitive types have all the same size.

Java Type Casting

Type casting is when you assign a value of one primitive data type to another type.

In Java, there are two types of casting:

    Widening Casting (automatically) - converting a smaller type to a larger type size
    byte -> short -> char -> int -> long -> float -> double

    Narrowing Casting (manually) - converting a larger type to a smaller size type
    double -> float -> long -> int -> char -> short -> byte

public class Main {
public static void main(String[] args) {
int myInt = 9;
double myDouble = myInt; // Automatic casting: int to double

    System.out.println(myInt);      // Outputs 9
    System.out.println(myDouble);   // Outputs 9.0

}
}

Java Syntax
![](/assets/images/2021-07-26-16-07-00.png)

Byte occupies 8 bits, a byte hasa width of 8

A short can store 16 bits and a width of 16

A int occupies 32bits and has a width of 32

To Create a Integer
int myFirstnumber = 5

To Print Something onto the console
System.out.println()

Maximum Value
Integer.MAX_VALUE;

Minimum Value
Integer.Min_VALUE;

Byte Maximum Value
byte myMaxByteValue = Byte.MAX_VALUE;

Byte Minimum Value
Byte.MIN_VALUE;

short myMinShortValue = Short.MIN_VALUE;

long myMaxLongValue = Long.MAX_VALUE;

Single and Double Precision
Single Precision occupies 32bits

Double precision occupies 64bits

![](/assets/images/2021-07-26-21-44-39.png)

Float
float myMinFloatValue = Float.MIN_VALUE;
![](/assets/images/2021-07-26-21-50-21.png)

Final Variables - final keyword if you dont want others or yourself to overwrite existing values
final int myNum = 15;

Examples of Variable types
int myNum = 5;
float myFloatNum = 5.99f;
char myLetter = 'D';
boolean myBool = true;
String myText = "Hello";

Char - The char data type is used to store a single character. The character must be surrounded by single quotes, like 'A' or 'c':
char myGrade = 'B';
System.out.println(myGrade);

Math.max(x,y)
The Math.max(x,y) method can be used to find the highest value of x and y:
Math.max(5, 10);

Math.min(x,y)
The Math.min(x,y) method can be used to find the lowest value of x and y:
Math.min(5, 10);

Math.sqrt(x)
The Math.sqrt(x) method returns the square root of x:
Math.sqrt(64);

Math.abs(x)
The Math.abs(x) method returns the absolute (positive) value of x:
Math.abs(-4.7);

Random Numbers
Math.random() returns a random number between 0.0 (inclusive), and 1.0 (exclusive):
Math.random();

The else Statement

Use the else statement to specify a block of code to be executed if the condition is false.
Syntax

if (condition) {
// block of code to be executed if the condition is true
} else {
// block of code to be executed if the condition is false
}
