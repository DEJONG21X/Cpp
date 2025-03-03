```cpp
// char 数组用于存储多个字符（通常用于字符串）。
// 以 '\0'（空字符）结尾的 char 数组可被视为 C 风格字符串：
char name[] = "Alice"; // 自动在末尾添加 '\0'

// 等价于：
char name[] = {'A', 'l', 'i', 'c', 'e', '\0'};

//C 语言提供了一些字符串处理函数，它们在 cstring 头文件中定义。

//获取字符串长度：
char name[]="hello";
length=strlen(name);

//复制字符串
char name2[10];
strcpy(name2,name);//strcpy 需要确保目标数组足够大，否则可能导致缓冲区溢出

//字符串拼接
char str1[20]="hello";
char str2[] ="word";
strcat(str1,str2);
cout<<str1;//将str2拼接到str1后

//字符串比较
strcmp(str1,str2);

//整行读取char数组
cin.getline(数组名，最大长度）


//修改char数组
char array[]="hello";
array[0]='H';//修改第一个字符
