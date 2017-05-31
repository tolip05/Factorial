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
            int m = int.Parse(Console.ReadLine());
            int factoriel = 1;
            while (true)
            {
                if (m <= 1)
                {
                    break;
                }factoriel *= n;
                m--;

            }
            Console.WriteLine(factoriel);
        }
    }
}
