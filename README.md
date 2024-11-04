1_)#include <stdio.h>

int main() {
int i,j;
    char S[4][5] = {
        {'1', '2', '3', '4', '5'},
        {'7', 'a', 'c', '8', 'd'},
        {'c', '9', 'z', 'z', '8'},
        {'5', '6', 'p', '3', 'k'}
    };
    for ( i = 0; i < 4; i++) {
        for ( j = 0; j < 5; j++) {
            printf("%c ", S[i][j]);
        }
        printf("\n");
    }

    return 0;
}



2_)#include<stdio.h>
int main(){
    int T[5],i,j;
    printf("matrix row pair:\n");
        for (i = 1; i < 4; i += 2) {
            for (j = 0; j < 5; j++) {
                printf("%c ", T[i][j]);
            }
            printf("\n");
        }
    return 0;
}



3_)#include<stdio.h>
int main(){
int T[5],i,j;
printf("matrix row pair:\n");
    for (i = 1; i < 4; i++) {
        for (j = 0; j < 5; j += 2) {
            printf("%c ", T[i][j]);
        }
        printf("\n");
    }
    return 0;
}