# cpp
#include <iostream>

using namespace std;

class arun{

public:
    int add(int x,int y)
    {

        return x+y;
    }

};

int main()
{
   int a,b,s;
   cout<<"enter the values"<<endl;
   cin>>a>>b;
   arun obj;
   s=obj.add(a,b);
   cout<<"sum of two nos are "<<s;

}
