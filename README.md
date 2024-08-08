# mini-project
#include<iostream>
using namespace std;
	int main(){
		char grade;
		int mathmatics,DSA,OOAD,CG,EDC,Sociology;
		cout<<".....................................................\n\n"<<endl;
		cout<<   "Enter your obtained marks in your subjects\n\n";
			cout<<"....................................................."<<endl;
			cout<<"Enter Mathmatics marks\n";
			cin>>mathmatics;
				cout<<"Enter DSA marks\n";
			cin>>DSA;
			cout<<"Enter OOAD marks\n";
			cin>>OOAD;
			cout<<"Enter CG marks\n";
			cin>>CG;
			cout<<"Enter EDC marks\n";
			cin>>EDC;
			cout<<"Enter Sociology marks\n";
			cin>>Sociology;
		float totalmarks=600;
		float total_obtained=mathmatics+DSA+OOAD+CG+EDC+Sociology;
		float percent=( total_obtained/totalmarks)*100;
	
	if(percent>=85){
	    grade='A';
        }
       	else if(percent>75 && percent<85){
       	grade='B' ;	
       }
       	else if(percent>55 && percent<75){
		   
		grade='C' ;	
	     }
      	else if(percent>35 && percent<55){
	  	grade='D' ;	
        }
        else {
        grade='E';
    	}
    	cout<<"\n Your total marks obtained in exam is: "<<total_obtained;
    		cout<<"\n"<<"Your total percent is :"<<percent<<"\n and \n";
    	if(grade=='A'){
    	 	cout<<"Your grade is 'A'\n";
    	}
else if(grade=='B'){
		cout<<"Your grade is 'B'\n";
	
}
else if(grade=='C'){
		cout<<"Your grade is 'C'\n";
	
}
else if(grade=='D'){
		cout<<"Your grade is 'D'\n";
	
}
else if(grade=='E'){
		cout<<"Your grade is 'E' and you are fail \n";
}
		return 0;
	}
