swap 4 numbers without temp variable 

public static void main(String[] args){
int a=10;
int b=20;
int c=30;
int d=40;
int e;
e=a+b+c+d 
a=e-(a+b+c);
b=e-(a+b+c);
c=e-(a+b+c);
d=e-(a+b+c);
System.out.println(a);
System.out.println(b);
System.out.println(c);
System.out.println(d);
}
