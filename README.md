# Area-of-a-circle-

#include <stdio.h>

int main()
{

    float radius;                                                     
    float area;

    printf ("Compute area of a circle: \n");                        //Display Compute area of a cicle 
    printf ("---------------------------------------- \n");         
    printf ("Enter the radius: ");                                 // Prompt the user to enter the radius:
    scanf ("%f", &radius);                                         // Read the entered value
    area = 3.14 * radius * radius;                                // Compute the area
    printf ("Area of the circle =  %f\n", area);                  // To display area of the circle to the screen

    return 0;
}

