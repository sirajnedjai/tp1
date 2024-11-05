1_)#include <stdio.h>

int main() {
int i,j;
    char T[5][5] = {
        {'1', '2', '3', '4', '5'},
        {'7', 'a', 'c', '8', 'd'},
        {'c', '9', 'z', 'z', '8'},
        {'5', '6', 'p', '3', 'k'},
        {'2', '9', 't', 'm', 'k'}
    };
    for ( i = 0; i < 5; i++) {
        for ( j = 0; j < 5; j++) {
            printf("%d ", T[i][j]);
        }
        printf("\n");
    }

    printf("matrix row pair:\n");
        for (i = 0; i < 5; i += 2) {
            for (j = 0; j < 5; j++) {
                printf("%d \t", T[i][j]);
            }
            printf("\n");
        }

    printf("matrix column impair:\n");
        for (i = 0; i < 5; i++) {
            for (j = 0; j < 5; j += 2) {
                printf("%d \t ", T[i][j]);
            }
            printf("\n");
        }
    return 0;
}