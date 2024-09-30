Question: Explain what a method is in C#?


In C#, a method is a block of code that performs a specific task and can be called to execute that task. Methods help organize code, promote reusability, and improve readability. Here are some key points about methods in C#:

Definition: A method is defined within a class or struct and can take parameters, return a value, or both.

Syntax: The basic syntax of a method includes:

Access modifier (e.g., public, private)
Return type (e.g., int, void)
Method name (e.g., CalculateSum)
Parameter list (in parentheses)
Method body (enclosed in curly braces)

Example:

public int Add(int a, int b)
{
    return a + b;
}

Calling a Method: You invoke a method by using its name and passing the required arguments.

int result = Add(5, 3); // result will be 8


Return Type: If a method has a return type other than void, it must return a value of that type using the return statement.

Parameters: Methods can have parameters that allow you to pass data to them. Parameters can have default values and can be passed by value or by reference.

Overloading: You can define multiple methods with the same name but different parameter lists (types or number of parameters). This is called method overloading.

Static vs. Instance Methods:

Instance Methods: Operate on instances of a class and require an object to be called.
Static Methods: Belong to the class itself and can be called without creating an instance.

Example of a static method:

public static int Multiply(int a, int b)
{
    return a * b;
}


Access Modifiers: Control the visibility of methods. Common modifiers include public, private, protected, and internal.
Methods are fundamental in structuring your C# code, making it easier to manage and maintain.