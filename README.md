# c-2
#include<stdio.h>
int main()
{
	int num,sum=0,temp,digit;
	printf("enter the value:");
	scanf("%d",&num);
	temp=num;
	while(temp>0){
		digit=temp%10;
		sum+=digit;
		temp/=10;
	}
	if(num%sum==0){
		printf("%d is nivens number \n",num);
	}else{
		printf("%d is not nivens number \n",num);
	}
	return 0;
}
