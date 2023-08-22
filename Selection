#include<stdio.h>
#include<stdio.h>
void selection_sort(int a[],int n)
{
	int i,j,m,temp,cnt=0;
	for(i=0;i<n-1;i++)
	{
		m=i;
		for(j=i+1;j<n;j++)
		{
			if(a[j]<a[m])
			m=j;
			cnt++;
		}
		temp=a[i];
		a[i]=a[m];
		a[m]=temp;
	}
	printf("the sorted arrays are:\n");
	for(i=0;i<n;i++)
	printf("%d\t",a[i]);
	printf("the num of times basic operaion is %d",cnt);
}
int main()
{
	int n,i;
	int *a;
	printf("the n value\n");
	scanf("%d",&n);
	a=(int*)calloc(n, sizeof(int));
	printf("enter the array values\n");
	for(i=0;i<n;i++)
	{
		scanf("%d",&a[i]);
	}
	selection_sort(a,n);
	return;
}
