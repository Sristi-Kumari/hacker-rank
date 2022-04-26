#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>

int main() {
    float kilometers,meters,feet,inches,centimeters;
    scanf("%f",&kilometers);
    meters=kilometers*1000;
    feet=kilometers*3280.84;
    inches=kilometers*39370.1;
    centimeters=kilometers*100000;
    printf("%0.2f m",meters);
    printf("\n%0.2f ft",feet);
    printf("\n%0.2f in",inches);
    printf("\n%0.2f cm",centimeters); 
    return 0;
}
