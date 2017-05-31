# Factorial
Faktorial
using System;

namespace factoriel1
{
    class Program
    {
        static void Main()
        {
            int n = int.Parse(Console.ReadLine());
            int b = int.Parse(Console.ReadLine());
            int factoriel = 1;
            while (true)
            {
                if (b <= 1)
                {
                    break;
                }factoriel *= n;
                b--;

            }
            Console.WriteLine(factoriel);
        }
    }
}
