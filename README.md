#include <iostream>
#include <string>

using namespace std;

int main() {
    string name, hobby;
    int age;

    // Nhập thông tin cá nhân
    cout << "Nhập tên của bạn: ";
    getline(cin, name);

    cout << "Nhập tuổi của bạn: ";
    cin >> age;
    cin.ignore(); // Xử lý dòng trống sau khi nhập số

    cout << "Nhập sở thích của bạn: ";
    getline(cin, hobby);

    // Hiển thị thông tin
    cout << "\n--- Giới thiệu bản thân ---" << endl;
    cout << "Tên: " << name << endl;
    cout << "Tuổi: " << age << endl;
    cout << "Sở thích: " << hobby << endl;

    return 0;
}

