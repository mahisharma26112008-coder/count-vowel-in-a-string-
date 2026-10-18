# count-vowel-in-a-string-


#include <iostream>
using namespace std;

int main() {
    string s;
    int count = 0;

    cout << "Enter a string: ";
    cin >> s;

    for (int i = 0; s[i] != '\0'; i++) {
        if (s[i] == 'a' || s[i] == 'e' || s[i] == 'i' ||
            s[i] == 'o' || s[i] == 'u' ||
            s[i] == 'A' || s[i] == 'E' || s[i] == 'I' ||
            s[i] == 'O' || s[i] == 'U') {
            count++;
        }
    }

    cout << "Total vowels = " << count;

    return 0;
}
