
class Student {
private:  // private section
int studentId;  //    int studentId
string studentName;  //    name <- 20 charcters

public:  // public section
Student();
Student(int ID, string name);
void assignDetails();  //    assignDetails() method declaration
void display();  //    display() method declaration

}


#include "Student.h"
#include <iostream>

// Assign studentId and name
Student::assignDetails(int ID, string name) 
{
  studentId=ID, studentName=name;
}

// Display StudentId and Name
Student::display() 
{
   cout << "Student ID = " << StudentId << endl << "Student Name = " << studentName << endl; 
}

class Box {
    private:
       int length;
       int width;
       int height;
    public:
void setLenght(int l);      // write prototypes of setters for length, width and height
void setWidth(int w ); 
void setHeight(int h);
int getLength();       // write prototypes of getters for length, width and height 
int getWidth();
int getHeight();
    int calcVolume();
};

