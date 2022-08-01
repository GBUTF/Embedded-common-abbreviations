# Embedded-common-abbreviations
嵌入式常见缩写及说明
# 参考
https://blog.csdn.net/weixin_42214698/article/details/120597734?ops_request_misc=&request_id=&biz_id=102&utm_term=FLITF&utm_medium=distribute.pc_search_result.none-task-blog-2~all~sobaiduweb~default-2-120597734.142^v37^pc_rank_34&spm=1018.2226.3001.4187
## 1.英文缩写
ARM：Advanced RISC Machine

AAPCS：ARM Architecture Process call standard ARM体系结构过程调用标准

RISC： Reduced Instruction Set Computer 精简指令集计算机

RTOS：Real Time Operating System 实时操作系统

DMA：Direct Memory Access 存储器直接访问

EXTI: External Interrupts 外部中断

FSMC: Flexible static memory controller 可变静态存储控制器

FPB：flash patch and breakpoint FLASH 转换及断电单元

HSE：Hign speed external 高速内部时钟

HSI: High speed internal 高速外部时钟

LSE: Low Speed external 低速外部时钟

LSI: Low Speed Internal 低速内部时钟

LSU: load store unit 存取单元

PFU: prefetch unit 预取单元

ISR：Interrupt Service Routines 中断服务程序

NMI: Nonmaskable Interrupt 不可屏蔽中断

NVIC: Nested Vectored Interrupt Controller

MCU:Microcontroller Unit 微控制单元又称单片微型计算机(Single Chip Microcomputer )或者单片机，是把中央处理器(Central Process Unit；CPU)的频率与规格做适当缩减，并将内存(memory)、计数器(Timer)、USB、A/D转换、UART、PLC、DMA等周边接口，甚至LCD驱动电路都整合在单一芯片上，形成芯片级的计算机，为不同的应用场合做不同组合控制。诸如手机、PC外围、遥控器，至汽车电子、工业上的步进马达、机器手臂的控制等，都可见到MCU的身影。

MPU: Memory Protection Unit

MIPS:million instructions per second 每秒能执行的百万条指令的条数

RCC：Reset and clock control 复位和时钟控制

RTC: Real-Time Clock 实时时钟

IWDG: independent watchdog

WWDG：Window watchdog

TIM：timer 定时器

##2.端口
AFIO：alternate function IO 复用IO端口

GPIO：general purpose input/output 通用IO端口

IOP（A-G）:IO port A - IO port G (例如：IOPA:IO port A)

CAN：Controller area network

FLITF：The Flash memory interface 闪存存储器接口

I2C： Inter-integrated circuit 内置集成电路

IIS： integrate interface of sound 集成音频接口

JTAG：joint test action group 联合测试行动小组

SPI：Serial Peripheral Interface

SDIO: SD I/O

UART: Universal Synchr./Asynch. Receiver Transmitter

USB: Universal Serial Bus

##3. 寄存器相关
CPSP： Current Program Status Register 当前程序状态寄存器

SPSP： saved program status register 程序状态备份寄存器

CSR：clock control/status register 时钟控制状态寄存器

LR： link register 链接寄存器

SP： stack pointer 堆栈指针

MSP: main stack pointer 主堆栈指针

PSP：process stack pointer 进程堆栈指针

PC： program counter 程序计数器

##4.调试相关
ICE：in circuit emulator 在线仿真

ICE Breaker 嵌入式在线仿真单元

DBG：debug 调试

IDE：integrated development environment 集成开发环境

DWT: data watchpoint and trace 数据观测与跟踪单元

ITM: instrumentation trace macrocell 测量跟踪单元

ETM： embedded trace macrocell 嵌入式追踪宏单元

TPIU：trace port interface unit 跟踪端口接口单元

TAP： test access port 测试访问端口

DAP: debug access prot 调试访问端口

TP: trace port 跟踪端口

DP：debug port 调试端口

SWJ-DP: serial wire JTAG debug port 串行-JTAG 调试接口

SW-DP: serial wire debug port 串行 调试接口

JTAG-DP：JTAG debug port JTAG 调试接口

##5.系统类
IRQ： interrupt request 中断请求

FIQ： fast interrupt request 快速中断请求

SW：software 软件

SWI： software interrupt 软中断

RO:read only 只读（部分）

RW:read write 读写（部分）

ZI:zero initial 零初始化（部分）

BSS：Block Started by Symbol 以符号开始的块（未初始化数据段）

##6.总线
Bus Matrix 总线矩阵

Bus Splitter 总线分割

AHB：advanced High-preformance Bus 高级高性能总线 AHB用于高性能、高时钟频率的系统结构，典型的应用如ARM核与系统内部的高速RAM、NAND FLASH、DMA、Bridge的连接。

APB:advanced peripheral bus 外围总线 APB用于连接外部设备，对性能要求不高，而考虑低功耗问题。

APB1: low speed APB 低速外围总线

APB2: high speed APB 高速外围总线

ASB ：Advanced System Bus 系统总线 ASB是AHB的一种替代方案。

PPB： Private Peripheral Bus 专用外设总线

##7.杂类
ALU：Arithmetic Logical Unit 算术逻辑单元

CLZ： count leading zero 前导零计数（指令）

SIMD： single instruction stream multiple data stream 单指令流，多数据流

VFP： vector floating point 矢量浮点运算

##8.词汇/词组
Big Endian 大段存储模式

Little Endian 小段存储模式

context switch 任务切换（上下文切换）（CPU寄存器内容的切换）

task switch 任务切换

literal pool 数据缓冲池

##9.词汇类/单词
arbitration 仲裁

access 访问

assembler 汇编器

disassembly 反汇编

binutils 连接器

bit-banding 位段（技术）

bit-band alias 位段别名

bit-band region 位段区域

banked 分组

buffer 缓存/

ceramic 陶瓷

fetch 取指

decode 译码

execute 执行

Harvard 哈佛（架构）

handler 处理者

heap 堆

stack 栈

latency 延时

load (LDR) 加载（存储器内容 加载到 寄存器Rn）

store (STR) 存储（寄存器Rn内容 存储到 存储器）

Loader 装载器

optimization 优化

process 进程/过程

thread 线程

prescaler 预分频器

prefetch 预读/预取指

perform 执行

pre-emption 抢占

tail-chaining 尾链

late-arriving 迟到

resonator 共振器

##10.指令相关
instructions 指令

pseudo-instruction 伪指令

directive 伪操作

comments 注释

FA full ascending 满栈递增（方式）

EA empty ascending 空栈递增（方式）

FD full desending 满栈递减（方式）

ED empty desending 空栈递减（方式）
————————————————
版权声明：本文为CSDN博主「我把夜熬成了白_」的原创文章，遵循CC 4.0 BY-SA版权协议，转载请附上原文出处链接及本声明。
原文链接：https://blog.csdn.net/weixin_42214698/article/details/120597734
