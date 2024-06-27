# CPU_with_5_7_Memory
## Introduction 
CPU is an internal component of the computer system that carries out the instructions of the computer programme. It mainly consists of three components namely control unit, ALU and memory unit. This project is all about making a basic CPU with Basic ALU and 5*7 Memory block. Let me break into smaller topics
<br>

![Final CPU 2.0](https://github.com/icy-chidam/CPU_with_5_7_Memory/assets/124269988/b0c8eff0-a3ec-4b8d-9cda-14c021f7d3ed)
## ALU (Arithmetic Logic Unit)

This integrated circuit carries out arithmetic and logic operations. Arithmetic operations include addition, subtraction, multiplication, etc. While logic operations include Boolean comparisons like AND, NAND, OR, NOR, EXOR, etc.

![Basic ALU](https://github.com/icy-chidam/CPU_with_5_7_Memory/assets/124269988/44b1c235-7a1b-4957-89da-8c697f2704cf)


**Select lines** | **Operations** |
:---------------:|:--------------:|
`000`            | Logical OR
`001`            | Logical AND
`010`            | Logical EXOR
`011`            | Logical NOR
`100`            | Logical NAND
`101`            | Logical EXNOR
`110`            | ADD/SUB
`111`            | Indetermined


![4-Bit ALU](https://github.com/icy-chidam/CPU_with_5_7_Memory/assets/124269988/6101901f-a777-45b7-89d9-ed9402d27028)

## Memory Unit
It’s the component of CPU that stores the data that was sent to it from ALU. Memory unit of any size can be designed using binary cell.Any type of information can be stored in the memory unit in the form of two binary logic levels i.e. logic 1 and logic 0.
### Basic Memory Cell
![Basic_Memory_Cell](https://github.com/icy-chidam/CPU_with_5_7_Memory/assets/124269988/aa8d0673-b2c1-46b0-8354-f8f428d3a53e)
### 7*5 Memory
This Memory block consists of basic building blocks as Binary Cell Memory cells.It also consists of read/write
**Operations** | **Bit** |
:---------------:|:--------------:|
`Read`           | 1
`Write`          | 0 
## Features
* 7-Seg Display
* Can do arithmetic operations like  `Addition` and `Subtraction`
* Can do Logical operations like `OR` `AND` `EXOR` `NOR` `NAND` `EXNOR`
* `READ` and `write` two 4-bits numbers
