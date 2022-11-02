## Design-and-analysis-of-algoeithms
#PROGRAM OF UNION 
```c++
/******************************************************************************

                              Online C++ Compiler.
               Code, Compile, Run and Debug C++ program online.
Write your code in this editor and press "Run" button to compile and execute it.

*******************************************************************************/

#include <bits/stdc++.h>
using namespace std;

int main()
{
    vector<int> A{10, 20, 30, 40, 50};
    vector<int> B{1, 2, 3, 40, 5};
     vector<int> sol;
      vector<int> res;
    int i=0;
    int n=5;
    while(i<n){
        sol.push_back(A[i]);
        sol.push_back(B[i]);
        i++;
    }
    sort(sol.begin(),sol.end());
    i=0;
     while(i<sol.size()){
         if(sol[i]!=sol[i+1]){
             res.push_back(sol[i]);
             i++;
         }
         else{
             i++;
         }
     }
     for(int i=0;i<res.size();i++){
         cout<<res[i]<<" ";
     }
    return 0;
}

```
