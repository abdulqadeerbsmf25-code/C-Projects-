# C++ -Projects-

" Prime Number "

#include <iostream>
using namespace std;
int main(){
	
  int num;
  do{
  cout<<"Please enter the number\n";
  
  cout<<"Please enter 0 to exit\n";
 
  cin>>num;
 
  bool is_prime = true;
 
 for(int i=2;i<num;i++){
  	
	  if(num%i==0){
 		
		 is_prime = false;
 		
		 break;
	 
	 }	
 }
 if(num!=0){
 
 if(is_prime)cout<<"The number is prime\n";
 
 else cout<<"The number is not prime\n";}
 
 }while(num!=0);
	return 0;
}
