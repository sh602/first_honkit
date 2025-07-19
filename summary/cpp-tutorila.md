## C++ 入门教程

### 1. Hello World

```cpp
#include <iostream>
using namespace std;

int main() {
    cout << "Hello, World!" << endl;
    return 0;
}
```

### 2. 变量与数据类型

```cpp
int a = 10;        // 整型
double b = 3.14;   // 浮点型
char c = 'A';      // 字符型
bool flag = true;  // 布尔型
```

### 3. 条件语句

```cpp
int score = 85;
if (score >= 60) {
    cout << "及格" << endl;
} else {
    cout << "不及格" << endl;
}
```

### 4. 循环语句

```cpp
for (int i = 0; i < 5; i++) {
    cout << i << endl;
}
```

### 5. 函数定义

```cpp
int add(int x, int y) {
    return x + y;
}
```

### 6. 输入输出

```cpp
int num;
cout << "请输入一个数字：";
cin >> num;
cout << "你输入的是：" << num << endl;
```

---