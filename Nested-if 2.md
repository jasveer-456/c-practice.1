#  Task : Login System

###  Problem:

Declare:

```c
int password = 1234;
int otp = 5678;
```

Conditions:

* If password is correct (1234)

  * Then check if OTP is correct (5678)

    * Print `"Login Successful"`
    * Otherwise print `"Wrong OTP"`
* Otherwise print `"Wrong Password"`
## source code
```
#include  <stdio.h>

int main(){
	int password = 1234;
    int otp = 5678;
    if(password=1234)
    {
    	if(otp=5678)
    	{
    		printf("Login Successful");
		}
		else
		printf("Wrong OTP");
	}
	else
	printf("Wrong Password");
}
```

---

## Output
```
Login Successful
```
