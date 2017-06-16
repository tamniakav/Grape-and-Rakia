using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Exam1
{
    class Exam1
    {
        static void Main(string[] args)
        {
            double area = double.Parse(Console.ReadLine());
            double kgGrape = double.Parse(Console.ReadLine());
            double brak = double.Parse(Console.ReadLine());

            double grape = area * kgGrape;
            double totalGrape = grape - brak;
            double percentige = (totalGrape * 45) / 100; 

            
            double rakia = percentige / 7.5;

            double moneyFromRakia = rakia * 9.80;
            double percGrape = (totalGrape * 55) / 100;
            

            double moneyFromGrape = percGrape * 1.50;

            Console.WriteLine("{0:f2}", moneyFromRakia);
            Console.WriteLine("{0:f2}", moneyFromGrape);
        }
    }
}
