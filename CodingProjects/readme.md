# Coding Projects

+ ### **Here is a madlib program I created in C++**

'''cpp

#include <iostream>
	
#include <string>

using namespace std;

string instructor;
string name;
string food;
int num;
string adj;
string color;
string animal;


int main()
{

	cout << "Enter the first or last name of your instructor: ";
	cin >> instructor;
	cout << endl;

	cout << "Enter your first name: ";
	cin >> name;
	cout << endl;

	cout << "Enter a food: ";
	cin >> food;
	cout << endl;

	cout << "Enter a number between 100 and 200: ";
	cin >> num;	
	cout << endl;

	cout << "Enter and adjective: ";
	cin >> adj;
	cout << endl;

	cout << "Enter a color: ";
	cin >> color;
	cout << endl;

	cout << "Enter an animal: ";
	cin >> animal;
	cout << endl;

	cout << "Dear Instructor " << instructor << endl;
	cout << " Im sorry that I am unable to turn in my homework now. First, I ate a rotten " << food << ", which " << endl;
	cout << "made me turn " << color << " and extremely ill. I came down with a fever of " << num << ". Next, " << endl;
	cout << "my " << adj << " pet " << animal << " must have smelled the remains of the " << food << " on my homework " << endl;
	cout << "because he ate it. I am currently rewriting my homework and hope you will accept it late." << endl << endl;

	cout << "Sincerely" << endl;
	cout << name << endl << endl;


return 0;
		

}
'''

|[**Home**](https://chogue7809.github.io/AboutMe/)|
