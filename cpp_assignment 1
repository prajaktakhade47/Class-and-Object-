# Class-and-Object-
#include <iostream>
using namespace std;

class Student{
private:
    string name;
    int rollNo;
    float m1, m2, m3;

public:
    Student(string n, int r, float a, float b, float c){
        name = n;
        rollNo = r;
        m1 = a;
        m2 = b;
        m3 = c;
        cout << "Student object created." << endl;
    }
    float calculateTotal(){
        return m1 + m2 + m3;
    }
    float calculatePercentage(){
        return calculateTotal()/3;
    }
    void displayResult(){
        cout<<"\n----- STUDENT RESULT -----"<<endl;
        cout<<"Name       : "<<name<<endl;
        cout<<"Roll No.   : "<<rollNo<<endl;
        cout<<"Total      : "<<calculateTotal()<<endl;
        cout<<"Percentage : "<<calculatePercentage()<<"%"<<endl;
    }
    ~Student(){
        cout<<"\nStudent object destroyed."<<endl;
    }
};
int main(){
    string name;
    int rollNo;
    float m1, m2, m3;

    cout<<"Enter student name: ";
    cin>>name;
    cout<<"Enter roll number: ";
    cin>>rollNo;
    cout<<"Enter marks of 3 subjects: ";
    cin>>m1>>m2>>m3;

    Student s1(name, rollNo, m1, m2, m3);
    s1.displayResult();
    return 0;
}
