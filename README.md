#include <stdio.h>

int main(void)
{
    char animal[10];
    char why[70];
    printf("좋아하는 동물 : ");
    scanf("%s", animal);
    fgets(stdin);
    printf("좋아하는 이유 : ");
    fgets(why, sizeof(why), stdin);
    printf("%s is %s", animal, why);
    return 0;
}
