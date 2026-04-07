#include <iostream>
using namespace std;

int main() {

    string name;
    int days;
    float rate = 5.0, total;

    cout << "Enter Borrower Name: ";
    cin >> name;

    cout << "Enter days overdue: ";
    cin >> days;

    total = days * rate;

    cout << "\n--- Library Fine Result ---\n";
    cout << "Name: " << name << endl;
    cout << "Overdue Days: " << days << endl;
    cout << "Total Fine: " << total << endl;

    if (days > 0) {
        cout << "Status: FINE APPLICABLE" << endl;
    }
    else {
        cout << "Status: NO FINE" << endl;
    }

    return 0;
}
