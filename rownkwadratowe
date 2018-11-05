#include <iostream>
#include <conio.h>
#include <math.h>

using namespace std;

int main()
{
	double a, b, c, d, x1, x2;
	cout << "Rozwiazywanie rownania kwadratowego" << endl;
	cout << "Podaj wspolczynniki:" << endl;
	cout << "a: ";
	cin >> a;
	cout << "b: ";
	cin >> b;
	cout << "c: ";
	cin >> c;
	d = (b * b) - (4 * a * c);
	if (a != 0)
	{
		cout << "Delta wynosi: " << d << endl;
		if (d < 0)
		{
			cout << "Rownianie nie posiada rozwiazan w dziedzinie rzeczywistej.";
			_getche();
			return 0;
		}
		else if (d == 0)
		{
			x1 = -b / 2 * a;
			cout << "Rownanie posiada jedno rozwiazanie x0 = " << x1;
			_getche();
			return 0;
		}
		else
		{
			x1 = (-b - sqrt(d)) / (2 * a);
			x2 = (-b + sqrt(d)) / (2 * a);
			cout << "Rownianie posiada dwa rozwiazania: x1 = " << x1 << " x2 = " << x2;
			_getche();
			return 0;
		}
	}
	else if ((a == 0) && (b != 0))
	{
		x1 = (-c) / (2 * b);
		cout << "Wspolczynnik a = 0, dlatego jest to rownianie liniowe z rozwiazaniem x0 = " << x1;
		_getche();
		return 0;
	}
	else if((a == 0) && (b == 0))
		if (c != 0)
		{
			cout << "Rownanie sprzeczne " << c << " = 0";
			_getche();
			return 0;
		}
		else
		{
			cout << "Rownianie tozszamosciowe 0 = 0";
			_getche();
			return 0;
		}
	_getche();
	return 0;
}
