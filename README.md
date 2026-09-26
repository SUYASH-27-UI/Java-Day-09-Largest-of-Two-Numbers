# Java-Day-09-Largest-of-Two-Numbers
# Java Day 9 - Largest of Two Numbers

This program takes two numbers from the user and finds the largest number using `if-else` conditions.

## Example Input

```text id="input9"
Enter first number: 45
Enter second number: 30
```

## Output

```text id="output9"
Largest number = 45
```

## Conditions

* If `num1 > num2`, the first number is largest.
* If `num2 > num1`, the second number is largest.
* If both are equal, the program displays that both numbers are equal.

## Concepts Used

* Scanner
* User input
* `if` statement
* `else if` statement
* `else` statement
* Comparison operators

## How It Works

1. The program takes two numbers from the user.
2. It compares the first number with the second number.
3. If the first number is greater, it is displayed as the largest.
4. Otherwise, the second number is checked.
5. If both numbers are equal, a separate message is displayed.
6. The result is printed on the screen.

## Java Code

```java id="code9"
import java.util.Scanner;

public class Main
{
    public static void main(String[] args)
    {
        Scanner sc = new Scanner(System.in);

        System.out.print("Enter first number: ");
        int num1 = sc.nextInt();

        System.out.print("Enter second number: ");
        int num2 = sc.nextInt();

        if (num1 > num2)
        {
            System.out.println("Largest number = " + num1);
        }
        else if (num2 > num1)
        {
            System.out.println("Largest number = " + num2);
        }
        else
        {
            System.out.println("Both numbers are equal.");
        }

        sc.close();
    }
}
```

## Sample Output

```text id="sample9"
Enter first number: 45
Enter second number: 30
Largest number = 45
```

## Goal

The goal of this project is to practice comparing two numbers using `if-else if-else` statements in Java.
