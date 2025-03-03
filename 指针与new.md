```cpp
int a = 10;   // 普通变量
int* p = &a;  // 指针 p 存储变量 a 的地址

//new关键词
int* p=new int(10);// 在堆上创建一个值为10的int变量
delete p;

//new 分配数组
int* arr=new int[5]
//```
delete [] arr;


//创建动态二维数组
int** arr=new int*[3];//new int*[3] 表示创建一个指针数组，它包含3 个 int* 类型的指针
for (int i = 0; i < 3; i++)
    arr[i] = new int[4]; // 每行 4 列
//赋值
for (int i = 0; i < 3; i++)
    delete[] arr[i];
delete[] arr;//释放内存



