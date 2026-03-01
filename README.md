# G.Jyotsna-10505_JAVA
This is my Java assignments works based on if else and for loop conditions


📌 Overview
This assignment demonstrates the use of if-else conditional statements and for loops in Java. These are basic control structures used to make decisions and repeat actions in a program.


🎯 Objective
Understand how if-else statements work.
Learn how to use a for loop for repetition.
Combine both concepts in a simple Java program.


🛠 Concepts Used

1️⃣ If-Else Statement

The if-else statement is used to execute different blocks of code based on a condition.
Syntax:
Java
Copy code
if(condition) {
    // code if condition is true
} else {
    // code if condition is false
}

2️⃣ For Loop

The for loop is used when we know how many times we want to repeat a block of code.
Syntax:
Java
Copy code
for(initialization; condition; increment/decrement) {
    // repeated code
}

💻 Sample Program

Java
Copy code
import java.util.Scanner;

public class IfElseForExample {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter a number: ");
        int number = sc.nextInt();

        // If-Else Example
        if(number % 2 == 0) {
            System.out.println("The number is Even.");
        } else {
            System.out.println("The number is Odd.");
        }

        // For Loop Example
        System.out.println("Numbers from 1 to " + number + ":");
        for(int i = 1; i <= number; i++) {
            System.out.println(i);
        }

        sc.close();
    }
}

▶️ How to Run

Save the file as IfElseForExample.java
Open terminal/command prompt.
Compile:
Copy code

javac IfElseForExample.java
Run:
Copy code

java IfElseForExample

📊 Expected Output (Example)

Copy code

Enter a number: 5
The number is Odd.
Numbers from 1 to 5:
1
2
3
4
5

✅ Conclusion

This assignment shows how:
if-else helps in decision-making.
for loop helps in repeating tasks.
Both can be combined to create interactive Java programs.
