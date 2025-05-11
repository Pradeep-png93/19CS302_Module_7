# EX 34 C PROGRAM TO READ A FILE NAME FROM USER AND CREATE THAT FILE AND INSERT STUDENT ROLL NUMBERS IN TO THAT FILE
## AIM:
To write a C program to read a file name from user and create that file and insert student roll numbers in to that file.

## Algorithm
1.	Start.
2.	Define a variables.
3.	Write a program to read a file name from user and create that file and insert student roll numbers in to that file.
4.	Read the value using scanf.
5.	Ask the user to make an input.
6.	Print out the answer.
7.	End.

## Program:
```
#include <stdio.h>
int main()
{
FILE *p;
char name[100];
int num;
int id;
char text[100];
float m;
scanf("%s",name);
scanf("%d",&num);
p=fopen("name","w");
printf("%s Opened\n",name);
{
scanf("%d %s %f",&id,text,&m);
fprintf(p,"%d %s %f",id,text,m);
}
fclose(p);
printf("Data added Successfully");
}
```

## Output:
![image](https://github.com/user-attachments/assets/4d76f860-1b7e-4867-b3ec-be5a613f5bbe)


## Result:
Thus the program was executed and the output was verified successfully.
