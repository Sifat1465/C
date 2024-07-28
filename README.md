#include<bits/stdc++.h>
using namespace std;
int main(){
    int t;cin>>t;
    while(t--){int x=0;
        string s;
        cin>>s;
        int n = s.size();
        if(n<=1){
            cout<<"NO";
            break;
        }
    for(int i=0;i<n;i++){
        if(s[0]!=s[i]){
            cout<<"YES";
            swap(s[0],s[i]);
          break;  
        }
        else{x=1;}
    }
    cout<<s;
        
    if(x==1) {   
     cout<<"NO" ;}  
    }
