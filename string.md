```cpp
//string字符串初始化
std::string s1 = "Hello";     // 直接初始化
std::string s2("World");      // 使用构造函数
std::string s3(s1);           // 拷贝构造
std::string s4(5, 'A');       // 生成 "AAAAA"


//std::string 允许使用 + 进行拼接

//整行读取string
string str;
getline(cin,str);


//用.size() or .length()获取长度
string s="Hello";
length=s.size();
size=s.length();

//访问字符串中的字符

//方法一[]
string s = "Hello";
s[1]='a';//通过访问string字符修改字符串


//方法二.at()
string s = "Hello";
s.at(1)='a';


//索引获取字符串
string s="Hello World";
string sub=s.substr.(7,5)//索引从7开始，取5个字符


//插入字符串
string s="Hello World";
s.insert(5,",")// 在索引 5 处插入 ","

//删除字符
string s = "Hello, World!";
s.erase(5, 1);  // 从索引 5 开始删除 1 个字符

//替换子串
string s = "Hello, World!";
s.replace(7, 5, "C++");  // 从索引 7 开始，替换 5 个字符

