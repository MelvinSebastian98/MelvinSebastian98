#include<iostream>
using namespace std;
void main()
{int v[100];h[100];
 int vSize;int hSize;
 cout<<"Timings of Vettel";
 cin>>v[];
 cout<<"Timings of Hamilton";
 cin>>h[];
 int vSize = sizeof(v)/sizeof(v[0]);
 int hSize = sizeof(h)/sizeof(h[0]);
if (vSize>hSize){
int n=vSize;}
else if (hSize>vSize){
int n=hSize;}
else{ int n=vSize;}
int vm=0;
int hm=0;
for (int i=0;i<n;i++)
 {if(v[i]>h[i])
  {int vm=vm+10;
  int hm=hm-2;}
  else if(h[i]>v[i])
  {int hm=hm+10;
  int vm=vm-2;}
  else if(v[i]==h[i])
  {int vm=vm;
  int hm=hm;}}
 if(vm>hm)
 {cout<<"Vettel : "<<vm<<" points";
 cout<<"Hamilton : "<<hm<<" points";}
 else  if(vm>hm)
 {cout<<"Hamilton : "<<hm<<" points";
 cout<<"Vettel : "<<vm<<" points";}
 }
