/*   This is comment and practice program */
#include<iostream>
using namespace std;

class A 
{
	private : int num1;
	public :
		int getNum() 
		{
			return this->num1;
		}	
};
int main() {
A a;
cout<<a.getNum();
return 0;
}