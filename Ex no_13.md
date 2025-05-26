# EX 13 To write a C program to replace all even elements by 0 and odd by 1 in one dimensional array
## AIM:
To write a C program to replace all even elements by 0 and odd by 1 in one dimensional array

## Algorithm
1. Read the number of elements and the array elements.
2. Loop through each element of the array.
3. If an element is even, replace it with 0.
4. If an element is odd, replace it with 1.
5. Print the modified array.
  

## Program:
```
/*
Program to replace all even elements by 0 and odd by 1 in one dimensional array
Developed by: Mariam Sherin
RegisterNumber:  212222060143
#include<stdio.h>
int main()
{
    int n;
    scanf("%d",&n);
    int arr[n];
    for(int i=0;i<n;i++){
        scanf("%d",&arr[i]);
    }
    for(int i=0;i<n;i++){
        if(arr[i]%2==0){
            printf("0 ");
        }else{
            printf("1 ");
        }
    }
}
*/
```

## Output:

![image](https://github.com/user-attachments/assets/fc175654-2dcf-4688-9792-592ea3dc9416)


## Result:
Thus the program was executed and the output was verified successfully.
