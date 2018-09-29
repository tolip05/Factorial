# Factorial
Faktorial
using System;

namespace factoriel1
{
    class Program
    {
        static void Main()
        {
            int a = int.Parse(Console.ReadLine());
            int b = int.Parse(Console.ReadLine());
            int factoriel = 1;
            while (true)
            {
                if (b <= 1)
                {
                    break;
                }factoriel *= a;
                b--;

            }
            Console.WriteLine(factoriel);
        }
    }
}
