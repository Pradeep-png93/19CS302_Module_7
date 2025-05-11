# EX 31 C PROGRAM TO FIND THE SMALLEST AMONG THREE NUMBERS USING STRUCTURES
## AIM:
To write a C program to find the smallest among three numbers using Structure.

## Algorithm
1.	Start.
2.	Define a variables.
3.	Write a program to find the smallest among three numbers using structure.
4.	Read the value using scanf.
5.	Ask the user to make an input.
6.	Print out the answer.
7.	End.

## Program:
```
#include<stdio.h>
struct num
{
int a,b,c;
};
int main()
{
struct num n;
scanf("%d%d%d",&n.a,&n.b,&n.c);
if(n.a<n.b&&n.a<n.c)
{
printf("%d",n.a);
}
else if(n.b<n.a&&n.b<n.c)
{
printf("%d",n.b);
}
else
{printf("%d",n.c);}}
```

## Output:

![image](https://github.com/user-attachments/assets/eb8f6f8b-4733-4e7a-a27e-aa6fa8822e77)


## Result:
Thus the program was executed and the output was verified successfully.
