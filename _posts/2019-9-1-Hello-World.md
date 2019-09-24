---
layout: post
title: If statements 
categories: c# programming 
---
If statements can be used in order to make your computer run certain things depending on certain situations and run something else if the input does not meet those specifications
---
            Console.WriteLine("Enter number A");
            int number1 = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("Enter number B");
            int number2 = Convert.ToInt32(Console.ReadLine());
            if (number1 < number2)
            {
                Console.WriteLine(number2 + " is larger");
            }
            else if (number1 == number2)
            {
                Console.WriteLine("They are equal");

            }
            else
            {
                Console.WriteLine(number1 + " is larger");
            }
            Console.ReadLine();
-----------------------------------------------------
