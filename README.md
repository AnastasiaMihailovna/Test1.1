// Задание 21. Напишите программу, которая принимает на вход пятизн.число и проверяет, 
// является ли оно палиндромом.
Console.WriteLine("Введите пятизначное число");
int num=Convert.ToInt32(Console.ReadLine());
string aNum=Convert.ToString (num);
if (aNum[0]==aNum[4]&&aNum[1]==aNum[3])
{
    Console.WriteLine("Да");
}
else
{
    Console.WriteLine("Нет");
}
_____________________________________________________

//Напишите программу, которая принимает на вход число и выдает таблицу кубов чисел от 1 до N.
Console.WriteLine("Введите число");
int num =Convert.ToInt32(Console.ReadLine ());
for (int i=1; i<=num;i++)
{
    Console.WriteLine (i*i*i);
}
