I’m probably currently involved in a game, job, or sport...
I’m also currently learning how to code...
How to reach me: e2020@gmail.com...
-Forrester

// Ask for the first name.
Console.WriteLine("Hello, what is your first name?");

string name = Console.ReadLine();

// Ask for last name.
Console.WriteLine($"Hello {name}, What is your last name?");

string lastname = Console.ReadLine();
Console.WriteLine($"{name} {lastname}, how old are you?");

// Ask for their age, but Console.ReadLine(); only returns strings.

int age = int.Parse(Console.ReadLine());
Console.WriteLine($"Ok, you are {age}?");


// Ask what sport they like.
Console.WriteLine($"What sport do you like, {name}?");

string Sport = Console.Readine();

// Ask if they have a favorite song.
Console.WriteLine($"Ok, what is your favorite song?");

string song = Console.ReadLine();

// Last ask for their shoe size.
Console.WriteLine("What size shoe do you wear?");
string shoeSize = Console.Readline();

// The survey is finished, thank the guest and show them the results.

Console.WriteLine($"Thank you for completing this survey {name}.");

Console.WriteLine($"Person: {lastname}, {name}");

Console.WriteLine($"Age: {age}");

Console.WriteLine($"Sport: {sport}");

Console.WriteLine($"Favorite Song: {song}");

Console.WriteLine($"Shoe Size: {shoeSize}");

Console.WriteLine("Sincerely " +
"-Forrester");
