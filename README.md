# lab2
巩固有关java 自增、自减运算符与类型转换有关知识
> 此次lab不需要提供代码文件或工程文件，仅需就两个问题向助教面试并提交书面答案的文档即可

## 问题一

自增（自减与自增类似，不单独设题）

### 问题描述

观察下面一段代码，思考控制台会有何种输出，并解释原因。
```
int x = 1;
x ++;
System.out.println(x);
++ x;
System.out.println(x);
System.out.println(x ++);
System.out.println(++ x);

x = x++ + ++x;
System.out.println(++ x + ++ x);
```


## 问题二
简单的类型转换

### 问题描述

观察下面几段代码，它们能否通过编译，如果不能，请解释原因，如果能，```x```的值为多少或控制台会有何种输出？并解释原因。

1.
```
char x = 'a';
x ++;
```
2.
```
char x = 'b';
x = x + 1;
```
3.
```
short x = 1;
x = x + 10;
```
4.
```
short x = 5;
x += 2;
```
5.
```
boolean x = true;
x ++；
```
6.
```
char x = 'z';
System.out.println(x + 1);
short y = 2；
System.out.println(y + 1);
```


# Deadline

2018年9月30日 23:59

将你的回答组织成pdf文件，命名为```学号_姓名_lab2.pdf```后提交到FTP目录（```WORK_UPLOAD```目录）

