# EX 9 C program to find the sum of odd digits using do while loop.
## DATE:
## AIM:
To write a C program to find the sum of odd digits using do while loop.

## Algorithm
1.Read an integer input (a) from the user.
2.Initialize sum as 0 and i as 1.
3.Use a do-while loop to iterate from i = 1 to a, adding odd numbers to sum.
4.Increment i in each iteration. 
5.Print the final sum of odd numbers.  

## Program:
```
#include <stdio.h>
int main()
{
    int i=1,a,sum=0;
    scanf("%d",&a);
    do{
        if(i%2!=0)
        {sum=sum+i;}
        i++;
        
    }while(i<=a);
    printf("%d",sum);
    return 0;
}
```

## Output:

![image](https://github.com/user-attachments/assets/61ea3225-5311-4abb-967c-8534efed0617)

## Result:
Thus the program was executed and the output was verified successfully.
