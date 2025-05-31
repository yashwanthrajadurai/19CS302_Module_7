# EX 31 C program to find the smallest among three numbers using Structure.

## AIM:

To write a C program to find the smallest among three numbers using Structure.

## Algorithm

Start.

Define a variables.

Write a program to find the smallest among three numbers using structure.

Read the value using scanf.

Ask the user to make an input.

Print out the answer.

End.

## Program:

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



## Output:


![Screenshot 2025-05-26 132023](https://github.com/user-attachments/assets/9440414a-c858-4e40-91bf-87216aa503bd)


## Result:

Thus the program was executed and the output was verified successfully.
