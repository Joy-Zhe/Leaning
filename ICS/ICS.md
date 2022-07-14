# Chapter 1
+ definitness/effectively computable/finiteness
### Compiler
+ translate the high level language to the ISA
### ISA: The instruction set architecture 
+ such as x86/powerPC/...
+ all cars have the same ISA , the cars and the planes have the different ISA
+ microarchitecture: such as Ryzen, Core, Pentium...
+ different brand of cars have the different microarchitectures.
## Electronic circuits
# Chapter 2
+ exclusive-or(XOR):异或
+ IEEE754
+ ASCII
+ HEX
# Chapter 3
+ digital logic
+ logic gate：NOT/AND/OR/NAND/NOR/XOR
+ 全加器
+ combinational logic
+ Storage$\rightarrow$R/S Latch (R/S触发器)
+ 主从R/S触发器：在一个cycle内R、S变化只引起一次改变
## 内存
+ D锁存器：一个门控D锁存器只能保存1bit，组合后保存nbits，成为寄存器
1) address: the location of a single space in the memory
2) addressability: the number of bit for each memory location 
# Chapter 4
## The von Neumann Model
+ MAR：存储内存地址的寄存器
+ MDR：存储对应内存值的寄存器
+ PC进入时即为PC+1
1) FETCH
2) DECODE
3) 


# LC-3 ISA
+ R6 R7慎用
+ R6 存放栈