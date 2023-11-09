# cprog
#include<stdio.h>
int main()
{
	int i,j,n=5;
	for(i=1;i<=n;i++)
	{
		for(j=1;j<=i;j++)
		{
			if(j==1)
			{
				printf("R");
			}
			if (j==2)
			{
				printf("G");
			}
			if (j==3)
			{
				printf("U");
			}
			if (j==4)
			{
				printf("K");
			}
			if (j==5)
			{
				printf("T");
			}
			else
				printf(" ");

		}
		printf("\n");
	}
}
