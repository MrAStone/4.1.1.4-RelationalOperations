<pre lang=c#>
using System;
using System.CodeDom;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace _4._1._1._4_RelationalOperations
{
    internal class Program
    {
        static void Main(string[] args)
        {
            //            Be familiar with and be able to use:
            //• equal to
            int a, b;
            a = 5;
            b = 6;
            Console.WriteLine(a == b); // == is a comparison.  Be careful as = is used for assignment only. // Output False

            //• not equal to
            Console.WriteLine(a != b); // != is not equal to // Output True
            //• less than
            Console.WriteLine(a < b); // Output True

            //• greater than
            Console.WriteLine(a> b); // Ouput False
            //• less than or equal to
            Console.WriteLine(a <= b);// output True
            //• greater than or equal to.
            Console.WriteLine(a >= b); // output False
        }
    }
}
