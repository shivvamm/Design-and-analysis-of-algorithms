## Design-and-analysis-of-algoeithms
#PROGRAM OF UNION 
```c++

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
