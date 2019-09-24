# LEARN-NOTE
## 1、bitmap整理
## 2、GObject学习、例程 
  git 上传demo
## 3、atuoTool学习、例程
* 1.autoscan->configure.scan->configure.ac  
* 2.aclocal + configure.ac -> aclocal.m4  
* 3.autoconf + configure.ac -> configure  
* 4.autoheader -> config.h.in  
* 5.automake + Makefile.am -> Makefile.in  
* 6./congigure + Makefile.in -> Makefile  
## 4、windbg调试、例程
* 1.设置微软调试符号表、PDB路径  
SRV*C:\mysymbols*http://msdl.microsoft.com/download/symbols  
* 2.设置源文件路径  
D:\Code\MyGit\h3cvdi-client-vdesktop\H3CDCloud_VDI\projects\vdp  
* 3.导入dump
* 4.!analyze -v
## 5、gdb 调试
attach到进程:  
* 1.ps -aux  //查询对应的进程号  
* 2.gdb attach pid  //attach 到指定进程  
* 3.info threads  //显示可调试线程号  
* 4.thread pid  //切换到对应线程  
* 5.bt  //显示堆栈  
	
dump步骤如下：
* 1.删除/vms/crash/_usr_bin_qemu-system-x86_64-hp.0.crash文件
* 2.运行虚机，等待奔溃后，会重新生成_usr_bin_qemu-system-x86_64-hp.0.crash文件
* 3.在/vms/crash/新建一个目录（例如dump）
* 4.执行apport-unpack命令：apport-unpack _usr_bin_qemu-system-x86_64-hp.0.crash dump
* 5.进行dump目录
* 6.执行 gdb /usr/bin/qemu-system-x86_64-hp  CoreDump
## 6、进程间通信学习、例程
包括在10(apue)  
## 7、音视频同步
## 8、vpn服务器搭建
已经完成  
## 9、NDK、JNI、CMAKE、adb
* 1.cmake git fork 教程  
## 10、apue
## 11、libyuv
## 12、patch
## 13、tcpdump
tcpdump -w dump.pcap -i eth0 -vv
## 14、反编译
IDA pro
* 1.F5
* 2.Alt + T
## 15、wireshark
## 16、gstream
## 17、open Gl
## 18、pixman
## 19、surfacefinger
## 20、freeImage
