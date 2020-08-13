using System;
using System.Diagnostics.CodeAnalysis;
using System.Globalization;
using System.Reflection.Emit;

namespace kurs2._1
{
    class Program
    {
        public static int LeastCommonMultiple (int a, int b)
        {
            int numb1, numb2;
            if (a > b)
            {
                numb1 = a; numb2 = b;
            }
            else
            {
                numb1 = b; numb2 = a;
            }
            for (int i = 1; i <= numb2; i++)
            {
                if ((i * numb1) % numb2 == 0)
                {
                    return i * numb1;
                }
            }
            return numb2;
        }
        static void Main(string[] args)
        {
            //Console.WriteLine("Zad.1 \r\n");
            //int a, b, range, end;
            //int[] array = new int[1000];
            //Console.Write("Define the end range of Prime Numbers you want to see: ");
            //range = Int32.Parse(Console.ReadLine());
            //end = (int)Math.Floor(Math.Sqrt(range));

            //for (int i = 0; i <= range; i++)
            //{
            //    array[i] = i;
            //}

            //for (int i = 2; i <= end; i++)
            //{
            //    if (array[i] != 0)
            //    {
            //        a = i + i;
            //        while (a <= range)
            //        {
            //            array[a] = 0;
            //            a += i;
            //        }
            //    }

            //}
            //Console.WriteLine("Prime numbers from 1 to " + range);
            //for (b = 2; b <= range; b++)
            //{
            //    if (array[b] != 0)
            //        Console.Write(b + ", ");
            //}
            //Console.WriteLine();
            //Console.WriteLine($"The total iteration is {b + 1} times");

            //Console.WriteLine("Zad. 2 \r\n");
            //int n = 0;
            //do
            //{
            //    Console.WriteLine(2 * n);
            //    n++;
            //}
            //while (n <= 1000);

            //Console.WriteLine("Zad. 3 \r\n");
            //int a = 0, b = 1, c = 1;
            //for (int i = 0; i < 20; i++)
            //{
            //    c = a;
            //    a += b;
            //    b = c;
            //    Console.WriteLine(a);
            //}

            //Console.WriteLine("Zad. 4 \r\n");
            //int lvl = 1;
            //int count = 0;
            //Console.Write("Write the last number at the end of pyramid: ");
            //int numb = Int32.Parse(Console.ReadLine());
            //for (int i = 0; i <= numb; i++)
            //{
            //    if (count < lvl)
            //    {
            //        Console.Write(i);
            //        Console.Write(" ");
            //        count++;
            //    }
            //    else
            //    {
            //        count = 0;
            //        lvl++;
            //        Console.Write("\n");
            //        i--;
            //    }
            //}

            //Console.WriteLine("Zad. 5 \r\n");
            //Console.Write("Type the number you want to power: ");
            //bool numb = Int32.TryParse(Console.ReadLine(), out int a);
            //do
            //{
            //    Console.WriteLine(Math.Pow(a, 3));
            //    a++;
            //}
            //while (a <= 20);

            //Console.WriteLine("Zad. 6 \r\n");

            //double add = 0;
            //for (double i = 1; i <= 20; i++)
            //{
            //   add += 1 / i;  
            //}
            //Console.WriteLine($"Total is {add}");

            //Console.WriteLine("Zad. 7 \r\n");
            //int a;
            //Console.Write("Enter the length of the diagonal: ");
            //a = Int32.Parse(Console.ReadLine());
            //int b = a - 1;

            //for (int i = 0; i < a; i++)
            //{
            //    for (int j = 0; j < b; j++)
            //        Console.Write(" ");
            //    for (int j = 0; j <= i; j++)
            //        Console.Write("* ");
            //    Console.WriteLine();
            //    b--;
            //}

            //b = 1;

            //for (int i = a - 1; i > 0; i--)
            //{
            //    for (int j = 0; j < b; j++)
            //        Console.Write(" ");
            //    for (int j = 0; j < i; j++)
            //        Console.Write("* ");
            //    Console.WriteLine();
            //    b++;
            //}

            //Console.WriteLine("Zad. 8 \r\n");
            //Console.WriteLine("Enter the text: ");
            //string word = Console.ReadLine();
            //string result = "";
            //for (int i = word.Length-1; i >= 0; i--)
            //{
            //    result = String.Concat(result, word[i]);
            //}
            //Console.WriteLine(result);
            //Console.WriteLine("Zad. 9 \r\n");

            //int n, i;
            //int[] a = new int[10];
            //Console.Write("Enter the decimal number:  ");
            //n = int.Parse(Console.ReadLine());
            //for (i = 0; n > 0; i++)
            //{
            //    a[i] = n % 2;
            //    n = n / 2;
            //}
            //Console.Write("Binary result is:  ");
            //for (i = i - 1; i >= 0; i--)
            //{
            //    Console.Write(a[i]);
            //}

            Console.WriteLine("Zad. 10 \r\n");
            //used function LeastCommonMultiple
            Console.WriteLine("Enter two numbers to find the LCM:");
            int numb1 = Int32.Parse(Console.ReadLine());
            int numb2 = Int32.Parse(Console.ReadLine());
            int LCMresult = LeastCommonMultiple(numb1, numb2);
            Console.WriteLine("The LeastCommonMultiple between {0} and {1} is {2}", numb1, numb2, LCMresult);

            Console.Read();


        }
    }
}
