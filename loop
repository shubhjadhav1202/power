#include <iostream>
using namespace std;
double power(double n,int p)
{
    double result=1;
    for(int i=0;i<p;i++){
        result *= n;
    }
    return result;
}
int main() {
    double n,result = 0;
    int p;
    cout << "enter n: ";
    cin >> n;
    cout <<"enter p: ";
    cin >> p;
    if(p<0){
        result = power(n,p*(-1));
        cout << n << "^" << p << "=" << 1/result << "\n";
    }
    else{
        result = power(n,p);
        cout << n << "^" << p << "=" << result << "\n";
    }
    return 0;
}
