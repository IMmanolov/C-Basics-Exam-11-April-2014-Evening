C-Basics-Exam-11-April-2014-Evening
===================================

using System;

class Cinema
{
    static void Main()
    {
        //Read the input from the console
        
        string typeOFprojection = Console.ReadLine();
        int rows = int.Parse(Console.ReadLine());
        int columns = int.Parse(Console.ReadLine());

        //Solution

        if (typeOFprojection == "Premiere")
        {
            double profit = 12 * rows * columns;
            Console.WriteLine("{0:F2} leva", profit);
        }
        else if (typeOFprojection=="Normal")
        {
            double profit = 7.50 * rows * columns;
            Console.WriteLine("{0:F2} leva", profit);
        }
        else
	    {
            double profit = 5 * rows * columns;
            Console.WriteLine("{0:F2} leva", profit);
	    }



    }
}
