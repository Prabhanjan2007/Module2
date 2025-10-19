# Module2
# day 1
Get N from the user as input. Write a C Program to print the sum of N numbers using float data type.
# program 
#include <stdio.h>
```
#include<stdio.h>
int main()
{
  int a,i;
  float b;
  b=0.0;
  scanf("%d",&a);
  for(i=1;i<=a;i++)
  {
      b+=i;
  }
  printf("Sum=%.1f",b);
  return 0;
}
```
# output
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/0c4f6c82-8ec0-418f-ac26-b8acdf2e618d" />


# day 2
Write a C program to print equilateral triangle or pyramid star pattern
# program
```
#include<stdio.h>
int main()
{
    int a,i,j;
    scanf("%d",&a);
    for(i=1;i<=a;i++)
    {
        for(j=1;j<=a-i;j++)
        {
            printf(" ");
        }
        for(j=1;j<=2*i-1;j++)
        {
            printf("#");
        }
        printf("\n");
    }
    return 0;
}
```
# output
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/6d6f7380-0e80-49cf-b101-fc58b62b14cb" />

# day 3
Write a C program for finding the factorial of a given number using function without return type with arguments.
# program
```
#include<stdio.h>
void fact(double a);
void fact(double a)
{
    double v=1,i;
    for(i=a;i>=1;i--)
    {
        v*=i;
    }
    printf("Factorial value is: %.0lf",v);
}
int main()
{
    double x;
    scanf("%lf",&x);
    fact(x);
    return 0;
}
```
# output
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/802bc196-5fce-47ce-a6d7-9e56f9828f24" />

# day 4
Write a C program to display n (input from user) number of multiplication table vertically using for loop?
# program
```
#include<stdio.h>
int main()
{
    int a,i,j;
    scanf("%d",&a);
    for(i=1;i<=a;i++)
    {
        for(j=1;j<=a;j++)
        {
            printf("%d ",i*j);
        }
        printf("\n");
    }
    return 0;
}
```
# output
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/05c01c6f-4b74-47e5-b224-51e68ccbfaa0" />

# day 4
Write a C program for the following pattern?
# program
```
#include<stdio.h>
#include<stdlib.h>
int main()
{
    int a=13,i,j;
    for(i=1;i<=a;i++)
    {
        for(j=1;j<=2*i-1;j++)
        {
            if(j!=i)
            printf("%d ",a-abs(i-j));
            else
            printf("%d ",0);
        }
        printf("\n");
    }
    return 0;
}
```
# output
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/921a6ee7-b929-475d-abd9-fc0690c55b62" />
