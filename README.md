//{ Driver Code Starts
//Initial function template for C++
###anmol bansal
#include<bits/stdc++.h>
using namespace std;

// } Driver Code Ends
//User function template for C++

class Solution{
    public:
    // arr : given array
    // l : starting index of the array i.e 0
    // r : ending index of the array i.e size-1
    // k : find kth smallest element and return using this function
    int kthSmallest(int arr[], int l, int r, int k) {
        sort(arr+l,arr+r+1);
        int ele=arr[k-1];
        return ele;
    }
};


