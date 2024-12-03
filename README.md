# Ovsiyenko_lab1

#include <iostream>
using namespace std;

int main(){
    
    int year;
    cout<<"Введіть рік:";
    cin>>year;
    
    if(year%4==0 && (year%100!=0 || year%400==0)){
        cout<<year<<"-є високосним роком!"<<endl;
    }
    
    else{
        cout<<year<<"-не є високосним роком!"<<endl;
    }

    return 0;
}
