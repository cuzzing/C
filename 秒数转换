#include <iostream>

/* run this program using the console pauser or add your own getch, system("pause") or input loop */

int main(int argc, char** argv) {
	using namespace std;
	int second;
	int day;
	int hour;
	int minute;
	cout << "Enter the number of seconds: ";
	int total;
	cin >> total;
	cout << total << " seconds = ";
	second = total % 60;  // second秒数，total分钟 
	total = total / 60;
	minute = total % 60;  // minute分钟，total小时 
	total = total / 60;
	hour = total % 24;  // hour小时，total天数 
	total = total /24;
	day = total;  // day天数 
	cout << day << " days, " << hour << " hours, " << minute << " minutes, " << second << " seconds";
	
	return 0;
}
