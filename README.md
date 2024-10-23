# To-find-Power-value
#include <stdio.h>

int main() {
    int a, b;
    int r = 1;

    scanf("%d", &a);
    scanf("%d", &b);

    

    while (b != 0) {
        r *= a;
        --b;
    }

    printf("%d\n", r);

    return 0;
}

