#include <stdio.h>

int main() {
    int original_marks[25], revised_marks[25];
    int birth_month[25], i;
    float original_avg, revised_avg;
    printf("Enter the original marks of 25 students:\n");
    for (i = 0; i < 25; i++) {
        scanf("%d", &original_marks[i]);
    }
    printf("Enter the birth months of 25 students:\n");
    for (i = 0; i < 25; i++) {
        scanf("%d", &birth_month[i]);
    }
    for (i = 0; i < 25; i++) {
        revised_marks[i] = original_marks[i] + birth_month[i];
    }
    revised_avg = 0;
    for (i = 0; i < 25; i++) {
        revised_avg += revised_marks[i];
    }
    revised_avg /= 25;
    original_avg = 0;
    for (i = 0; i < 25; i++) {
        original_avg += original_marks[i];
    }
    original_avg /= 25;
    if (revised_avg - original_avg >= 5) {
        printf("Can implement - Significant increase in class average.\n");
    } else {
        printf("Need not implement - No significant increase in class average.\n");
    }

    return 0;
}
