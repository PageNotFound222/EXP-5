# EXPERIMENT 5:To study and implement C++ decision making statements
## NAME: PRATHAMESH GALPHADE
## PRN-24070123123
Decision-making is a fundamental concept in programming that allows a program to choose between different paths of execution based on specific conditions. In C++, this is done using conditional or decision control statements. These help the program respond differently depending on the situation, making the code more dynamic and interactive.

Basic if and if-else Statements:
The if statement is the simplest form of decision-making in C++. It runs a block of code only if a certain condition is true. When we want to run one block if the condition is true and a different one if it's false, we use the if-else statement. These are perfect for making basic yes-or-no decisions in a program.

Using if-else-if Ladder and Nested if-else:
When there are multiple conditions to evaluate, the if-else-if ladder is helpful. It checks each condition one by one until one is true, then runs the associated block. For more complex decisions, we use nested if-else statements—putting one if inside another. This lets us handle layered conditions and fine-tuned decision-making.

Switch Statement:
The switch statement is another powerful decision-making tool in C++. It's especially useful when we want to compare a single variable or expression against several possible values. Instead of writing multiple if-else blocks, the switch provides a cleaner and more organized way to manage such comparisons.

Implementation Summary:
To demonstrate how decision-making works in C++, several simple programs were created. These include checking if a number is odd or even, verifying if a character is a vowel, finding the largest of three numbers, building a calculator using a switch statement, and even creating a basic banking system using switch-case logic. These practical examples help solidify the concepts in a real-world context.

Based on the above decision making statements in C++ , Simple programs have been used to help understand how decision making statements work in c++. The programs are:

Odd-Even check
Vowel Check
Finding the largest number from three given numbers by the user
Making a Calculator using Switch Case
Made a basic banking system using Switch Case

Algorihtms:
Program 1:

Objective: To determine whether a user-entered number is even or odd.

Steps:

Start

Ask the user to enter an integer (n)

Read input into variable n

Check divisibility of n by 2:

If n % 2 == 0, then:

Display "This is an even number"

Else:

Display "This is an Odd number"

End
Program 2:

Objective: To determine whether the character entered by the user is a vowel or a consonant.

Steps:

Start

Declare a character variable str

Ask the user to enter a character

Read the input into str

Check if the character is a vowel:

If str is equal to 'a', 'e', 'i', 'o', 'u' (or their uppercase forms), then:

Display "The Character entered is a Vowel"

Else:

Display "The Character entered is a Consonant"

End
Program 3

Objective:

To determine and display the largest number among three user-entered integers.

Steps:

Start

Declare three integer variables: a, b, c

Ask user to enter three numbers

Read input values into a, b, and c

Initialize num ← a

Compare b and c with num:

If b > num, set num ← b

If c > num, set num ← c

Display the largest number (num)

End

Program 4:

Objective: To perform one of four basic arithmetic operations—Addition, Subtraction, Multiplication, or Division—based on user input.(calculator)

Steps:

Start

Declare float variables a, b, sum, sub, mul, Div and integer num

Ask user to enter two numbers

Read inputs into a and b

Ask user to select an operation:

1 → Addition

2 → Subtraction

3 → Multiplication

4 → Division

Read input into num

Use a switch-case statement to perform the selected operation:

Case 1: sum ← a + b

Case 2: sub ← a - b

Case 3: mul ← a * b

Case 4: Div ← a / b

Default: Display invalid input message

Display the result of the selected operation

End
