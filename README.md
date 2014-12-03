Pro-6
=====
+
#include<iostream>
// Library function. (Predefined codes).
#include<conio.h>
+
using namespace std;
int main()
{
	int a = 1, b = 1, c;
	// Value is pre-defined.
	cout << "Enter any number : \n";
	cin >> c;
// Value is stored in int c.
	for (a = 1; a <= c; a++)
	// a will always be greater and equal to 1 and less then equal to the number user enteres. Eg 5 so a=5,4,3,2,1.
		b = b*a;
	{
		cout << "The factorial is : " << b << endl;
	}
	_getch();
	// gets charachter and screen does not exit afterwards until you want it to.
	return 0;
	// returns the value to int. As int always returns a value
}
+
This program gives you the factorial of the number you entered using only loop statement in C++
