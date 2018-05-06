## 什么是数组

在`C++`语言中,为了方便处理,把具有相同类型的多个变量按有序的形式组织起来.我们把这种结果称为**数组**.


**一维数组直观表示:**



## 数组的意义

你现在有一个任务,编写一个程序,把班级里的60名同学的成绩存入电脑(只存成绩),如何你不会数组,可能会这样写:

你会发现代码会十分的复杂.


```c
#include <cstdio>

int main(){
    int student0,student1,student2,
    student4, student5, student6, student7,
    student8, student9, student10, student11, student12,
    student13, student14, student15, student16, student17,
    student18, student19, student20, student21, student22,
    student23, student24, student25, student26, student27, student28,
    student29, student30, student31, student32, student33, student34,
    student35, student36, student37, student38, student39, student40,
    student41, student42, student43, student44, student45, student46,
    student47, student48, student49, student50, student51, student52, student53,
    student54, student55, student56, student57, student58, student59,
    student60;

    scanf("%d",&student1);
    scanf("%d",&student2);
    scanf("%d",&student3);
    scanf("%d",&student4);
    scanf("%d",&student5);
    scanf("%d",&student6);
    scanf("%d",&student7);
    scanf("%d",&student8);
    scanf("%d",&student9);
    scanf("%d",&student10);
    scanf("%d",&student11);
    scanf("%d",&student12);
    scanf("%d",&student13);
    scanf("%d",&student14);
    scanf("%d",&student15);
    scanf("%d",&student16);
    scanf("%d",&student17);
    scanf("%d",&student18);
    scanf("%d",&student19);
    scanf("%d",&student20);
    scanf("%d",&student21);
    scanf("%d",&student22);
    scanf("%d",&student23);
    scanf("%d",&student24);
    scanf("%d",&student25);
    scanf("%d",&student26);
    scanf("%d",&student27);
    scanf("%d",&student28);
    scanf("%d",&student29);
    scanf("%d",&student30);
    scanf("%d",&student31);
    scanf("%d",&student32);
    scanf("%d",&student33);
    scanf("%d",&student34);
    scanf("%d",&student35);
    scanf("%d",&student36);
    scanf("%d",&student37);
    scanf("%d",&student38);
    scanf("%d",&student39);
    scanf("%d",&student40);
    scanf("%d",&student41);
    scanf("%d",&student42);
    scanf("%d",&student43);
    scanf("%d",&student44);
    scanf("%d",&student45);
    scanf("%d",&student46);
    scanf("%d",&student47);
    scanf("%d",&student48);
    scanf("%d",&student49);
    scanf("%d",&student50);
    scanf("%d",&student51);
    scanf("%d",&student52);
    scanf("%d",&student53);
    scanf("%d",&student54);
    scanf("%d",&student55);
    scanf("%d",&student56);
    scanf("%d",&student57);
    scanf("%d",&student58);
    scanf("%d",&student59);
    scanf("%d",&student60);
    return 0;
}
```


**如果你会数组**,你会这样写:

```c
#include <cstdio>

int main(){
    int student[60];

    int i;
    for(i=0;i<60;i++)
        scanf("%d",&a[i]);

    //输出成绩
    for(i=0;i<60;i++)
        scanf("%d:%d\n",i,&a[i]);
    return 0;
}
```

可以看出代码已经非常简便了


