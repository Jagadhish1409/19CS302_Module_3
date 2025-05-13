# EX 12 C program to check whether the given number is prime or not using function without return type and with arguments.
## AIM:
To write a C program to check whether the given number is prime or not using function without return type and with arguments.

## Algorithm
1. Start
2. Declare the variable i.
3. Read the value given using scanf.
4. Check whether the given number is prime or not using if-else statement condition.
5. If true,print ("%d is a prime number.",i).
6. If false, print ("%d is not a prime number.",i).
7. End.   

## Program:
```c
#include<stdio.h> 
int main()
{
int i; 
scanf("%d",&i);
if(i%2==1 && i%1==0)
{
printf("%d is a prime number.",i);
}
else
{
printf("%d is not a prime number.",i);
}
return 0;
}

```

## Output:
![image](https://github.com/user-attachments/assets/b55b7bbc-69ac-4dcd-989c-426f6476ca48)




## Result:
Thus the program was executed and the output was verified successfully.
