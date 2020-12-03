/*
Find a pair of numbers in an array that adds to a given sum
Example: 
Input: 
int arr[] = {2,4,7}
int sum = 9;
Output:
2 7
*/

#include <iostream>
using namespace std;

int main()
{
	int size, num, sum;
	cin >> size;
	int * numbers;
	numbers = new int[size];
	for (int i = 0; i < size; i++)
	{
		cin >> numbers[i];
	}
	
	
	cin >> sum;

	int index = 0;
	int num1 = numbers[index];

	while (index < size && num1 < sum)
	{
		int i = index + 1;

		while (i < size && (sum - num1) >= numbers[i])
		{
			if (num1 + numbers[i] == sum)
			{
				cout << num1 << " " << numbers[i] << " " << endl;
				i = size;
			}
			else i++;
		}
	index++;
	num1 = numbers[index];
	}
	
	

	return 0;
}
