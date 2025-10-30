using System; // Import the System namespace to access basic classes like Console

class Program
{
    static void Main() // Main method: the entry point of the program
    {
        // Display a welcome message to the user
        Console.WriteLine("Welcome to Package Express. Please follow the instructions below.");

        // Ask the user to enter the package weight
        Console.Write("Please enter the package weight: ");
        decimal weight = Convert.ToDecimal(Console.ReadLine()); // Convert user input from text to a decimal number

        // Check if the package weight is greater than 50
        if (weight > 50)
        {
            // If true, show a message and end the program
            Console.WriteLine("Package too heavy to be shipped via Package Express. Have a good day.");
            return; // Ends the program immediately
        }

        // Ask the user to enter the width of the package
        Console.Write("Please enter the package width: ");
        decimal width = Convert.ToDecimal(Console.ReadLine()); // Convert input to a decimal

        // Ask the user to enter the height of the package
        Console.Write("Please enter the package height: ");
        decimal height = Convert.ToDecimal(Console.ReadLine()); // Convert input to a decimal

        // Ask the user to enter the length of the package
        Console.Write("Please enter the package length: ");
        decimal length = Convert.ToDecimal(Console.ReadLine()); // Convert input to a decimal

        // Check if the sum of all dimensions exceeds 50
        if (width + height + length > 50)
        {
            // If total dimensions are too large, display message and stop the program
            Console.WriteLine("Package too big to be shipped via Package Express.");
            return; // Ends the program
        }

        // Calculate the shipping quote:
        // Multiply width × height × length × weight, then divide by 100
        decimal quote = (width * height * length * weight) / 100;

        // Display the final quote formatted as a dollar amount
        Console.WriteLine("Your estimated total for shipping this package is: $" + quote.ToString("0.00"));

        // Thank the user before ending the program
        Console.WriteLine("Thank you!");
    }
}
