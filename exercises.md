
###### exercise1

```
#include <stdio.h>
int main(void)
{
int i,j;
int a[3][3],b[3][3],c[3][3];
printf("please input the array for a:\n"); 
for(i = 0; i < 3; i++)
{
for(j = 0; j < 3; j++)
{
scanf("%d",&a[i][j]);
}
}
printf("please input the array for b:\n"); 
for(i = 0; i < 3; i++)
{
for(j = 0; j < 3; j++)
{
scanf("%d",&b[i][j]);
}
}
printf("now the array c is :\n");
for(i = 0; i < 3; i++)
{
for(j = 0; j < 3; j++)
{
c[i][j] = a[i][j]+b[i][j];
printf("%5d",c[i][j]);
}
printf("\n");
}
return 0;
}

```

###### exercise2

```


```
