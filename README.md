# FACTORIAL-OF-A-NO



Online C compiler to run C program online
#include <stdio.h>

int main() {
    // Write C code here
    int i, fact=1, n;
    printf("ENTER A NO\n");
    scanf("%d", &n);
    for(i=2; i<=n; i++)
    {
        fact=fact*i;
    }
    printf("%d", fact);

    return 0;
}
