#  Task : Eligible for Scholarship

###  Problem:

Declare:

```c
int marks = 85;
int income = 200000;
```

Conditions:

* If marks are **80 or above**

  * Then check if income is **less than 300000**

    * Print `"Eligible for Scholarship"`
    * Otherwise print `"Not Eligible (Income High)"`
* Otherwise print `"Not Eligible (Low Marks)"`

---

## Source code

```
#include <stdio.h>

int main(){
	int marks = 85;
    int income = 200000;
    if(marks <=85)
    {
    	if(income <=300000)
    	{
    		printf("Eligible for Scholarship");
		}
		else
		printf("Not Eligible (Income High)");
	}
	else
	printf("Not Eligible (Low Marks)");
}
```

---

## Output
```
Eligible for Scholarship
```
