# taller-5-p8

using System;

using System.Collections.Generic;

using System.Linq;

using System.Text;

using System.Threading.Tasks;

using static System.Math;


namespace ConsoleApplication4


{

    class Program
    {
        public static double Avarage(params int[] numbers)
        {
            double total = 0;
            double x = 0;
            foreach (int number in numbers)
                total += number;

            x = total / numbers.Length;
            
            Console.WriteLine("{0}", x);
            
            return x;
            
        }
        
        static void Main(string[] args)
        
        {
        
            Avarage(20,56,76,2456, 2456);
            
            Console.ReadKey();
            
        }
        

    }
}
