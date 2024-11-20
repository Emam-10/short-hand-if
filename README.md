# short-hand-if
#include <iostream>
#include <string>
#include "postive or negative.h"
using namespace std;



int main()
{
    int n;
    cin >> n;
   postiveornegative::number(n); //lib to read postive and negative number


    int number=-5;
    string result;

    if (number > 0) {  //if else
       result= "postive";
    }
    else {
        result ="Negative" ;
    }

    cout <<result<< endl;


    result = (number == 0) ? "Zero" : ((number > 0) ? "postive" : "negative"); //short hand if
    cout << "The result is " << result  << endl;



    return 0;
}
