#include<iostream>
using namespace std;
int main()
{
	
	int x1, x2, y1, y2;
	cin >> x1 >> x2 >> y1 >> y2 ;
	double m = (y2 - y1) / (x2 - x1);
	cout << "please enter the coordinates of two points (x1,y1)and (x2,y2)";
	cout << "gradient of the line :" << m << endl;
	double theta_radian = atan(m);
	double theta_degree = theta_radian * 180 / 3.14;
	cout << "angle (in radians):" << theta_radian << endl;
	cout << "angle (in degrees):" << theta_degree << endl;
	return 0;
	
}
