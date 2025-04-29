# EX 7 C Program to Print a right triangle star Pattern using nested for loop
## DATE: 29-04-25
## AIM:
To write a C Program to Print a right triangle star Pattern using nested for loop

## Algorithm
1. Start.
2. Declare the variables i,j,k,n.
3. Prompt the user to enter a value.
4. Read the value using scanf.
5. Enter number of rows and columns.
6. End.  

## Program:
```
#include <stdio.h>
int main() {
 int i, j, rows;
 scanf("%d", &rows);
 for (i = 1; i <= rows; i++) {
 for (j = 1; j <= i; j++) {
 printf("*");
 }
 printf("\n");
 } return 0;
}
```

## Output:
![image](https://github.com/user-attachments/assets/84525891-56ba-478f-8f85-02caf4e91dda)

## Result:
Thus the program was executed and the output was verified successfully.
