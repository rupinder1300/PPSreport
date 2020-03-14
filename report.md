![gne](https://raw.githubusercontent.com/rupinder1300/PPSreport/master/rk.jpg)
# Programming For Problem Solving (ESC-105)
------
Submitted By: Rupinder kaur

Class Roll no: 1916064

University Roll no: 1905146

Branch: Electrical

Section: B

Batch:2019-2023

-------

            Experiment No: 1
Write a code to print name of the collage.
```C
#include<stdio.h>
int main();
{
puts("Welcome you in gndec");
}
```

Experiment No: 2
Desing a code to execute addtion of two number.
```C
#include<stdio.h>
int main()
{
int a,b,c;
printf("enter the value of a:" );
scanf("%d",&a);
printf("enter the value of b :");
scanf("%d",&b);
c=a+b;
printf("c:%d",c);
}
```

Experiment No:3
Write a C program to compute the perimeter and area of a rectangle with a
 height of 7 inches and width of 5 inches.
```C

#include <stdio.h>
int main(void)
{
    int a,b,perimeter,area;
    printf("enter the numbers:");
    scanf("%d%d", &a, &b);
    perimeter=2*(a+b);
    printf("perimeter of the rectangle: %d inches",perimeter);
    area=a*b;
    printf("\narea of the rectangle: %d square inches", area);
    return 0;
}
```

Experiment No. 4
Design a code to execute addition of two numbers if the sum is even.
```C

#include<stdio.h>
#include<math.h>
int main()
{
    int a,b,sum;
    printf("enter the value of a and b :");
    scanf("%d %d", &a,&b);
    sum=a+b;
    if(sum%2==0)
    {
    printf("Even");
    }
    else
    {
        printf("Odd");
        
    }
    
}
```

Experiment No. 5
Write a C program to print big'C'. 
```C
#include<stdio.h>
int main () 
{
    puts(" ######");
    puts("##    ##");
    puts("#");
    puts("#");
    puts("#");
    puts("#"); 
    puts("#");
    puts("##    ##");
    puts(" ######");
    return(0);
} 
  ```
