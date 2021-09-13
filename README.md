# shpargalka

#include <stdio.h>


int main(){
	//переменная

	int a;
	int b = 32;
	
	char c;
	char d = 'g';

	unsigned char a1;
	unsigned char a2 = 15;

	short s1;
	short s2 = -32767;

	unsigned short un1;
	unsigned short un2 = 65;

	unsigned int uni1;
	unsigned int uni2 = 5689;

	long l1;
	long l2 = -2145812;

	unsigned long unl1;
	unsigned long unl2 = 5854265;

	float f1;
	float f2 = 5.256;

	double d1;
	double d2 = -18.15486;

	long double ld1;
	long double ld2 = -5689.15846;
	



	a = 5;		a1 = 28;	s1 = 5689;	un1 = 59;	uni1 = 134679;	l1 = -56895689;	unl1 = 789461;	f1 = 48.456;	d1 = 56.159753;	 ld1 = 5689.15846;
	c = 588;

	printf("%d %d \n", a, b);
	printf("%d %d %d %d %d %d %f %f %f \n", a1, s1, un1, uni1, l1, unl1, f1, d1, ld1);


	return 0;
}
