# Task: Check Whether a Person is Eligible to Vote.

Write a C program that:

1. Declares an integer variable `age` and assigns it a value.
2. Uses an `if else ` statement to check whether the person is **18 or older**.
3. If the condition is true, print:
   `"You are eligible to vote."`
4. If the condition is false, print:
   `"You are not eligible to vote."`
   
## source code
```
#include <stdio.h>
int main(){
	int age = 20;
	if (age>18)
	{
		printf("you are eligible to vote");
	}
}
```
## output
```
you are eligible to vote
