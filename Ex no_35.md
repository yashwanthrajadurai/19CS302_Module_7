# EX 35 C program to create a file named "Hospital.txt" and display messages on successful creation, opening, and closing of the file.

## AIM:

To write a C program to create a file named "Hospital.txt" and display messages on successful creation, opening, and closing of the file.

## Algorithm

Start.

Define a variables.

Write a program to read a file name from user and create that file and insert student roll numbers in to that file.

Read the value using scanf.

Ask the user to make an input.

Print out the answer.

End.

## Program:

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


## Output:

![Screenshot 2025-05-26 133356](https://github.com/user-attachments/assets/0366213a-9f39-4156-934e-a49959d86f89)


## Result:

Thus the program was executed and the output was verified successfully.
