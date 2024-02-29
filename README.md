using System;

class Program
{
    public static void Main(string[] args)
    {
        Console.Write("What is the area of a circle? ");
        float fruitCost = float.Parse(Console.ReadLine());
        float tax = fruitCost * 0.13f;
        float total = fruitCost + tax;
        Console.WriteLine($"The tax is ${tax} and the total is ${total}.");

        if (total > 30) 
        {
            Console.WriteLine("That's a rip-off!");
        } 
        else if (total <= 30 && total >= 10) 
        {
            Console.WriteLine("Meh, a bit pricey");
        } 
        else 
        {
            Console.WriteLine("Ok, here is my money");
        }


    }
}
