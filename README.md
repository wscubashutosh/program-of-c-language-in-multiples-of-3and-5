# program-of-c-language-in-multiples-of-3and-5
#include <math.h>
#include <stdio.h>
#include <string.h>
#include <stdlib.h>
#include <assert.h>
#include <limits.h>
#include <stdbool.h>
int main()
{
    int t,b,c,j;
    scanf("%d",&t);
    for (b=0;b<t;b++)
    {
       int sum=0;
        j=3;
        scanf("%d",&c);
        while(j<c)
        {
            if((j%3==0)||(j%5==0))
            {
                sum+=j;
            }
            j++;
        }
        printf("%d\n",sum);
    }
    return 0;
}
