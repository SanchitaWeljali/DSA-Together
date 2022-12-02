//{ Driver Code Starts
#include <bits/stdc++.h>
using namespace std;


// } Driver Code Ends
class Solution
{
    public:
    bool isAnagram(string a, string b){
        int l1 = a.length();
        int l2 = b.length();
        
    if (l1 != l2)
        return false;
 
    sort(a.begin(), a.end());
    sort(b.begin(), b.end());

    for (int i = 0; i < l1; i++)
        if (a[i] != b[i])
            return false;
 
    return true;
        
    }

};

//{ Driver Code Starts.

int main() {
    
    int t;

    cin >> t;

    while(t--){
        string c, d;

        cin >> c >> d;
        Solution obj;
        if(obj.isAnagram(c, d)) cout << "YES" << endl;
        else cout << "NO" << endl;
    }

}

// } Driver Code Ends
