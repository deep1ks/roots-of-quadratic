# roots-of-quadratic
when we will input coefficients of quadratic equation it will give me roots of quadratic
#include<iostream>
#include<math.h>
using namespace std;
int main()
{
	
 double  a,b,c,d,x,y,sum_roots,product_roots;
cout<<"enter three coefficients of quadratic equation a,b,c"<<endl;
cin>>a>>b>>c;
d=b*b-4*a*c;
x=(-b+pow(d,0.5))/(2*a);
y=(-b-pow(d,0.5))/(2*a)	;
sum_roots=-b/a;
product_roots=c/a;
float e=x+y;
float f=x*y;
	
cout<<"root1="<<x<<"  root2="<<y<<endl;
cout<<"sum of roots="<<sum_roots<<"  product of roots="<<product_roots<<endl;	
cout<<e<<endl;
cout<<f<<endl;	
	
	
	
	
	
	
	
return 0;	
}
