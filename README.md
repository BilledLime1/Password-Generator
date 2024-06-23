#include <iostream>
#include <cstdlib>
#include <ctime>
using namespace std;
int main(){
    int len;
    cin >> len;
    srand(time(0));
    for (int i=0;i<len;i++)cout << char(rand()%94+33);
    return 0;
}
