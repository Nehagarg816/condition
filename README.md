# condition
This is a program for conditional operator with printf values.
#include<stdio.h>
#include<conio.h>
void main()
{
	int a;
	printf("Enter one number a:");
	scanf("%d",&a);
	a%2==0?printf("a is an even number"):printf("a is an odd number");
}
