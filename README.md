# EX-NO-6-Pseudo-Random-Number

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

## ALGORITHM:

1.Start the program and import the required libraries.
2.Seed the random number generator using the current time (i.e) rand(time(0));
3.Get the number of random numbers to generate.
4.Pass the value for number of iterations and print the numbers.
5.End the program.

## PROGRAM:
```
#include <stdio.h>
#include <stdlib.h>
#include <time.h>
int main()
{
printf("Code by:Melkin sam - 212223220056\n");

int count, min, max;
printf("Enter the number of random numbers to generate: ");
scanf("%d", &count);
printf("Enter the minim
um value: ");
scanf("%d", &min);
printf("Enter the maximum value: ");
scanf("%d", &max);
srand(time(NULL));

printf("Pseudorandom numbers:\n");

for (int i = 0; i < count; i++)
{
int random_number = (rand() % (max - min + 1)) + min;
printf("%d\n", random_number);
}
return 0;
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/5960b7cc-4867-43be-8342-db60471629bf)

## RESULT:
The Implementation of Pseudorandom Number Generation Using Standard library is
successful.

