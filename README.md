#include <iostream>
using namespace std;
int main()
{
       int a=5,b=10,temp;
       cout<<"Before swapping." <<end1;
       cout<<"a=" <<a<<", b=" <<b<<end1;
       temp=a;
       a=b;
       b=temp;
       cout<<"\n After swapping," <<end1;
       cout<<"a=" <<a<<", b=" <<b<<end1;
       return 0;
} 

#include<iostream>
using namespace std;
int main() 
{
  float n1, n2, n3;

  cout<<"Enter three numbers:" ;
  cin>>n1>>n2>>n3;

  if(n1>=n2 & & n1>=n3) 
     cout<<"Largest number:" <<n1;
     
  if(n2>=n1 & & n2>=n3) 
     cout<<"Largest number:" <<n2;
   
  if(n3>=n1 & & n3>=n2) 
    cout<<"Largest number:" <<n3;

  return 0;
}

#include <iostream>
using namespace std;

int main() 
{
   int year;

   cout<<"Enter a year:" ;
   cin>>year;

   if(year % 4 == 0)
   {
     if(year % 100 == 0)
     {
       if(year % 400 == 0)
          cout<<year<<"is a leap year" ;
       else
          cout<<year<<"is not a leap year" ;
     } 
     else
         cout<<year<<"is a lesp year" ;
   } 
    else
        cout<<year<<"is not a leap year" ;

    return 0;
}
  

