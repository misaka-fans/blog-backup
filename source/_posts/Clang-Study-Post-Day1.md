---
title: C语言入门学习之数据类型Char的运用(随学习进度不断修改)
date: 2024-03-03 13:59:32
tags: 
      - coding
      - study
cover: https://ts1.cn.mm.bing.net/th/id/R-C.9a864b6b5a4df041d6fddd72b6e12455?rik=ehi3u30l1%2fPx%2fQ&riu=http%3a%2f%2fwww.w3schools.cn%2fwp-content%2fuploads%2fc%2fc-logo.png&ehk=ZIVUd12vPYpOwaMUCTzsLkK8aukj5cnzsRADTdxoKfM%3d&risl=&pid=ImgRaw&r=0
---
# 0、目前了解到的现象&结论
通过以下方法输出字符串时：
```c
// A
char x = 'ABC';
printf("%c", x); //C
```

```c
// B
char *x = "ABC";
printf("%s", x); //ABC
```
本文章将会随学习进度补充更多用法。

# 1、使用时应牢记的注意事项

A号代码框，使用`%c`将会输出字符串内最后一位字符。<b>注意：此时应使用单引号，注意与反引号的区别</b>

B号代码框中，当char用作指针变量时，即<b>char *</b>，字符串应被双引号框住，`%s`将会输出这段字符串，`%d`将字符串以其十进制方式输出，`%c`输出一个字符（指针所指的字符。
	
即可简化理解为：单引号内为要打印的一个字符，而双引号中的内容为一串要打印的字符串（指针）。
