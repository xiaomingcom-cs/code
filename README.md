# Nachos OS
Nachos系统包括两部分：模拟的硬件系统以及在这些硬件之上运行的操作系统内核。
## Lab1
Nachos系统的安装和调试
* 基本环境配置
  ** 安装gcc MIPS交叉编译器
* 测试Nachos
  ** 进入code/thread/ 运行make命令，可编译生成一个基本的Nachos内核(后续实验将对该内核进行扩展，包括进程同步互斥，文件系统和系统调用)
  ** gdb调试
## Lab2
Nachos的Makefiles
* code/下子目录的Makefile文件
* 各子目录下的Makefile.local文件
* code/目录下的Makefile.dep文件
* code/目录下的Makefile.commom文件
* 如何在其他目录下修改Nachos代码并生成修改后的Nachos系统
## Lab3
利用信号量实现线程同步

## Lab4
分析filesys目录下文件系统和machine目录下DISK硬盘的实现

## Lab5
基本文件系统不能进行扩展(即不能改变文件大小,只能通过复制UNIX文件到nachos文件系统中，本实验要求实现nachos -ap/-hap/-nap
* nachos -ap将UNIX文件追加到nachos文件末尾
* nachos -hap从一个nachos文件的中间开始将一个UNIX文件写入该Nachos文件中
* nachos -nap将一个nachos文件附加到一个nachos文件后面
