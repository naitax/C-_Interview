#include <iostream>
#include <vector>

using namespace std;

int main()
{
	
	int arr[5];
	for (int i = 0; i < 5; i++)
	{
		cin >> arr[i];
	}
	
	int arr_size = (sizeof(arr) / sizeof(arr[0])) - 1;
	vector <int> result;
	int sum_holder;
	int count = 1;

	for (int i = arr_size; i>= 0; i--)
	{
		sum_holder = arr[i] + count;

		if (sum_holder >= 10)
		{
			result.push_back(sum_holder % 10);
			count = 1;
		}
		else
		{
			result.push_back(sum_holder);
			count = 0;
		}
	}
	if (count == 1)
	{
		result.push_back(count);
		count = 0;
	}

	for (int i = arr_size; i >= 0; i--)
	{
		cout << result[i];
	}
	return 0;
}
