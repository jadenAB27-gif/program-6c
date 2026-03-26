# program-6c
C module 6
EXP.No:6c-Area of triagnle using pointers.

Date: 26/03/26
Name: JADEN SAMUEL ABRAHAM
Ref no: 25003451

AIM:
To write a C program to find the area of a triangle using pointers.

ALGORITHM:
1) Get the height and base of the triangle as input from the user.
2) assign pointers to the variables.
3) find the area of the triangle using those pointers.
4) print the result using printf() function.

PROGRAM:
```
#include <stdio.h>

int main() {
    float base, height, area;
    float *b, *h, *a;

    // Assigning addresses
    b = &base;
    h = &height;
    a = &area;

    // Input base and height
    printf("Enter the base of the triangle: ");
    scanf("%f", b);

    printf("Enter the height of the triangle: ");
    scanf("%f", h);

    // Calculate area using pointers
    *a = 0.5 * (*b) * (*h);

    // Display result
    printf("\nArea of the triangle = %.2f\n", *a);

    return 0;
}
```
OUTPUT:

Enter the base of the triangle: 10
Enter the height of the triangle: 5

Area of the triangle = 25.00


RESULT:
Thus the C program to find the area of a triangle using pointers is executed successfully.
















