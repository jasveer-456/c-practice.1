#  Task 3: Number Type Checker

###  Problem:

Declare `int num = 0;`

Use `if-else if` to check:

* If number is positive
* If number is negative
* Otherwise print `"Number is Zero"`
---
## source code
```
# include <stdio.h>

int main(){
	int num = 0;
	if(num <0)
	{
		printf("number is negative");
	}
	else if (num>0)
	{
		printf("number is positive");
	}
	else
	{
		printf("number is zero");
	}
}
```
## output
```
number is zero
