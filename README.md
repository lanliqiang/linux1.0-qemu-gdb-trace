# linux1.0-qemu-gdb-trace

Linux 0.11内核
反汇编看内核，有图有真相
非常感谢mik的点拨。因为固有的观念，对INTEL哪里存放物理地址感到困惑。Linux0.11内核这块，存储物理地址的只有CR3和分页结构里的地址。没开启分页时，线性地址就是物理地址，开启分页后，线性地址要根据分页来找到物理地址。
第一章、搭建内核分段分页执行环境。
第二章、内存和外设的准备。
第三章、布置中断表，制作进程环境，切换到进程0。
第四章、拷贝新进程，及进程0的最后使命。
