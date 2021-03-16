# STL-LIBRARY-IN-C-
// Online C++ compiler to run C++ program online
#include <iostream>
using namespace std;

int main() {
    // Write C++ code here
   cout<<'c'+1<<endl;
   
   // pair
   
   pair<int,int> p1;
   
   p1.first=10;
   p1.second=12;
   
   cout<<p1.first<<" "<<p1.second<<endl<<endl;
   
   // second way of make pair
   
   pair<int,string> p;
   
  // p=make_pair(2,"abc");
  
  p={2,"abc"};
   
    cout<<p.first<<" "<<p.second<<endl;
    

    return 0;
}
