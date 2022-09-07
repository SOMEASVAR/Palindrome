# Palindrome


## Aim:
To write a C# program to find whether the given string is a Palindrome or not.
## Algorithm:
## Step 1:
To start the C# program in visual Studio 2022.

## Step 2:
Create a class and declare two variable with string datatype.

## Step 3:
Loop over the entire string and reverse it.

## Step 4:
Use if condition to check whether the string and the reversed string is equal or not.

## Step 5:
print palindrome if it's equal else print not a palindrome.

## Step 6:
Save the program and run the program in visual studio 2022.

## Program:
```
PROGRAM DEVELOPED BY: R.SOMEASVAR
REGISTER NUMBER: 212221230103
```
```
using System;
class palindrome
{
    static void Main()
    {
        string number, remainder, reverse = "";
        number=Console.ReadLine();
        remainder = number;
        for (int s = number.Length - 1; s >= 0; s--)
        {
            reverse += number[s];

        }
        Console.WriteLine(reverse);
        if(reverse==remainder)
        {
            Console.WriteLine(remainder + " is a palindrome");
        }
        else
        {
            Console.WriteLine(remainder + " is not a palindrome");
        }



    }
}
```

## Output:
## Case 1:
![output](./palindrome%20number.jpg)
## Case 2:
![output](./not%20a%20palindrome%20number.jpg)


## Result:
Thus the C# program to display whether the given string is Palindrome or not is executed successfully.
