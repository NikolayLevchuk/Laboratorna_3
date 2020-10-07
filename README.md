# Laboratorna_3

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
 
namespace ConsoleApplication15
{
    //***********************Лабораторна №3**********************************\\
    /*Вариант 13
        13. Перевірити істинність вислову: &quot;Цифри даного тризначного числа
              утворюють зростаючу послідовність&quot;.
     */
    
    class Program
    {
        static void Main(string[] args)
        {
            string str;
            int i;
            Console.WriteLine("Введите трехзначное число образующее строго возрастную последовательность");
            str = Console.ReadLine();
            if (str[0] < str[1] && str[1] < str[2] )
                Console.WriteLine("true");
            else
                Console.WriteLine("false");
        }
    }
}
