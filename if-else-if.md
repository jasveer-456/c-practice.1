**`if-else if` practice tasks in C (without user input)** 

---

# Task 1: Grade Calculator

###  Problem:

Declare `int marks = 75;`

Use `if-else if` to print grade according to marks:

* 90 and above → `"Grade A"`
* 75 to 89 → `"Grade B"`
* 50 to 74 → `"Grade C"`
* Below 50 → `"Fail"`

---
## source code
```
#include <stdio.h>

int main(){
	int marks = 75;
	if(marks>=90)
	{
		printf("Grade A");
	}
	else if (marks>75 || marks<89)
	{
		printf("Grade B");
	}
	else if(marks>50 || marks<74)
	{
		printf("Grade C");
	}
	else
	{
		printf("Fail");
	}
}
```
## output
```
Grade B
