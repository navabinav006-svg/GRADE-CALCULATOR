#include <stdio.h>

int main(void) {
    float score;

    printf("Enter your score (0-100): ");
    scanf("%f", &score);

    if (score < 0 || score > 100) {
        printf("Invalid score. Enter a number from 0 to 100.\n");
    } else if (score >= 90) {
        printf("Grade: A\n");
    } else if (score 
