#include<iostream>
using namespace std;
int main()
{
    float num1 , num2;

     cout<<"Enter first operand: ";
    cin >> num1;
    cout<<"Enter second operand: ";
    cin >> num2;
    
    char operation;
    cout<<"Enter operator: ";
    cin>> operation;

    switch (operation){

        case '+':
        cout<<num1<< "+"<< num2<<"="<<num1+num2;
        break;

        case '-':
        cout<<num1<<"-"<<num2<<"="<<num1-num2;
        break;

        case '*':
        cout<<num1<<"*"<<num2<<"="<<num1*num2;
        break;

        case '/':
        cout<<num1<<"/"<<num2<<"="<<num1/num2;
        break;

        default:
        cout<<"Error! operator is not correct ";
        break;
    }
    return 0;

}
