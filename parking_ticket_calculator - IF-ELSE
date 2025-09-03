#include <iostream>
using namespace std;

int main(){
    string vehicle;
    string car = "car";
    string bike = "bike"; 
    string truck = "truck";
    int hours;
    cout<<"Enter type of vehicle: car/bike/truck \n";
    cin>>vehicle;
  

    if (vehicle == car){
        cout<<"2$ for first hour, 1.5$ per additional hours \n";
        cout<<"Enter how many hours car parked?:            ";
        cin>>hours;
        if ( hours> 1){
            cout<<"You have to pay "<<2+(1.5*(hours-1))<<"$";
        }
        else{
            cout<<"You have to pay 2$";
        }
    }
    else if ( vehicle == bike) {
        cout<<"1$ for first hour, 0.75$ per additional hours \n";
        cout<<"Enter how many hours Bike parked?:            ";
        cin>>hours;
        if ( hours> 1){
            cout<<"You have to pay "<<1+(0.75*(hours-1))<<"$";
        }
        else{
            cout<<"You have to pay 1$";
        }
    }
    else {
        cout<<"4$ for first hour, 3$ per additional hours \n";
        cout<<"Enter how many hours Truck parked?:            ";
        cin>>hours;
        if ( hours> 1){
            cout<<"You have to pay "<<4+(3*(hours-1))<<"$";
        }
        else{
            cout<<"You have to pay 4$";
        }
    }

}
