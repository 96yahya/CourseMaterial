C# Basics
-	Declarations:

using System;

class Program
{
    static void Main()
    {
        // Variable declaration and assignment

        int age = 25;
        string name = "John Doe";
        float temperature = 98.6f;
        bool isStudent = true;

        // Displaying the values of the variables

        Console.WriteLine("Name: " + name);
        Console.WriteLine("Age: " + age);
        Console.WriteLine("Temperature: " + temperature);
        Console.WriteLine("Is Student: " + isStudent);

        // Modifying variable values
        age = 26;
        temperature = 99.2f;
        isStudent = false;

        Console.WriteLine("\nModified values:");

        Console.WriteLine("Age: " + age);
        Console.WriteLine("Temperature: " + temperature);
        Console.WriteLine("Is Student: " + isStudent);
    }
}
 
-	Read and write:
using System;

class Program
{
    static void Main()
    {
        Console.WriteLine("What is your name?");
        string name = Console.ReadLine();

        Console.WriteLine("How old are you?");
        int age = Convert.ToInt32(Console.ReadLine());

        Console.WriteLine("What is your favorite color?");
        string color = Console.ReadLine();

        Console.WriteLine("\nThank you for providing the following information:");
        Console.WriteLine("Name: " + name);
        Console.WriteLine("Age: " + age);
        Console.WriteLine("Favorite Color: " + color);
    }
}
 
-	Selection statements:
If statement:
if (condition)
{
// Code to execute if the condition is true
}
int num = 10;
if (num > 0)
{
    Console.WriteLine("The number is positive.");
}

If else statement:
if (condition)
{
    // Code to execute if the condition is true
}
else
{
    // Code to execute if the condition is false
}

int num = 10;
if (num > 0)
{
    Console.WriteLine("The number is positive.");
}
else
{
    Console.WriteLine("The number is not positive.");
}








-	Switch statement:

switch (variable)
{
    case value1:
        // Code to execute if variable matches value1
        break;
    case value2:
        // Code to execute if variable matches value2
        break;
    // More case statements...
    default:
        // Code to execute if no case matches
        break;
}

char grade = 'B';
switch (grade)
{
    case 'A':
        Console.WriteLine("Excellent!");
        break;
    case 'B':
        Console.WriteLine("Good job!");
        break;
    case 'C':
        Console.WriteLine("Keep going!");
        break;
    default:
        Console.WriteLine("Try again next time!");
        break;
}
