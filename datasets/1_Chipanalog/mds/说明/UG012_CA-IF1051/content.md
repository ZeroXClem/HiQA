 # CA-IF1051 系列 CAN 收发器测试板说明


#  1.描述
此份文件描述了 CA-IF1051 系列测试板的相关使用说明，其中有产品介绍、原理图、PCB 布线图、
物料清单以及部分测试数据等。CA-IF1051 测试板可以用来评估 CA-IF1051 系列 CAN 收发器的参数性能
等。


# 2.芯片简介
CA-IF1051 是一款控制区域网络（CAN）收发器，符合 ISO11898-2（2016）高速 CAN 物理层标准。
所有器件均设计用于数据速率高达 5Mbps（兆位每秒）的 CAN FD 网络。该器件支持总线故障保护电压
±58V，具有静音模式，通常也称作仅侦听模式。此外，器件包含许多保护功能，以提高器件和 CAN
的稳定性。


# 3.物料清单
---table begin---
Table tile:UG012_CA-IF1051物料清单表
| Item | Ref Des | Qty | Description                                  | Package     | MFR         |
|------|---------|-----|----------------------------------------------|-------------|-------------|
| 1    | C1      | 1   | Capacitor C0603 -                           | -           | -           |
| 2    | C2, C3, C5 | 3   | Capacitor C0603 -                      | -           | -           |
| 3    | C4, C6  | 2   | Capacitor C0603 -                           | -           | -           |
| 4    | C7      | 1   | Capacitor R-6mm-2 -                         | -           | -           |
| 5    | C8      | 1   | Capacitor C0603 -                           | -           | -           |
| 6    | C9, C11 | 2   | Capacitor C0603 -                           | -           | -           |
| 7    | C10     | 1   | Capacitor C0603 -                           | -           | -           |
| 8    | FBL1, FBL2 | 2   | Inductor C1206_M -                      | -           | -           |
| 9    | J1, J8, J14, J16 | 4   | Header, Unshrouded , 2.54, Male, 3P  | con,hdr,254-3p - | -     |
| 10   | J2, J3, J4, J5, J6, J7, J9, J10, J11, J12, J13, J15, J17, J18, J19, J20, J21 | 17 | Header, Unshrouded , 2.54, Male, 2P  | con,hdr,254-2p - | - |
| 11   | JP1, JP2 | 2   | KF301-2P 接插件 KF301-5.0-2P -            | -           | -           |
| 12   | R1, R5  | 2   | 电阻 R1206 -                                 | -           | -           |
| 13   | R2      | 1   | 电阻 R1206 -                                 | -           | -           |
| 14   | R3      | 1   | 电阻 R1206 -                                 | -           | -           |
| 15   | R4, R6  | 2   | 电阻 R1206 -                                 | -           | -           |
| 16   | S1, S2, S3, S4, S5 | 5   | SMA 连接器 SMA_CON_DIP_DIR -            | -           | -           |
| 17   | U1      | 1   | CA-IF1051 SOP-08 Chipanalog                 | -           | -           |
---table end---


#  4.测试仪器
直流电源、500MHz 带宽示波器安捷伦 DSOX3054T、6.5 位多功能万用表安捷伦 34465A、高频信号发
生器等。


# 5. 硬件连接
1. 将直流电压源连接到 T1 和 T2；
2. 函数发生器输出一定频率和幅值的信号，连接到信号的输入端 TXD；
3. 通过示波器测量各个通道输出端，用示波器观察 TXD、CANH、CANL、RXD 等管脚的波形。



# 6.测试示例
略(详细测试框图见规格书)。



# 7.PCB 布线建议
1. CA-IF1051 电源管脚滤波电容的位置放尽可能摆放在靠近芯片的管脚，距离应控制在2mm以内，如下
图6和图7所示。当需要在供电电源线和地线中放置过孔，应放置在电容相对于芯片管脚的外侧，而
非放置在电容和芯片之间，以减少过孔寄生电感的影响，如下图8和图9所示。
2. CA-IF1051总线侧为差分输出，差分走线尽量保证等长，避免直角及锐角走线。




#  重要声明
上述资料仅供参考使用，用于协助 Chipanalog 客户进行设计与研发。Chipanalog 有权在不事先通知
的情况下，保留因技术革新而改变上述资料的权利。

