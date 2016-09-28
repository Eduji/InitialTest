# InitialTest
#include <Windows.h>
#include <iostream>
using namespace std;
int main()
{
	int repetitions;
	int counter = 0;

	std::cout << "Input a Number: ";
	std::cin >> repetitions;
	while (counter < repetitions) {
		counter++;
		std::cout << counter << ":\tIt is Wednesday, my dudes!\n";
	}
	system("PAUSE");
	return 0;
}
