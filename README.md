# C-programming-use-into-sequence-printing

#include<stdio.h>
int main()
{
    int i, j, n, k;
    scanf("%d", &n);

    i = 1;
    while(i <= n)
    {
        j = 1;
        while(j <= n){
            k = 1;
            while(k <= n){


                printf("%d %d %d", i, j, k);
                printf("\n");
                k++;
            }

            j++;

        }

         printf("\n");

       i++;
    }

   return 0;
}
