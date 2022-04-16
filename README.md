# Palindrome


## Aim:
To write a C# program to find whether the given string is a Palindrome or not.
## Algorithm:
### Step1:
Start.
### Step2:

### Step3:

### Step4:

### Step5:

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
