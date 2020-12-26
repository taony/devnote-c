#	1、C语言简介

C 语言是一种通用的高级语言，最初是由丹尼斯·里奇在贝尔实验室为开发 UNIX 操作系统而设计的。C 语言最开始是于 1972 年在 DEC PDP-11 计算机上被首次实现。

在 1978 年，布莱恩·柯林汉（Brian Kernighan）和丹尼斯·里奇（Dennis Ritchie）制作了 C 的第一个公开可用的描述，现在被称为 K&R 标准。

UNIX 操作系统，C编译器，和几乎所有的 UNIX 应用程序都是用 C 语言编写的。由于各种原因，C 语言现在已经成为一种广泛使用的专业语言。

# 2、C语言标准

## 2.1、 C90标准

C89、C90、ANSI C通常指的是同一个C语言标准。1989年，美国国家标准协会(ANSI)推出C语言和C标准库的标准。该标准通常被称为ANSI C。由于该标准是1989年推出的，因此也被称为C89。时隔一年，1990国际标准协会ISO参照ANSI标准，推出一模一样的C语言和C标准库标准，由于该标准是1990年提出的，因此被称为C90标准。因此，C89, C90, ANSI C是同一个标准。

## 2.2、C99标准

1994年，ANSI/ISO联合的组织想要为ANSI C标准加入有限的改动，使C标准在国际化字符、一些明显的缺陷、数值计算上更上一层楼，推出了C99标准。

## 2.3、C11标准

2011年，标准委员会推出了C11标准。



#	3、运行环境

## 3.1、C语言编译器

C 语言编译器用于把源代码编译成最终的可执行程序，一般使用GNU 的 C/C++ 编译器。在Linux或者Unix操作系统下查看GCC的版本，操作如下：

```c
TaonyMacBook:~ taony$ gcc -v
Configured with: --prefix=/Applications/Xcode.app/Contents/Developer/usr --with-gxx-include-dir=/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX.sdk/usr/include/c++/4.2.1
Apple clang version 12.0.0 (clang-1200.0.32.28)
Target: x86_64-apple-darwin20.2.0
Thread model: posix
InstalledDir: /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin
```

