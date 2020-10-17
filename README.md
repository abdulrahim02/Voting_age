# Voting_age
Created by Abdulrahim Mulla


//Voting_age
#include <iostream>
using namespace std;
 
int main()
{
	int age=0;
	char n;
	
	cout<<"Enter the name : ";
 	cin>>n;
 	
	cout<<"Enter the Age of Candidate : ";
 	cin>>age;
 	
 		if(age>= 18)
 		{
 			cout<<"\n You can Vote :)";
		}
		else
		{
			cout<<"\n You can't Vote :(";
		}
	
	return 0;
}
