#include<iostream>
using namespace std;

int main() {
	int size = 5;
	int arr[size];
	int task;
	int index = -1;
	start:
		cout<<" 1. To insert data \n 2. To delete data \n 3. To display data \n";
	
	
	cout<<"Enter your task number that you want to perform"<<endl;
	cin>>task;
		
	if(task == 1) {
		cout<<"Enter the elements :"<<endl;
		for(int i = 0; i < 5; i++) {
			cin>>arr[i];
		}
		goto start;
	}
	
	else if(task == 2) {
		
		
		int elem;
		cout<<"Enter the element you want to delete : \n";
		cin>>elem;
		// Matching the entered element with the array elements
		for(int i = 0; i < size; i++) {
			if(arr[i] == elem) {		
	        	index = i;
				break;
	}
		}
		
		//Shifting the elements of array to left by position at every iteration, when condition is true
		
		if(index != -1) {
			for(int i = index; i < size -1; i++) {
				arr[i] = arr[i+1];
			}
			cout<<"New Array : ";
			for(int i = 0; i < size -1; i++) {
				cout<<arr[i] << " ";
			}
		}
		
		// It display in the case when no element is matched
		else 
		{
			cout<<"Given element was not found! \n";
		}
		
		cout<<"\n";
		
		goto start;
	}
	
	else if(task == 3) {
	cout<<"Your entered elements are :";
	for(int n = 0; n < 5; n++) {
		cout<<arr[n] << " ";
	}
	}


	return 0;	
}
