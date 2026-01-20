# String-Length-Using-Getline-Cpp
This repository contains a simple C++ program that reads a string using getline() and calculates its length using the length() function. It demonstrates basic string input handling and string operations in C++.
# String Length Using getline() in C++

This repository contains a basic C++ program that takes a string input from the user using `getline()` and prints the length of the string using the `length()` function.

## 📌 Program Description
The program prompts the user to enter a string, reads the complete line including spaces, and then displays the total number of characters in the string. This example helps beginners understand string input and basic string operations in C++.

## 🧠 Concepts Covered
- C++ string handling
- `getline()` function
- `length()` function
- User input and output

## 💻 Source Code
```cpp
#include<iostream>
using namespace std;

int main(){
    string str = "Ranjith";
    cout << "Enter the string name: ";
    getline(cin, str);
    cout << str.length() << endl;
    return 0;
}
