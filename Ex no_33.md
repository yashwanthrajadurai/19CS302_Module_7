# EX 33 C program to read a file name from user and create that file using fopen().

## AIM:

To write a C program to read a file name from user and create that file using fopen().

## Algorithm

Start.

Define a variables.

Write a program to read a file name from user and create that file using fopen().

Read the value using scanf.

Ask the user to make an input.

Print out the answer.

End.

## Program:

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


## Output:

![Screenshot 2025-05-26 132925](https://github.com/user-attachments/assets/a6628354-ba92-48f4-8e8b-19d5c8460dfd)


## Result:

Thus the program was executed and the output was verified successfully.
