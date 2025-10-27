    #include <iostream>
    #include <cmath>
    #include <iomanip>
    using namespace std;

    double distanceBetweenPoints(double x1, double y1, double x2, double y2) {
    return sqrt(pow(x2 - x1, 2) + pow(y2 - y1, 2));
    }

    int main() {
    double x1, y1, x2, y2;

    cout << "Masukkan x1: ";
    cin >> x1;
    cout << "Masukkan y1: ";
    cin >> y1;
    cout << "Masukkan x2: ";
    cin >> x2;
    cout << "Masukkan y2: ";
    cin >> y2;

    cout << fixed << setprecision(4);
    cout << "Jarak kedua titik adalah: "
         << distanceBetweenPoints(x1, y1, x2, y2) << endl;

    return 0;
    }
