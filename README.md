# 3.2-code-C-
# 3.1-code-C- Подстановка любого числа в переменную "x" и "y" И обмен их значений без использования 3 переменной
#include <iostream>
using namespace std;

int main()
{
    int x=0;
    int y=0;
    int d=0;
    cout << "Enter x: ";
    cin >> x;
    cout << "Enter y: ";
    cin >> y;
    x=y+x;
    y=x-y;
    x=x-y;
    cout << "x: " << x << endl;
    cout << "y: " << y << endl;

    return 0;
}
