# shecodes_question_first_round
#include<stdio.h>
#include<conio.h>
void main()
{
clrscr();
int a,b,c=0;
printf("Program to repeat number in case of repetition otherwise returning sum of three numbers\n\n" );
printf("enter any three numbers\n");
scanf("%d %d %d", &a, &b, &c);
if(a==b)
printf("The repeated number is: %d\n",a);
else if(a==c)
{
printf("The repeated number is: %d\n",a);}
else if(b==c)
{
printf("The repeated number is: %d\n",b);
}
else
{
c=a+b+c;
printf(" The sum of entered numbers is: %d\n",c);
}
printf("Program by Tulsi Thakur\n");
getch();
}
