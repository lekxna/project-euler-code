# project-euler-code
I will start making and uploading challenging project euler solutions

using System;
namespace ConsoleApp1
{
    class Program
    {
        static void Main(string[] args)
        {
            long num = 600851475143;
            for (long i = 2; i <= Math.Sqrt(num); i++)
            {
                while (num % i == 0)
                {
                    num = num / i;
                    Console.WriteLine(num);
                }
               
            }
        }
    }
}   
