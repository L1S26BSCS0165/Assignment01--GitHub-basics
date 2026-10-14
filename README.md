# Assignment01--GitHub-basics
assignment01-getting started with github: c++ program for sum of 50 numbers


#include <iostream>
using namespace std;

int main() {
    int sum = 0;
    int n = 50;
    for (int i = 1; i <= n; i++) {
        sum = sum + i;
        
    }

    cout << "Sum of first 50 natural numbers (loop): "
         << sum << endl;

    int formulaSum = n * (n + 1) / 2;

    cout << "Sum of first 50 natural numbers (formula): "
         << formulaSum << endl;

    return 0;
}
