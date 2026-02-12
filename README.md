#include <iostream>
using namespace std;

int main() {
    // 1. Ask user for temperature in Celsius
    float celsius;
    cout << "Enter temperature in Celsius: ";
    cin >> celsius;

    // 2. Convert Celsius to Fahrenheit
    float fahrenheit = (celsius * 1.8) + 32;

    // 3. Output the result
    cout << celsius << "°C is " << fahrenheit << "°F" << endl;

    // 4. Bonus: Check temperature conditions
    if (celsius < 0) {
        cout << "Freezing!" << endl;
    } else if (celsius > 30) {
        cout << "Hot!" << endl;
    }

    return 0;
}
