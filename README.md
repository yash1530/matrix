# matrix
#include<bits/stdc++.h>
using namespace std;

int main() {
	int n,m;cin>>n>>m;
	vector<vector<int>>v(n,vector<int>(m,0));
		vector<vector<int>>res(n,vector<int>(m,0));

	for(int i=0;i<n;i++)
	{
	
	for(int j=0;j<m;j++)
	{
	cin>>v[i][j];
	}
	}
	for(int i=0;i<n;i++)
	{
	
	for(int j=0;j<m;j++)
	{
	      res[j][i]=v[i][j];
	}
	
	}
	for(int i=0;i<n;i++)
	{
	
	for(int j=0;j<m;j++)
	{
	      cout<<res[i][j]<<" ";
	}
	cout<<endl;
	}

}
	
	
