# scanf的使用

## 1.读取整数

**读取一个整数**
```c
#include <cstdio>

int main(){
    int a;
    scanf("%d",&a);
    printf("du qu de shu zi shi %d",a);
    return 0;
}
```

**读取多个整数**

```c
#include <cstdio>

int main(){
    int a,b;
    scanf("%d%d",&a,&b)
    printf("du qu de shu zi shi %d,%d",a,d);
    return 0;
}
```

## 2.读取小数(实数)

**单精度**

```c
#include <cstdio>

int main(){
    float a; //单精度
    scanf("%f",&a);
    printf("shu zi shi %f",a);
    return 0;
}
```

**双精度**

```c
#include <cstdio>

int main(){
    double a; //单精度
    scanf("%lf",&a);
    printf("shu zi shi %lf",a);
    return 0;
}
```

## 读取字符

```c
#include <cstdio>

int main(){
    char a;
    scanf("%c",&a);
    printf("zifu shi %c",a);
    return 0;
}
```

## 使用scanf的读取的技巧

 - 读取`数字`,`字符串`的时候,会略过空格
 - 读取`字符`的时候,不会略过空格
 - `scanf`是一个函数,返回值是读取变量的数量
 - `scanf`如果读取的是文件(重定向)时,读取文件末尾返回`EOF`这个值,也就是`-1`


**样例1:略过空格**

**样例2:读取字符**

**样例3:echo能力**
