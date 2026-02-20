## Task  — Vowel or Consonant

Write a program that:

* Takes a character input
* Uses `switch` to check whether it is a vowel or consonant.

---

## Source code
```
#include <stdio.h>

int main(){
	char ch='e';
	switch (ch){
		case'a':
		case'e':
		case'i':
		case'o':
		case'u':
			printf("vowel");
			break;		
		default:
			printf("consonant");		
	}
}
```

---

## Output
```
vowel
```
