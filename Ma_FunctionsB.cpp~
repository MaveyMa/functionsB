// Name: Mavey Ma
// Due: Oct. 15, 2015
// Functions B Programming Worksheet (& Passerby Reference)

#include <iostream>
#include <string>
#include <cassert>
#include <cmath>

using namespace std;
//1
double feetToInches(double val);
void FeetToInches(double feet, double& inches);
//2
double computeRectangle(double valA, double valB);
void computerArea (double valA, double valB, double& valC);
//3
void computerArea (double valA, double valB, double& valArea, double& valPerimeter);
//4
void  stats(double valA, double valB, double valC, double valD, double& valE, double& valF);
//5
void calcAreaPerimeter(double radius, double& area, double& perimeter);
//6
double calcArea(double length, double width);

int main()
{ 
    //1 TESTS
    cout << feetToInches(1.0) << endl;
    cout << "Expected: 12\n";
    cout << feetToInches(0.5) << endl;
    cout << "Expected: 6\n";
    double inchesVal;
    FeetToInches(2.0, inchesVal);
    cout << "Expected: 24\n";
    FeetToInches(5.0, inchesVal);
    cout << "Expected: 60\n";
    //2 TESTS
    cout << computeRectangle(1.0, 3.5) << endl;
    cout << "Expected: 3.5\n";
    cout << computeRectangle(0.5, 50) << endl;
    cout << "Expected: 25\n";
    double areaAnswer1;
    computerArea(2.0, 100, areaAnswer1);
    cout << "Expected: 200\n";
    computerArea(5.0, 0, areaAnswer1);
    cout << "Expected: 0\n";
    //3 TESTS
    double areaAnswer, perimeterAnswer;
    computerArea(2.0, 100, areaAnswer, perimeterAnswer);
    cout << "Expected: 200 and 204\n";
    computerArea(5, 3.0, areaAnswer, perimeterAnswer);
    cout << "Expected: 15 and 16\n";
    //4 TESTS
    double avgAnswer, sumAnswer;
    stats(1, 2, 3, 4, avgAnswer, sumAnswer);
    cout << "Expected: 2.5 and 10\n";
    stats(5, 3, 0, 100, avgAnswer, sumAnswer);
    cout << "Expected: 27 and 108\n";
    //5 TESTS
    double circleArea, circlePerimeter;
    calcAreaPerimeter(2, circleArea, circlePerimeter);
    cout << "Expected: 12.56 and 12.56\n";
    calcAreaPerimeter(5, circleArea, circlePerimeter);
    cout << "Expected: 78.5 and 31.4\n";
    //6 TESTS
    cout << calcArea(100, 3) << endl;
    cout << "Expected: 300\n";
    cout << calcArea(11, 9) << endl;
    cout << "Expected: 99\n";

    return 0;
}
// *******************PROBLEM ONE*******************//
double feetToInches(double val)
{
    double result = val * 12; //12 INCHES IN A FOOT
    return result;
}
void FeetToInches(double feet, double& inches)
{
    inches = feet * 12; //12 INCHES IN A FOOT
    cout << inches << endl;
}
// *******************PROBLEM TWO*******************//
double computeRectangle(double valA, double valB)
{
    double result = valA * valB;
    return result;
}
void computerArea (double valA, double valB, double& valC)
{
    valC = valA * valB;
    cout << "Area is " << valC << endl;
}
// *******************PROBLEM THREE*******************//
void computerArea (double valA, double valB, double& valArea, double& valPerimeter)
{
    valArea = valA * valB;
    valPerimeter = (valA * 2) + (valB * 2);
    cout << "Area is " << valArea << endl;
    cout << "Perimeter is " << valPerimeter << endl;
}
// *******************PROBLEM FOUR*******************//
void  stats(double valA, double valB, double valC, double valD, double& valE, double& valF)
{
    valF = valA + valB + valC + valD; //SUM
    valE = valF / 4; //AVERAGE
    cout << "Average is " << valE << endl;
    cout << "Sum is " << valF << endl;
}
// *******************PROBLEM FIVE*******************//
void calcAreaPerimeter(double radius, double& area, double& perimeter)
{
    const double PI = 3.14;
    area = PI * radius * radius;
    perimeter = 2 * PI * radius;
    cout << "Circle Area is " << area << endl;
    cout << "Circle Perimeter is " << perimeter << endl;
}
// *******************PROBLEM SIX*******************//
double calcArea(double length, double width)
{
    double result = length * width;
    return result;
}
