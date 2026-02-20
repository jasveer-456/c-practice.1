## Task — Simple Calculator

Write a program that:

* Takes two integers and an operator (`+`, `-`, `*`, `/`)
* Uses `switch` to perform the selected operation
* Displays the result

---
## source code
```
#include <stdio.h>

int main(){
	int a=10;
	int b=20;
	char op='*';
	int result;
	switch (op){
		case '+':
			result=a+b;
			printf(" %d",result);
			break;
		case '*':
			result=a*b;
			printf(" %d" ,result);
			break;	
		case '-':
		    result=a-b;
			printf("%d",result);
			break;
		case'/':
			result=a/b;
			printf("%d",result);
			break;
		default:
			printf("wrong");			
	}
}
```

---

## Output
```
 200
```
