#include<iostream>
#include<string>
using namespace std;
class Solution {
public:
    string num;
    void get() {
        if (num=="I"){
            cout<<1;
        }
        else if(num=="V"){
            cout<<5;
        }
        else if(num=="X"){
            cout<<10;
        }
        else if(num=="L"){
            cout<<50;
        }
        cin>>num;
        cout<<num;
    }
};
int main(){
 Solution s;
 s.get();
 return 0;
}
