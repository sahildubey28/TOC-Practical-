#include <bits/stdc++.h>
using namespace std;

int main ()
{
  string bin;
  int ones = 0, zeros = 0;
  cout<<endl;
  cout << "\tDesign A Program For Creating A Machine Which Accepts String Having Equal Number Of Ones And Zeros.\n";
  cout << "Enter Any Binary Number : ";
  cin >> bin;
  int size = bin.size ();
  for (int i = 0; i < size; i++)
    {
      if (bin[i] == '1')
	{
	  ones++;
	}
      else if (bin[i] == '0')
	{
	  zeros++;
	}
      else
	{
	  cout << "Error!!! You've Entered Wrong Binary Number\n";
	  ones = -1;
	  break;
	}
    }
  if (ones != -1)
    {
      cout << "Please Wait, While Machine Is Checking Your Binary Number...\n";
    }

  if (ones == zeros && ones != -1)
    {
      cout << "\nAccepted!!! The Given Binary Number Having Equal Number Of Zeros And Ones\n";
    }
  else if (ones == -1)
    {
      cout << "\nFailed !!! Please Enter A Valid Binary Number.\n";
    }
  else
    {
      cout << "\nInvalid !!! The Given Binary Number Not Having Equal Number Of Zeros And Ones\n";
    }
  return 0;
}
