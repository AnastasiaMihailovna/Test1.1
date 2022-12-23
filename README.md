// Напишите программу, которая на вход принимает два числа и выдаёт, какое число большее, а какое меньшее.

Console.WriteLine("Введите число");
int number1=Convert.ToInt32(Console.ReadLine());

Console.WriteLine("Введите число");
int number2=Convert.ToInt32(Console.ReadLine());

if(number1>number2)
{
    Console.WriteLine("max==number1");
}
else
{
    Console.WriteLine ("max==namber2");
}
_________________________

// Задача 6: Напишите программу, которая на вход принимает число и выдаёт, является ли число чётным (делится ли оно на два без остатка).
Console.WriteLine("Введите число");

int number=Convert.ToInt32(Console.ReadLine());

if (number%2==0)
{
    Console.WriteLine("Да");
}
else
{Console.WriteLine("Нет");
}

______________________
Задача 8: Напишите программу, которая на вход принимает число (N), а на выходе 
показывает все чётные числа от 1 до N.

5 -> 2, 4
8 -> 2, 4, 6, 8

Console.WriteLine("Введите число");
int number1=Convert.ToInt32 (Console.ReadLine());
int number1%2==0
While(number1<0)
{
    Console.WriteLine(number1);
    number=number+1;
}
