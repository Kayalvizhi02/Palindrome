# Palindrome


## Aim:
To write a C# program to find whether the given string is a Palindrome or not.
## Algorithm:
### Step1:
Start.
### Step2:
Create a class and declare the variable with string datatype.
### Step3:
Get the string from the user and store the string in the value variable.
### Step4:
Store the value data to another variable and use the for loop function to check the condition.
### Step5:
Use if - else condition to print that the given string is palindrome or not.
### Step6:
stop.

## Program:
```c#
using System;
class HelloWorld
{
    static void Main()
    {
        string value, dupvalue, rev = "";
        Console.WriteLine("Enter the string");  
        value = Console.ReadLine();
        dupvalue = value;
        for (int s = value.Length - 1; s >= 0; s--)
        {
            rev += value[s];
        }
        if (rev == dupvalue)
            Console.WriteLine(dupvalue + " is a palindrome");
        else
            Console.WriteLine(dupvalue + " is not a palindrome");
    }
}




```
## Output:

![img](https://user-images.githubusercontent.com/75413726/163685534-74ca6138-223f-48f0-b9ff-841ce9dbcd52.png)

## Result:

Thus the C# program to display whether the given string is Palindrome or not is executed successfully.
