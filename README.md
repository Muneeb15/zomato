# zomato
#include<iostream>
using namespace std;
int main()
{
	for(int i=1;i<=10;i++){
	
	//int b;
	
	int b=i*i;
	if(i==5){
		continue;
	}
	cout<<b<<endl;}
	
    cout<<"using while loop"<<endl;
    
int i=1;
while(i<=10)
  	if(i==5){
  			i++;
	  continue;
	  
  
  }
  	else{
  		int b=i*i;
  	i++;
  	cout<<b<<endl;
	  
	  }
  	
  cout<<"using dowhile loop"<<endl;
i=1;
do
{
  if(i==5)
  {
  i++;
  continue;
}
else{
int b=i*i;
cout<<b<<endl;
i++;}
  }
  	while(i<=10);
  return 0;
}
  
