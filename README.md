# Print-multiplication-table-of-a-number
Using C language program is made which gives the output to print multiplication table of a number
#include <stdio.h>
int main() {
    int n, i = 1;
    scanf("%d", &n);
    while(i <= 10) {
        printf("%d x %d = %d\n", n, i, n*i);
        i++;
    }
    return 0;
}
