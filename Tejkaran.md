# Name-Tej Karan Singh
# Class-It(B2)
# Class Roll no.-1921108

```C
1, Write a program on to add two numbers.

#include <stdio.h>
int main()
{
    int firstNumber, secondNumber, sumOfTwoNumbers;
    
    printf("Enter two integers: ");
    // Two integers entered by user is stored using scanf() function
    scanf("%d %d", &firstNumber, &secondNumber);
    // sum of two numbers in stored in variable sumOfTwoNumbers
    sumOfTwoNumbers = firstNumber + secondNumber;
    // Displays sum      
    printf("%d + %d = %d", firstNumber, secondNumber, sumOfTwoNumbers);
    return 0;
}
Output-![](https://ibb.co/TTxTW89)
