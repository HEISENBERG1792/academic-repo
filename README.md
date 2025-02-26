#include<stdio.h>
int main(){
    int garden_length;
    int garden_width;
    int road_width;
 printf("Enter the width of the garden: ");
    scanf("%d", &garden_width);
    printf("\nEnter the length of the garden: ");
    scanf("%d", &garden_length);
    printf("\nEnter the width of the road surrounding the garden: ");
    scanf("%d", &road_width);

    int garden_area;
    garden_area = garden_length * garden_width;

    int total_length;
    int total_width;

    total_length = garden_length + (2 * road_width);
    total_width = garden_width + road_width + road_width;

    int total_area;
    total_area = total_length * total_width;

    printf("\nThe garden area is: %d", garden_area);
    printf("\nThe total area covered by the garden and the surrounding road is: %d", total_area);
}
