# Advanced-C-Lab-Manual
## EXP NO:1A C PROGRAM FOR ARRAY OF STRUCTURE TO CHECK ELIGIBILITY FOR THE VACCINE:

## Aim:
To write a C program for array of structure to check eligibility for the vaccine person age above 6 years of age.

## Algorithm:
1.	Declare structure eligible with age (integer) and n (character array)
2.	Declare variable e of type eligible
3.	Input age and name using scanf, store in e
4.	If e.age <= 6
-	Print "Vaccine Eligibility: No"
Else
-	Print "Vaccine Eligibility: Yes"
5.	Print details (e.age, e.n)
6.	Return 0
 
## Program:
```
#include<stdio.h> struct eligib
{
int age; char n[4];
};
int main()
{
struct eligib e; scanf("%d%s",&e.age,e.n);
if(e.age<=6)
{
printf("Age:%d\nName:%svaccine:%d\neligibility:no",e.age,e.n,e.age);
}
 
else
{
}
 

printf("Age:%d\nName:%svaccine:%d\neligibility:yes",e.age,e.n,e.age);
 

}
```
## OUTPUT

![exp1 c](https://github.com/user-attachments/assets/0509c342-f059-42b1-ac3c-7b495bc43d89)

## RESULT
Thus, the program to check eligibility for the vaccine is verified successfully. 


