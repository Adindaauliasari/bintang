#include "iostream"
  
using namespace std;

int main()

{

	int l=1, m=9, n=1;  
      
    for(l=1;l<=9;l++){
      	for(m=9;m>0;m--){
		    cout<<"*";
		  	for(n=1;n<l;n++){
		  	cout<<" ";	
			}	
		}
               
		cout<<endl;
	}  

}
