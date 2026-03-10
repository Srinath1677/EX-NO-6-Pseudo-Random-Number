# EX-NO-6-Pseudo-Random-Number

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:
1. Start the program and import the required libraries.
2. Seed the random number generator using the current time(i.e) rand(time(0));
3. Get the number of randon number to generate.
4. Pass the value for number of iterations and print the numbers.
5. End the program.

# PROGRAM:
```c
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main() {
    int n;

    printf("Enter how many random numbers to generate: ");
    scanf("%d", &n);

    srand(time(0)); // Seed the random number generator

    printf("Generated Random Numbers:\n");
    for (int i = 0; i < n; i++) {
        printf("%d ", rand());
    }

    printf("\n");
    return 0;
}
```
# OUTPUT:
<img width="606" height="123" alt="Screenshot 2026-02-04 090631" src="https://github.com/user-attachments/assets/52f7be6a-03b2-4b71-81b7-c29debaa329a" />



# RESULT:

Thus the code is successfully executed
