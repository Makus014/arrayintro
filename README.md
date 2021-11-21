# arrayintro




// months
#include <iostream>
using namespace std;


  int main() {

	//int heartRates[8] = { 54, 60, 71, 59, 62, 63, 60, 58 };

	//for (int i = 0; i < 8; i++) {
	//	cout << heartRates[i] << endl;
	//}

	string months[12] = { "January", "Febuary", "March", "April", "May", "June", "July", "August", "September", "October", "November", "December" };

	for (int i = 0; i < 12; i++) {
		cout << months[i] << endl;
	}
	return 0;


	return 0;
}
  
  
  
  
  
// mark
  #include <iostream>
  using namespace std;

  int main() {

	int subject[5];
	int result = 0;
	cout << "Mark your grades" << endl;
	for (int i = 0; i < 5; i++) {
		cout << "Enter your mark: " << endl;
		cin >> subject[i];
		result += subject[i];
	}
	cout << "Average is " << result / 5 << endl;

	return 0;
  }
