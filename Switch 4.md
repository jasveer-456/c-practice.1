##  Task  — Menu Driven Program

Create a menu-driven program:

```
1. Addition
2. Subtraction
3. Exit
```

---

## Source code
```
#include <stdio.h>

int main(){
	int a=4;
		switch(a){
		case 1:
			printf("Addition");
			break;
		case 2:
			printf("Subtraction");
			break;
		case 3:
			printf("Exit");	
			break;
		default:
			printf("Invalid Number");		
	}
}
```

## Output
```
Invalid Number
```
