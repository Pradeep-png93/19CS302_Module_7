# EX 33 C PROGRAM TO READ A FILE NAME FROM USER AND CREATE THAT FILE USING FOPEN().
## AIM:
To write a C program to read a file name from user and create that file using fopen().

## Algorithm
1.	Start.
2.	Define a variables.
3.	Write a program to read a file name from user and create that file using fopen().
4.	Read the value using scanf.
5.	Ask the user to make an input.
6.	Print out the answer.
7.	End  

## Program:
```
#include <stdio.h>
int main()
{FILE *p;
char name[40];
scanf("%s",name);
p=fopen("name","w");
printf("%s File Created Successfully\n",name);
printf("%s File Opened\n",name);
fclose(p);
printf("%s File Closed",name);
}
```

## Output:

![image](https://github.com/user-attachments/assets/8e32a7c7-7c25-4fb5-b043-f0392c303600)

## Result:
Thus the program was executed and the output was verified successfully.
