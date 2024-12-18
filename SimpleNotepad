using System;
using System.Collections.Generic;

class SimpleNotepad
{
    static List<string> notes = new List<string>();

    static void Main()
    {
        string command;
        do
        {
            Console.WriteLine("Options: [add/view/exit]");
            command = Console.ReadLine()?.ToLower();

            if (command == "add")
            {
                Console.Write("Enter note: ");
                string note = Console.ReadLine();
                notes.Add(note);
                Console.WriteLine("Note added.");
            }
            else if (command == "view")
            {
                Console.WriteLine("Your notes:");
                foreach (string note in notes)
                {
                    Console.WriteLine("- " + note);
                }
            }

        } while (command != "exit");

        Console.WriteLine("Goodbye!");
    }
}
