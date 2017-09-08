# stl-algoritham
#include<iostream.h>
#include<conio.h>
#include<algoritham>
#define size 10
int main()
{
int n,item;
int array[size],i;
cout<<"how many elements you want to enter:";
cin>>n;
int*limit=array+n;
cout<<"enter numbers":;
for(i=0;i<n;i++)
{
cin>>item;
array[i]=item;
sort(array,limit);
cout<<"\n sorted list :";
for(i=0;i<n;i++)
cout<<array[i]<<'\t';
cout<<endl;
getch();
}
