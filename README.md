#include<iostream>
using namespace std;
class abc{
    int n,count=0;
    public:
    void get()
    {
        
        while(1)
        {
            cout<<"enter the number "<<endl;
            cin>>n;
            if(n%8==0)
            {
                count++;
            }
            else {
                cout<<"numbers divisibe by 8 are "<<count<<endl;
            break;
             }
           
        }
    }

};
int main()
{
    abc obj;
    obj.get();
    return 0;
    }
