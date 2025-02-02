#include<iostream>
#include<string>

using namespace std;

class car{
private:

string brand;
string model;
float price;
int mileage;

public:
//initiate data members
car(string b,string m,float p,int mil){

brand=b;
model=m;
price=p;
mileage=mil;}

//function to display car details
void display()
{
cout<<"brand"<<brand<<endl;
cout<<"model"<<model<<endl;
cout<<"price"<<price<<endl;
cout<<"mileage<<mileage<<endl;
}
//function to update mileage when car is driven
void drive (int distance){
mileage+=distance
cout<<"update mileage:"<<mileage<<"miles"<<endl;
}
};
int main(){
//creating a car object
car mycar("toyota","corolla",20000,5000);

//display car details
mycar.display();

//simulate driving the car for 150 miles
mycar.drive(150);

//simulate driving the car for 300 miles
mycar.drive(300);

return 0;
}


