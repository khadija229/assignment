# assignment
// shopping calculation

using System;

class Program
{
    static void Main(string[] args)
    {
        double allTotal = 0;
        int choice = 1;

        while (choice == 1)
        {

            Console.WriteLine("Enter price please :");
            double Price = Convert.ToDouble(Console.ReadLine());

            Console.WriteLine("Please provide the product quantity :");
            int Quantity = Convert.ToInt32(Console.ReadLine());

            double total = Price * Quantity;

            Console.WriteLine("Total = " + total);

            allTotal += total;

            Console.WriteLine("Add another product ? 1 = Yes, 0 = No: ");
            choice = Convert.ToInt32(Console.ReadLine());

        }

        Console.WriteLine("All Total = " + allTotal);
    }
}
