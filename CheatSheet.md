[Google drive slides](https://drive.google.com/drive/u/0/folders/1JAMXS9jJRH3kxISSy5qVaTuK1jRvXaX1)

[TutorialsPoint](https://www.tutorialspoint.com/csharp/csharp_decision_making.htm)

[GC_Github](https://github.com/grandcircusco)

[GC_June_Examples](https://github.com/grandcircusco/CSharpBootcamp_June2022)

[Classroom_Codeshare](https://docs.google.com/document/d/1EVBRWABNdaM124Io1wmBlqFopW8_jbMUn2OrC75cf1Q/preview)

[Odd_or_Even](https://csharp-station.com/how-to-test-for-even-or-odd-numbers-in-c/#:~:text=One%20great%20way%20to%20use,no%20remainder%20must%20be%20eve)

[GC_CheatSheet](https://github.com/grandcircusco/cheatsheets/tree/master/csharp)

[W3Schools](https://www.w3schools.com/cs/index.php)



Convert.ToInt32 = int
.ToInt64 = long
.ToSingle = float
.ToDouble = double
.PARSE

Math.Abs() - gets absolute value
Math.Floor() - largest integer value less than the provided value
Math.Ceiling() - smallest integer value greater than the provided value
Math.Round() - rounds the provided value to the nearest integer value

Remainder Operator (Modulus, Mod)
10 % 3 = 1
10 % 4 = 2
10 % 2 = 0
Can use this to check odd or even.[EX: if (userNumber %2 == 0){even}] if 0 remainder then even.

AND - &&
OR - ||

Common String Methods:

To.Lower()
To.Upper()

//example switches
//example if/elseif/else
//



Casting example
int points
Points = pointIncrease += pointIncrease;
Level = (int)Math.Ceiling((double)Points / 1000);



use linq for practice assessment questions

.where (x => x % 2 == 0).ToList();


classes with base - you don't typically want people to build new objects from the base class. You want them to create it from the classes that derive from it. Should use the "protected" access modifier private means no one can get to it and protected means only me and only things that inherit me

you can protect the methods

protected stops this from happening candyBar.Cost = 234.22;

the sealed modifier means that the class can't be inherited. You can have truck class, fordtruck class and then you can seal fordtruck so it forces people to use the truck class

You cannot put protected in a class
You can put protected on a setter
You can put protected in a constructor

would probably use it more on a constructor vs a member


"Sealed"

Polymorphism
The condition incurring in several different forms

the ability of an object of differnent types to provide an interface for different methods. Allows multiple things to do different things

overloading and overriding

overloading methods


