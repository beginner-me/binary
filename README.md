# binary
binary conversion
/*12. Write a program that shows the binary equivalent of a given positive number between 0 to 255.*/
#include<stdio.h>
int main()
{   
    int a,i;
    int array[6];
	printf("Enter a number between 0 to 255 ");
	scanf("%d",&a);
	for (i=0;i<5;i++)// for loop for dividing each number by 2 and finding remainder
	{
		array[i]=a%2;
		a=a/2;
		printf("%d",array[i]);
		
		
	}
	 for (int i = 4; i >= 0; i--) {     
        printf(" %d ",array[i]);  }
	
}
