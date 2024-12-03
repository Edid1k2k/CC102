#include <iostream>

using namespace std;

int main()
{

    char symbol1, symbol2, symbol3;
    cout << "Enter 1st symbol to use (*, ^, #, $, @): ";
    cin >> symbol1;
    cout << "Enter 2nd symbol to use (*, ^, $, @): ";
    cin >> symbol2;
    cout << "Enter 3rd symbol to use (*, $, @): ";
    cin >> symbol3;
    cout << "You picked: " << symbol1 << " " << symbol2 << " " << symbol3 << endl;
  

    // f:
    cout << "f:" << endl;
    int n = 10;
    for (int i = 0; i < n; ++i) {
        for (int j = 0; j < i; ++j) {
            cout << symbol1;
        }
        cout << " ";
        for (int k = i; k < n - 1; ++k) {
            cout << symbol1;
        }
        cout << endl;
    }
    cout << endl;
  

    // g:
    cout << "g:" << endl;
    int rows = 5;
    int cols = 10;
    for (int i = 0; i < rows; ++i) {
        for (int j = 0; j < cols; ++j) {
            if (i % 2 == 0) {
                cout << symbol2 << " ";
            } else {
                cout << " " << symbol2;
            }
        }
        cout << endl;
    }
    cout << endl;
  

    // h:
    cout << "h:" << endl;
    n = 7;
    for (int i = 0; i <= n; ++i) {
        for (int j = 0; j < i; ++j) {
            cout << symbol1;
        }
        cout << symbol2 << endl;
    }
    for (int i = n; i >= 0; --i) {
        for (int j = 0; j < i; ++j) {
            cout << symbol1;
        }
        cout << symbol2 << endl;
    }
    cout << endl;
  

    //i:
    cout << "i:" << endl;
    n = 5;
    cout << "                             " << symbol3 << endl;
    for (int i = 1; i <= n; ++i) {
        cout << "                             ";
        for (int k = 0; k < i; ++k) {
            cout << symbol2; 
        }
        cout << symbol3 << endl;
    }
    int m = 2;
    for (int i = 0; i < m; ++i) {
        cout << "##########";
        for (int j = 0; j < n; ++j) {
            cout << symbol2;
        }
        cout << symbol3 << endl;
    }
    for (int i = n; i > 0; --i) {
        cout << "                             ";
        for (int k = 0; k < i; ++k) {
            cout << symbol2;
        }
        cout << symbol3 << " " << endl;
    }
    cout << "                             " << symbol3 << endl;
   
    return 0;
}
