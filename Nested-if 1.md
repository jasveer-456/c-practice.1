Task : Find Largest of Three Numbers (Using Nested if)

###  Problem:

Declare:

```c
int a = 10, b = 20, c = 15;
```

Use nested `if` to find the largest number.
## source code
```
# include <stdio.h>

int main(){
	int a = 10;
	int b = 20;
	int c = 15;
	if (b>a)
	{
		if (b>c)
		
		{
			printf("B is greater than a and c");
		}
		else
		{
			printf("b is greater than a but small than c ");
		}
	
	}
}
```
## output
```
B is greater than a and c
