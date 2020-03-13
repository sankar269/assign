#include <stdio.h>

int factorial(int);
int combination(int, int);
int permutation(int, int);

int main()
{
    int n, r, c, p;
    printf("Enter the value of n :");
    scanf("%d", &n);

    printf("Enter the value of r :");
    scanf("%d", &r);

    c = combination(n, r);
    p = permutation(n, r);

    printf("\nCombinations : %d", c);
    printf("\nPermutations : %d", p);

    return 0;
}

int combination(int n, int r)
{
    int c;

    c = factorial(n) / (factorial(r) * factorial(n - r));

    return c;
}

int permutation(int n, int r)
{
    int p;

    p = factorial(n) / factorial(n - r);

    return p;
}

int factorial(int n)
{
    int i;
    int fact = 1;

    for (i = 1; i <= n; i++)
    {
        fact = fact * i;
    }
    return fact;
}
