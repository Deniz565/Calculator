using System;

class Calculator
{
    static void Main()
    {
        while (true)
        {
            Console.WriteLine("Simple Calculator");
            Console.WriteLine("1. Addition");
            Console.WriteLine("2. Subtraction");
            Console.WriteLine("3. Multiplication");
            Console.WriteLine("4. Division");
            Console.WriteLine("5. Exit");

            Console.Write("Enter your choice (1-5): ");
            int choice = int.Parse(Console.ReadLine());

            if (choice == 5)
            {
                Console.WriteLine("Exiting the calculator. Goodbye!");
                break;
            }

            Console.Write("Enter the first number: ");
            double num1 = double.Parse(Console.ReadLine());

            Console.Write("Enter the second number: ");
            double num2 = double.Parse(Console.ReadLine());

            double result = 0;

            switch (choice)
            {
                case 1:
                    result = Add(num1, num2);
                    break;
                case 2:
                    result = Subtract(num1, num2);
                    break;
                case 3:
                    result = Multiply(num1, num2);
                    break;
                case 4:
                    result = Divide(num1, num2);
                    break;
                default:
                    Console.WriteLine("Invalid choice. Please enter a number between 1 and 5.");
                    continue;
            }

            Console.WriteLine($"Result: {result}");
        }
    }

    static double Add(double a, double b)
    {
        return a + b;
    }

    static double Subtract(double a, double b)
    {
        return a - b;
    }

    static double Multiply(double a, double b)
    {
        return a * b;
    }

    static double Divide(double a, double b)
    {
        if (b != 0)
        {
            return a / b;
        }
        else
        {
            Console.WriteLine("Error: Cannot divide by zero.");
            return double.NaN; // Not a Number
        }
    }
}
