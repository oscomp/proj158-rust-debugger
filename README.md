# proj158-rust-debugger
支持Rust语言的源代码级内核调试工具

### 项目描述

方便的源代码级调试工具，对监测程序运行状态和理解程序的逻辑十分重要；高效的Rust语言跟踪能力，是Rust操作系统内核开发的必要工具，对基于Rust的操作系统教学和实验很有帮助。本项目希望在扩展已有源代码调试工具的Rust语言支持能力，实现在QEMU和RISC-V开发板上的Rust教学操作系统的源代码调试。

### 所属赛道

2022全国大学生操作系统比赛的“OS功能设计”赛道

### 参赛要求

* 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生（2022年春季学期或之后本科毕业的大一~大四的学生）
* 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖
* 请遵循“2022全国大学生操作系统比赛”的章程和技术方案要求
### 项目导师

向勇

* github [https://github.com/xyongcn](https://github.com/xyongcn)
* email [xyong@tsinghua.edu.cn](mailto:xyong@tsinghua.edu.cn)
### 难度

高

### 特征

* Rust
* GDB
* OpenOCD
### License

* GPL3
### 预期目标

在VSCode编辑器的已有debugger插件基础上，扩展对Rust语言和操作系统内核特征的源代码级跟踪分析能力。

* 函数调用栈跟踪：函数名和调用参数；
* Rust异步函数栈跟踪；
* 内核数据结构信息获取和展现；
* 系统调用过程跟踪；
* 进程切换过程跟踪；
* 中断处理过程跟踪；
* 对被跟踪内核运行环境的适配：QEMU、U740开发板、eBPF
