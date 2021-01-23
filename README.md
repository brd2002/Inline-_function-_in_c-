# Inline-_function-_in_c++
#include<iostream>
using namespace std;
 class operation {
  int a,b,add,sub,mul;
  float div;
   public:
       void get();
       void sum();
       void difference();
       void product();
       void division();
 };
 inline void operation ::get()
 {
     cout<<"Enter First Value:";
     cin>>a;
     cout<<"Enter Second value:";
     cin >>b;
 } inline void operation ::sum()
 {
     add=a+b;
     cout<<"Addition is ="<<a+b<<"\n";
 }
 inline void operation:: difference()
 {
     sub =a-b;
     cout<<"Difference is :"<<a-b<<endl;
 } inline void operation :: product()
 {
     mul =a*b;
     cout<<" Product is :"<<mul<<"\n";
 }inline void operation:: division()
 {
     div =a/b;
     cout<<"Division is :"<<div;
 } int main()
 {
     cout<<"Programe using inline  function \n";
     operation s;
     s.get();
     s.sum();
     s.difference();
     s.product();
     s.division();
     return 0;
 }

  
