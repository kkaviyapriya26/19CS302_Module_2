# EX 10 C program to find the factorial of a given number using a function with arguments and return type.
## DATE: 29-04-25
## AIM:
To write a C program to find the factorial of a given number using a function with arguments and return type.

## Algorithm
1. Start.
2. Declare the variables.
3. Prompt the user to enter a value.
4. Read the value using scanf.
5. Enter factorial of the number.
6. End.
## Program:
```
#include <stdio.h>
int main() {
 int n, i;
 unsigned long long factorial = 1;
 scanf("%d", &n);
 if (n < 0) {
 printf("Factorial is not defined for negative numbers.\n");
 } else {
 for (i = 1; i <= n; i++) {
 factorial *= i;
 }
 printf("Factorial of %d = %llu\n", n, factorial);
 }
 return 0;
}
```

## Output:
![image](https://github.com/user-attachments/assets/0afa0724-0bca-4008-b8dd-f4580bb7f687)

## Result:
Thus the program was executed and the output was verified successfully.
