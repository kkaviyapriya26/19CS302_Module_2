# EX 9 C program to find the sum of odd digits using do while loop.
## DATE: 29-04-25
## AIM:
To write a C program to find the sum of odd digits using do while loop.

## Algorithm
1. Start
2. Input a number (num)
3. Initialize sum = 0
4. Do the following:
a. Extract the last digit: digit = num % 10
b. If digit is odd, add it to sum
c. Remove the last digit: num = num / 10
   While num > 0
6. output the value of sum
7. end   

## Program:
```
#include <stdio.h>
int main() {
    int num, digit, sum = 0;
    printf("Enter a number: ");
    scanf("%d", &num);
    if (num < 0) {
        num = -num;  // Make the number positive
    }
    do {
        digit = num % 10;         // Get the last digit
        if (digit % 2 == 1) {     // Check if it's odd
            sum += digit;         // Add to sum
        }
        num = num / 10;           // Remove the last digit
    } while (num > 0);
    printf("Sum of odd digits: %d\n", sum);
    return 0;
}
```

## Output:
![WhatsApp Image 2025-04-29 at 19 51 20_074198c1](https://github.com/user-attachments/assets/3563c1bc-e3b9-474b-a40e-b714b471fdba)

## Result:
Thus the program was executed and the output was verified successfully.
