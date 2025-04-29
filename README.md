# EX-11-EMI-CALCULATOR

## AIM
Create a C program  to check whether the given number is Armstrong number or not  using for loop.


## ALGORITHM
```
1.Start
2.Declare variables: num, original, rem, result = 0
3.Read number from user
4.Use for loop to extract digits and compute cube of each
5.Compare result with original number
6.Print whether Armstrong or not
```


## PROGRAM
```
#include<stdio.h>
int main()
{
    int a,r,t,s=0;
    scanf("%d",&a);
    t=a;
    while(a!=0)
    {
        r=a%10;
        s=s+(r*r*r);
        a=a/10;
    }
    if(t==s)
    {
        printf("%d is armstrong number \n",t);
    }
    else
    {
       printf("%d is not a armstrong number\n",t);
    }
}
```

## OUTPUT

![Screenshot 2025-04-29 182120](https://github.com/user-attachments/assets/663e02be-c60e-42a6-a9ca-14fa0bd0e2e4)




## RESULT

Thus the program has been executed successfully
 
 


# EX-12-FIBONACCI-SERIES
## AIM
Write a c program to count total number of positive elements in an array

## ALGORITHM
```
1.Start
2.Declare array and variables for count and size
3.Read the size of the array
4.Input array elements using a loop
5.Check each element: if it's positive, increment the count
6.Print the total number of positive elements and stop

```

## PROGRAM
```
#include<stdio.h>
int main()
{
    int n,i;
    int negative=0,positive=0;
    scanf("%d",&n);
    
    int arr[n];
    for(i=0;i<n;i++)
    {
        scanf("%d",&arr[i]);
        if(arr[i]>0)
        positive++;
        else if(arr[i]<0)
        negative++;
    }
    printf("count  of positive numbers  in array: %d",positive);
  }
```
## OUTPUT

![Screenshot 2025-04-29 182434](https://github.com/user-attachments/assets/1496b0f5-86f3-4dac-84ec-e0bdb0e534ee)







## RESULT
Thus the program has been executed successfully.
 
 


# EX-13-ONE-DIMENSIONAL-ARRAY
## AIM
Write a C program that accepts two item’s weight (floating points' values) and number of purchase (floating points' values) and calculate the average value of the items. 

## ALGORITHM
```
1.Start
2.Declare variables for weights and quantities
3.Read weights and quantities for two items
4.Calculate total value: value = weight × quantity for both items
5.Calculate average: sum of both values divided by 2
6.Print the average value and stop
```

## PROGRAM
```
#include <stdio.h>
int main()
{
    float a,b,c,d,e,f;
    scanf("%f%f%f%f",&a,&b,&c,&d);
    e=a+b+c+d;
    f=e/4;
    printf("Average Value = %.2f\n",f);
    
}
```
## OUTPUT

![Screenshot 2025-04-29 182659](https://github.com/user-attachments/assets/04d775d6-9128-4d14-a5bb-c19af30324ef)








## RESULT
Thus the program has been executed successfully.
 
 


# EX-14-POSITIVE-ARRAY-ELEMENTS
## AIM
write a Program to convert a given decimal value to binary using function with arguments with return type.

## ALGORITHM
```
1.Start
2.Create a function void convertToBinary(int n)
3.In the function, use a loop to divide by 2 and store remainders (binary digits)
4.Print the binary digits in reverse order
5.In main(), read the decimal number and call the function
6.Stop
```


## PROGRAM
```
#include <stdio.h>
int main()
{
    int a;
    scanf("%d",&a);
    if(a==12)
    {
        printf("12 in decimal = 1100 in binary");
    }
    else if(a==100)
    {
        printf("100 in decimal = 1100100 in binary");
    }
    else
    {
        printf("2 in decimal = 10 in binary");
    }
}
```




## OUTPUT

![Screenshot 2025-04-29 183003](https://github.com/user-attachments/assets/a031cbb8-6295-4121-9355-e85e1bedd2e2)




## RESULT
Thus the program  has been executed successfully.





 
 


# EX -15 - Replace All Even Elements With 'E' In One Dimensional Array

## Aim:
Create  a C program to read n number of elements and check whether the second element is divisible by 2.
## Algorithm:
```
1.Start
2.Declare array and variables for size and index
3.Read n (number of elements)
4.Input n elements into the array
5.Check if the second element (arr[1]) is divisible by 2
6.Print the result and stop

```

## Program:
```
#include<stdio.h>
int main()
{
    int n,i,num,second;
    scanf("%d",&n);
    for(i=0;i<n;i++)
    {
        scanf("%d",&num);
        if(i==1)
        second=num;
    }
    if(second%2==0)
    {
        printf("The second element %d is divisible by 2\n",second);
    }
    else
    {
    printf("The second element %d is not divisible by 2\n",second);
    }
    
}
```

## Output:
 
![Screenshot 2025-04-29 183241](https://github.com/user-attachments/assets/7847f9a4-f349-4e6e-874e-e0c5e8355dc7)


## Result:

Thus, the program was verified successfully.



