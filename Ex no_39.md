# EX 39 C program to find sum of digits.
## DATE:
## AIM:
To write a C program to find sum of digits.

## Algorithm
1.Start the program and declare variables to store the number and sum.

2.Read an integer input from the user.

3.Use a loop to extract each digit using modulus and division.

4.Add each digit to the sum variable.

5.Print the sum of digits and end the program. 

## Program:
```
/*
C program to find sum of digits.
*/

#include <stdio.h>

int main()
{
    int num, sum = 0, digit;
    scanf("%d", &num);

    while(num != 0)
    {
        digit = num % 10;
        sum += digit;
        num /= 10;
    }

    printf("Sum of digits: %d\n", sum);

    return 0;
}

```

## Output:
<img width="393" height="239" alt="image" src="https://github.com/user-attachments/assets/a74a00ae-38a2-49fe-a754-c5de2213ee0f" />



## Result:
Thus the program was executed and the output was verified successfully.
