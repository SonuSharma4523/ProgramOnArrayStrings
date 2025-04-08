# ProgramOnArrayStrings


using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ArrayStringPrograms
{
    class Program
    {
        static void Main(string[] args)
        {
            // 1. How to reverse a string in c#

            //string str = "Sonu Sharma";
            //string Restr = "";
            //foreach (var c in str)
            //{
            //    Restr = c + Restr;
            //}
            //Console.WriteLine(str);

            // 2.How to print an array

            //  int[] arr = { 1, 2, 3, 4, 5 };
            //foreach (var c in arr)
            //{

            //    Console.WriteLine(c);
            //}

            // 3.How to count occurrences of a character in a string?

            //string str = "banana";
            //char search = 'a';
            //int count = 0;

            //foreach (char c in str)
            //{
            //    if (c == search) count++;
            //}
            //Console.WriteLine(count);

            //4. how to reverse an array
            //int[] arr = { 1, 2, 3, 4, 5 };
            //int[] reversedArr = new int[arr.Length];
            //for (int i = 0; i < arr.Length; i++)
            //{
            //    reversedArr[arr.Length - 1 - i] = arr[i];
            //}
            //foreach (var item in reversedArr)
            //{
            //    Console.WriteLine(item);
            //}

            // or
            //int[] arr = { 1, 2, 3, 4, 5 };
            //for (int i = arr.Length - 1; i >= 0; i--)
            //{
            //    Console.WriteLine(arr[i]);
            //}

            // 5. How to sum of a array
            //int[] arr = { 5, 4, 6, 7, 3 };
            //int sum = 0;
            //foreach (var c in arr)
            //{
            //    sum += c;
            //}
            //Console.WriteLine(sum);   


            // 6. How to find the maximum value in an array  
            //int[] arr = { 10, 50, 30, 20, 70 };
            //int max = arr[0];

            //foreach (int num in arr)
            //{
            //    if (num > max)
            //        max = num;
            //}
            //Console.WriteLine(max); 

            // 6. How to find the minimum value in an array  
            //int[] arr = { 10, 50, 30, 20, 70 };
            //int max = arr[0];

            //foreach (int num in arr)
            //{
            //    if (num < max)
            //        max = num;
            //}
            //Console.WriteLine(max); 


            // 7.0 How to count vowels in a string?
            //string str = "Hello World";
            //int count = 0;
            //string vowels = "aeiouAEIOU";

            //for (int i = 0; i < str.Length; i++)
            //{
            //    if (vowels.Contains(str[i]))
            //        count++;
            //}
            //Console.WriteLine(count);
            // 8.0 how to sort an array
            //int[] arr = { 40, 50, 10, 20, 70 };
            //int n = arr.Length;

            //for (int i = 0; i < n - 1; i++)
            //{
            //    for (int j = 0; j < n - i - 1; j++)
            //    {
            //        if (arr[j] > arr[j + 1]) // Swap if the element is greater
            //        {
            //            int temp = arr[j];
            //            arr[j] = arr[j + 1];
            //            arr[j + 1] = temp;
            //        }
            //    }
            //}
            //foreach (var item in arr)
            //    {
            //        Console.WriteLine(item);
            //    }
            // 9.0 Simple Pyramid
            //int rows = 5;
            //for (int i = 1; i <= rows; i++)
            //{
            //    Console.Write(new string(' ', rows - i)); // Print spaces
            //    Console.WriteLine(new string('*', 2 * i - 1)); // Print stars
            //}


            //Or
        //    int rows = 5;
        //    for (int i = 1; i <= rows; i++)
        //    {
        //        // Print spaces
        //        for (int j = i; j < rows; j++)
        //        Console.Write(" ");

        //    // Print stars
        //    for (int k = 1; k <= (2 * i - 1); k++)
        //        Console.Write("*");

        //    Console.WriteLine();
        //}


        Console.ReadLine();


            }
        }
    }

