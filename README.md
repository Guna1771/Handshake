# Handshake
Finding the maximum number of handshakes 
#include<stdio.h>
int main()
{

	int num;
	scanf(ā%dā,&num);
	int total = num * (num-1) / 2;
	printf(ā%dā,total);
	return 0;
}
