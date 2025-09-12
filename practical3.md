```c
// Program to read prefix and postfix
#include <iostream>

using namespace std;

int main()
{
    int a=5;
    int b;
    b=++a;
    cout <<a;
    cout <<b;
    a=5;
    b=a++;
    cout <<a;
    cout <<b;
    b=--a;
    cout <<a;
    cout <<b;
    b=a--;
    cout <<a;
    cout <<b;
    return 0;
}

output
66655545
```
