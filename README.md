// check-prime-or-not
#include <iostream>
#include <math.h>

using namespace std;

int main()
{   
    int n, val=0;
   cout<<"enter the number: ";
   cin>>n;
   for(int i=2;i<=sqrt(n);i++){
       if(n%i==0){
      
           val=1;
           break;
       }
       
   }
if(val==1){
cout<<"it is not a prime number";}
else cout<<"it is a prime number";
    return 0;
}
