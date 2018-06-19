## 代码



```c
#include <cstdio> //头文件
int main(){ //主函数
    printf("hello world!"); //输出
    return 0; //程序结束
}
```

## 代码讲解


**1.main函数**  
每个程序都要有**main函数**,代表程序从哪个地方开始执行,它的框架如下

```c
int main(){

    //代码区域

    return 0; //函数结束,基本都要返回0
}
```

**2.printf函数**  
如果要使用这个函数,你心须先包含`cstdio`这个头文件,也就是`#include <cstdio>`,它的意思是`C语言的标准的输入输出头文件`(c stand input output),我们用的是C++语言,C++语言是可以兼容C语言的  


**3.注释**

什么是**注释**?注释是为了更好让别人或自己来阅读代码,在代码编译阶段,注释会被略过.  
注释有两种,单行注释与多行注释,写法如下.

```c
//这是单行注释

/*
    这里是
多
    行
    注释!
*/

```

## 在noiLInux上编写代码

**0.打开配置好的gedit,`ctrl+s`保存文档为`1.cpp`**


<center>
![0](/book/images/gedit/输入代码00.png=500x700)
</center>

保存到`~`**家目录**下

**1.输入上面的代码!**

<center>
![1](/book/images/gedit/输入代码1.png=500x700)
</center>


`ctrl+s`保存

<center>
![3](/book/images/gedit/输入代码3.png=500x700)
</center>

**2.`ctrl+alt+t打开终端`**


<center>
![4](/book/images/gedit/输入代码4.png=500x700)
</center>

编译代码:

```shell
g++ -g -o 1 1.cpp
```

<center>
![5](/book/images/gedit/输入代码5.png=500x700)
</center>

**3:运行代码**

<center>
![6](/book/images/gedit/输入代码6.png=500x700)
</center>

在终端里输入

```shell
./1
```

看到结果:

<center>
![7](/book/images/gedit/输入代码7.png=500x700)
</center>


## 为什么不使用c++语言的输入输出(`cin,cout`)呢? 

上面的程序也可以这么写:

```c
#include <iostream> // C++的输入输出头文件
using namespace std; //使用标准命名空间

int main(){
    cout << "hello world!" << endl;
    return 0;
}
```

为什么不使用c++语言的输入输出(`cin,cout`)呢?有以下几个原因:  

  - 学习本书的目的是为了参数**信息学竞赛**,不是为了深入学习**c++**语言
  - 在面对复杂格式化输出的时候,C的输出方法更简单,代码量更少
  - C的输入输出更快(基本上为了更快的输入,会使用**快读**技巧)


## 练习题目

 - 超级玛丽游戏
 - 菱形三角形
