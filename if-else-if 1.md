# Task 2: Largest of Three Numbers

###  Problem:

Declare three integers:
`int a = 10, b = 25, c = 15;`

Use `if-else if` to print the largest number.

---
## source code
```
# include<stdio.h>

int main(){
	int a = 10;
	int b = 25;
	int c = 15;
	if (a>=b && a>=c)
	{
	printf("a is greater than b and c");
    }
    else if (b>=a && b>=c)
    {
    	printf("b is greater than a and c");
	}
	else
	{
		printf("c is greater than a and b");
	}
}
```
## output
```
b is greater than a and c
