if-else (Справочник по C#)

    // if-else statement
    if (condition)
    {
        then-statement;
    }
    else
    {
        else-statement;
    }
    // Next statement in the program.

    // if statement without an else
    if (condition)
    {
        then-statement;
    }
    // Next statement in the program.

Обработка ошибок и исключений try catch finally

    try
        {
            int x = 5;
            int y = x / 0;
            Console.WriteLine($"Результат: {y}");
        }
        catch
        {
            Console.WriteLine("Возникло исключение!");
        }
        finally
        {
            Console.WriteLine("Блок finally");
        }
