#include <iostream>
using namespace std;

int main() {
    int rows = 5; // Example dimensions
    int cols = 5;
    int array[5][5];

    // Populate the array with i * j
    for (int i = 0; i < rows; i++) {
        for (int j = 0; j < cols; j++) {
            array[i][j] = i * j;
        }
    }

    // Print the array
    for (int i = 0; i < rows; i++) {
        for (int j = 0; j < cols; j++) {
            cout << array[i][j] << " ";
        }
        cout << endl;
    }

    return 0;
} 
<!---
Bler123code/Bler123code is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
