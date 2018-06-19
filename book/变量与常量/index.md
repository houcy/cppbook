## 常量

有时需要定义不变的变量，即常量

如:

```c
#define pi 3.1415
```
## 变量

在程序运行的过程中,可以改变的量

```c
int a=10; a=100;
```
## 标识符的书规则

**标识符**在程序中用来标识各种程序成分，命名程序中的一些实体，如变量、常量、函数、类型和符号等对象。它由大小写字母,数字,下划线组成,其中**数字不能放开头**

例子

```
 int a;  // 正确
 int Aa;// 正确
 int a8;// 正确
 int _a8;// 正确
 int 8a; //错误,不能以数字开头
```

注意:

 - 区分大小,a与A是不同的
 - 不能使用保留字做为变量名,如 `int char =a` 不可以

## 常用变量类型

 - 整型
  - int 32位整型
  - long long 64位整型
 - 浮点型
  - float 单精度
  - double 双精度
 - 布尔型: bool
 - 字符型: char

## 一个常用的函数:`sizeof()`

`sizeof(变量类型/变量名)` 返回**变量类型**或者**变量**所占内存的字节长度

```c
#include <cstdio>

//sizeof(变量类型/变量名)
int main(){

    int a;
    printf("%d",sizeof(a));

    printf("%d",sizeof(long long));
    return 0;
}
```

## 练习题目

- luguo P1001 A+B Problem
- luguo P1421 小玉买文具
- luguo P1425 小鱼的游泳时间
- noiopenjudge 整型数据类型存储空间大小
- noiopenjudge 浮点型数据类型存储空间大小
- noiopenjudge 其他基本数据类型存储空间大小
- noiopenjudge 填空：类型转换1
- noiopenjudge 填空：类型转换2
- noiopenjudge 浮点数向零舍入
- noiopenjudge 打印ASCII码	10
- noiopenjudge 打印字符	10
- noiopenjudge 整型与布尔型的转换
- noiopenjudge Hello, World!的大小
