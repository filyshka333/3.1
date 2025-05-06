#include <iostream> 
using namespace std; 
class Number {; 
public: 
 int num; 
 int result; 
 void res(){ 
  cin >> num; 
  result = num /100; 
  cout << result; 
 } 
}; 
int main() 
{ 
 setlocale(LC_ALL, "Russian"); 
 Number num; 
 num.res(); 
  
}
