# First_Smester_Programs
Collection of my programming exercises and projects from my first semester

#include<iostream>
using namespace std;
int main(){
	int factorial =1;
	int num;
	cout <<"The number for fictorial is :"<< endl;
	cin >> num;
	for(int i = 1;i<=num;i++){
		factorial *=i; 
	}
	cout <<"The factprial of number is"<<factorial << endl;
	return 0;
}