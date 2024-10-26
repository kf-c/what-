# what-
i don't want to open my mouth now.
#include<stdio.h>
int main()
{
	int a=10;
	int *p=&a;
	int **q=&p;
	int ***r=&q;
	
	printf("Address of a=%u\n",&a);
	printf("Address of a=%u\n",p);
	printf("Address of p=%u\n",&p);
	printf("Address of p=%u\n",q);
	printf("Address of q=%u\n",&q);
	printf("Address of q=%u\n",r);
	
	printf("Value of a=%d\n",a);
}
