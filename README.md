# Lab-15.10-
#include <iostream>
#include <cmath>	// needed for math functions like sqrt()
using namespace std;

int main()
{
	double a, b;	// the smaller two sides of the triangle 
	double hyp;	// the hypotenuse calculated by the program

	cout << "Please input the value of side one" << endl;
	cin >> a;
  cout << "Please input the value of side two" << endl;
	cin >> b;

	// Fill in the assignment statement that determines the hypotenuse
  hyp = sqrt(pow(a,2)+ pow(b,2));
 

	cout << "The sides of the right triangle are " << a << " and " << b << endl;

	cout << "The hypotenuse is " << hyp << endl;

}
