# riscv-simulator-guide
RISC-V模拟器，相关硬件实现`riscv-isa-sim`以及模拟器pk, bbl的指导手册

## 缘由
本人在研究过程中，由于相关指导以及手册的缺失，以致于只可以通过阅读源代码来了解模拟器实现的机器的工作原理。效率不提，由于没有记录、很多时候甚至会忘却。在这里通过wiki的方式提供一份关于risc-v官方模拟器硬件层spike以及软件上的bbl、pk的简易手册

## 内容
实话实话、纯C++构建的两个工程代码读起来是不难的，但总归有工作量。以下文章的分析多数的视野狭隘、若要刨根问底，还是得通读代码

* [spike,bbl,pk是什么?为什么?怎么用](./contents/00.md)
* [spike+bbl运行linux框架,简介](./contents/01.md)
* [spike调试linux为什么如此慢](./contents/02.md)
