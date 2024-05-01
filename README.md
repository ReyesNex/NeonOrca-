#include <iostream>
using namespace std;

int
main ()
{
  int number;
  char proceed;

  do
	{
	  cout << "\nEnter any integer : ";
	  cin >> number;

	  switch (number % 2 == 0)
		{
		case true:
		  cout << "\nThis is even number";
		  break;
		default:				//case false
		  cout << "\nThis is odd number";
		}
	  cout << "\n\nPress Y to proceed or any key to terminate : ";
	  cin >> proceed;
	}
  while (proceed == 'Y' || proceed == 'y');

  cout << "\nThank You for using :)" << endl;
  return 0;
}

