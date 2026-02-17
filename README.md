#ifndef STUDENT_H
#define STUDENT_H

#include <string>
using namespace std;

class Student {
private:
    string indexNumber;
    string name;

public:
    Student();
    Student(string idx, string nm);

    string getIndexNumber();
    string getName();

    void display();
};

#endif
