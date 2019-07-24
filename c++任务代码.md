```c++
/*20190724 结构体*/
#include<iostream>
#include<string>
using namespace std;

struct Task
{
	char number[20];
	string name;
	int age;
	string address;
	string tel;
};

int main()
{
	Task cym =
	{
		"P19301112",
		"程伊旻",
		21,
		"李园1516",
		"18715665338"
	};
	cout << "学号：" << cym.number << endl;
	cout << "年龄：" << cym.age << endl;
	cout << "姓名：" << cym.name << endl;
	cout << "地址：" << cym.address << endl;
	cout << "联系方式：" << cym.tel << endl;
	int test;
	cout << "请输入：" << endl;
	cin >> test;
	system("pause");

	return 0;
}
```