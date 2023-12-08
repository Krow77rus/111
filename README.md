
using System;

class Program
{
    static void Main(string[] args)
    {
        Console.WriteLine("Введите вашу фамилию:");
        string фамилия = Console.ReadLine();

        Console.WriteLine("Ваша фамилия: " + фамилия);

        // Чтобы программа не закрылась сразу после вывода результата
        Console.WriteLine("Нажмите любую клавишу для выхода...");
        Console.ReadKey();
    }
}
