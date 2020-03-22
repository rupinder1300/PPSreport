![gne](https://raw.githubusercontent.com/rupinder1300/PPSreport/master/rk.jpg)
# Programming For Problem Solving (ESC-105)
------
Submitted By: Rupinder kaur

Class Roll no: 1916064

University Roll no: 1905146

Branch: Electrical Engineering

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

            Experiment No: 4
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

           Experiment No: 5
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

             Experiment No:6
Write a computer program in C, which takes two numbers (integers) as input and print the smaller number.
```C
#include<stdio.h>
void main()
{
    int a,b;
    a=1000;
    b=250;
    if(a<b)
    {printf("%d",a);}
        else
        {printf("%d",b);}
}
```

            Experiment No:7 

```C 
#include<stdio.h>
int main()
{
    puts("########");
    puts("########     ####");
    puts("        ####");
    puts("##       ####");
    puts("####    ###");
    puts("###");
    puts("##       ####");
    puts("####       ###  ###");
    puts("######   ####");
    puts("####         ####");
    puts("##       ####");
    puts("####       ###  ###");
    puts("##       ####");
    puts("####     ###      ###");
    puts("##");
    puts("########     ####");
    puts("      ####");
}
``` 

            Experiment No:8 
Write a code to print table of any number. 
```C 
#include <stdio.h>
int main() {
    int n, i;
    printf("Enter an integer: ");
    scanf("%d", &n);
    for (i = 1; i <= 10; ++i) {
        printf("%d * %d = %d \n", n, i, n * i);
    }
    return 0;
} 
``` 
   
            Experiment No:9
Write a C program to print the following character in a reverse way without using any predefined function and header file 
```C 
#include<stdio.h>
#include<string.h>

int main()
{
char Str[100], RevStr[100];
int i, j, len;

printf("\n Enter a string to reverse:");
scanf("%s",Str);
j=0;
len = strlen(Str);
for (i = len-1;i>=0; i--)
{
    RevStr[j++] = Str[i];
}
RevStr[i] = '\0';

printf("Reverse of the string is: %s\n",RevStr);

return 0;
} 
``` 

             Experiment No:10  
Write a code to convert temperature from Fahrenheit scale to centigrade scale. 
```C
#include<stdio.h>
#include<math.h>

int main()
{
    float fr,cent;

    printf("enter the temprature in fahrenheit:");
    
    scanf("%f",&fr);
    cent= 5/9*(fr-32);
    printf("temprature in centigrade : %f",cent);
return(0);
} 
``` 

             Experiment No:11
Problem: Design a code to mark 'Present' if student entered in a hall before 8:35 and
marked 'Late' before 8:45 otherwise marked 'Absent'. 
```C 
#include<stdio.h>
int main()
{
    float time;
    scanf("%f", &time);
    if(time>8.14 && time<8.36)
    printf("Present");
    else
    {
        if(time>=8.36 && time<=8.45)
        printf("Late");
        else
    {
if(time>8.45 && time<9.00)
printf( "Absent");
else
{
    if(time==8.00 && time<=8.14)
    printf(" Sorry Gate Closed");
    else
{
    if(time>7.00 && time<8.00)
    printf(" You Entered Wrong Time");
    else
    {
        if(time>=9.00)
        printf(" Sorry Gate Closed");
        else
        {
            if(time>=1.00 && time< 7.00)
            printf(" Wrong Timing");
        }
    }
}
}
}
}
}
 ``` 

            Experiment No:12 
Write a code to find the factorial of a number 
```C
#include<stdio.h>
long factorial (int);
int main()
{
    int x;
    long fact =1;
    printf(" \n Enter a number to calculate it's factorial :");
    scanf(" %d", &x);
    printf(" %d! = %1d\n",x,factorial (x));
    return 0;
}

long factorial (int x )
{
    int c;
    long ans =1;
    for (c = x; c> 1; c--)
    { ans *= c; }
    return ans;
}  
``` 

            Experiment No:13 
Write a code to display the number is prime 
```C
#include<stdio.h>
int main()
{
    int a;
    printf(" \n Enter the Number :");
    scanf("%d",&a);
    
    for (int x=1;x<a;x++)
    
    {        if(a % x==0)
        {
            printf("%d is a Prime Number ",a);
            break;
        } 
        else
        {
            printf("%d is not a Prime Number",a);
            break;
        }
    }
    return 0;
}  
```  

              Experiment No:14 
Write a program to swap two numbers using a temporary variable. 
```C
#include<stdio.h>
void swap ( int*,int*);
int main()
{
    int x,y;
    printf("\n Enter the two integers :");
    scanf("%d %d",&x,&y);
    printf(" \nBefore Swapping \nx = %d \ny =%d ",x,y);
    swap (&x,&y);
    printf(" \n After swapping \nx = %d \ny  %d",x,y);
    return 0; 
}

void swap (int*a,int*b)  
{
    int temp;
    temp = *b;
    *b = *a;
    *a = temp;
} 
``` 

             Experiment No:15 
Write a code to print table between range i.e table 6 to 9. 
```C 
#include<stdio.h>
#include<math.h>
int main()
{
    int n,i,j,m; 
scanf(" %d %d",&m,&n);
for(i=m;i<=n;i++)
{
    for(j=1;j<=10;j++)
    {
        printf( " \n%d x %d=%d", i,j,i*j);
    }
    printf(" \n-------------");
}
}  
``` 
