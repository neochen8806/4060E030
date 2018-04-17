
###### exercise1 矩陣相加

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

###### exercise2 矩陣相乘

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
c[i][j] = a[i][j]*b[i][j];
printf("%5d",c[i][j]);
}
printf("\n");
}
return 0;
}

```

###### exercise_array

```
#include <iostream>
using namespace std;
int main()
{
	cout << "2018.04.17" << endl;
	
	int i,a[10],b=1;

	for(i=0;i<10;i++)
	{
		a[i]=b;
		b++;
    }

	for(i=0;i<10;i++)
		cout << a[i] << endl;
		
    return 0;
}
```
![result](PIC/array.PNG)

###### exercise

```

```

###### exercise

```

```

###### exercise

```

```

###### exercise

```

```

###### exercise

```

```

###### exercise

```

```

###### exercise

```

```

###### exercise

```

```

###### exercise

```

```

###### exercise

```

```

###### exercise

```

```

###### exercise

```

```

###### exercise

```

```

###### exercise

```

```

