#  Task 4: Weekday Checker

###  Problem:

Declare `int day = 3;`

Use `if-else if` to print:
1 → Monday
2 → Tuesday
3 → Wednesday
4 → Thursday
5 → Friday
Otherwise → `"Invalid day"`

---
## source
```
# include <stdio.h>

int main(){
	int day = 3;
	if (day == 1)
	{
		printf("Monday");
	}
	else if (day ==2)
	{
		printf("Tuesday");
	}
	else if (day ==3)
	{
		printf("Wednesday");
	}
	else
	{
		printf("Invalid day");
	}
}
```
## output
```
Wednesday
