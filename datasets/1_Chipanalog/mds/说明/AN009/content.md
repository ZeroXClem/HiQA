# 利用隔离运算放大器构建隔离电源反馈环路


# 1 .概述
误差放大器作为开关电源中的重要器件，用作输出电压的误差放大，并基于误差信号产生反馈控制。误差放大器
的性能直接影响了开关电源的输出精度和瞬态响应速度。传统的隔离电源设计通常采用光耦实现误差信号的隔离传输，
如图 2 所示。本文首先将“光耦+TL431”反馈环路与隔离放大器(CA-IS310x) 构成的反馈环路进行了对比，阐述了 CA￾IS310x 在开关电源设计中的优势，并讨论了典型应用中的设计方法和建议。


# 2. 隔离开关电源的工作原理
# 2.1 .工作原理
图 1 所示为隔离开关电源的原理框图，由 PWM 控制与反馈环路、变压器、功率模块，以及输入、输出网络组成。
图中误差放大器将输出电压 Vo 的分压信号与基准电压进行比较，且对所产生的误差信号进行放大。放大后的信
号由 COMP 输出，驱动控制器产生占空比与误差信号成比例的 PWM 控制信号，用于驱动 MOSFET 通断；MOSFET 的
通断则控制变压器传输或储存能量，从而保持稳定的电压输出，并实现原边与副边的电源隔离。为确保隔离电源反馈
环路的稳定性，误差放大器通常采用 Type II 或 Type III 补偿电路。在隔离电源设计中，误差信号需要通过隔离通道从
副边传送到原边的控制器。传统的隔离电源设计通常采用光耦隔离，如图 2 所示；随着集成隔离运算放大器的推广，
考虑到隔离放大器相比于光耦的诸多优势，越来越多的电源设计开始采用隔离放大器。下面，我们就对两种隔离技术
进行说明和对比。
# 2.2. 基于光耦的隔离开关电源
图 2 所示采用光耦实现反馈信号的隔离，其中两个关键元件是：提供 2.5V 参考电压的 TL431 并联型电压基准和光
耦合器。分压电阻 RT、RB用于设置输出电压； RC 和 CC 则用于环路补偿。该反馈电路在传统的隔离电源设计中非常通
用，由于必须为光耦提供一个最小工作电流，R1 作为限流控制不能选择阻值过大的电阻。由此可见，光耦隔离需要消
耗更大功率。该电路中，当输出电压升高时，流过光耦 LED 的电流 i1将增大，一次侧电流 i2随之增大，使得光电晶体
管的集电极电压下降，进而减小 PWM 控制器的占空比，减小输出电压，使其稳定在预设值。由此可见，由 TL431 和
光耦构成的负反馈环路旨在保持稳定的输出电压。当然，设计中需要谨慎考虑环路补偿设计，以确保系统稳定工作。
# 2.3 基于隔离运算放大器的开关电源
图 3 所示电路中，原边控制采用了隔离误差放大器。CA-IS3101/CA-IS3102 隔离运算放大器用作输出电压 VO的误差
信号放大器，并将放大后的误差信号反馈至原边控制器。其中，输出电压 VO通过电阻分压后连接到运算放大器的反相
输入端(−IN)，该信号与作用在同相输入(+IN)引脚的 1.225V 内部基准电压(REFOUT2)相比较，放大后的误差信号 COMP 经
过 OOK 调制器，跨过 SiO2 电容绝缘栅传送到原边控制器。由于输出分压信号连接在运算放大器的反相输入端，如果
输出电压 VO 由于负载阶跃或其它因素而下降，则−IN 引脚电压下降，低于+IN 基准电压，使得 COMP 引脚输出高电平，
通过隔离栅后将 OOK 调制信号还原成模拟信号，输出 EAOUT 和 EAOUT2 随之增大，提高 PWM 控制器占空比，控制变压
器从原边向副边传送功率，以提升输出电压，进而保证稳定的输出电压。图中，在-IN 与 COMP 之间连接阻容元件(Z1, 
Z2)构成误差放大器的补偿网络，以确保反馈环路的工作稳定性。


# 3. 光耦隔离与隔离运算放大器比较
表 1 为“光耦+TL431”方案与 CA-IS3101/CA-IS3102 方案的比较。与常用的光耦方案相比，采用电容隔离误差放大
器在瞬态响应、功率密度和稳定性方面均有大幅提高。光耦隔离器在整个工作周期、高温环境下都具有不确定的电流
传输比，而 CA-IS3101/CA-IS3102 的隔离信号传输特性不随生命周期而改变，并且在−40°C 至+125°C 宽温范围内保持稳
定。另外，CA-IS3101/CA-IS3102 内部集成了宽带运算放大器，在隔离电源设计中能够提供足够快的瞬态相应。器件内
部 1.225 V 的高精度电压基准既提高了输出电压精度及输出稳定度，也提高了系统集成度，省去了外部基准。
表 1. 两种隔离方案的性能比较
---table begin---
Table tile:AN009两种隔离方案的性能比较表
| 特性           | CA-IS310x      | TL431+光耦          |
|--------------|--------------|-----------------|
| 信号隔离传输介质  | 电容隔离       | 光隔离            |
| 基准电压稳定性  | 高            | 低               |
| 基准误差        | <1%           | < 2%             |
| 工作温度范围    | -40°C ~ 125°C | < 85°C          |
| 工作带宽        | 400kHz       | < 80kHz         |
| 响应速度        | 快(< 0.5μs)   | 慢( ~ 5μs)       |
| 增益稳定性      | 稳定          | 存在光衰减        |
| 功耗            | 较低          | 较高             |
| 工作寿命        | > 40 年      | 短               |
| 设计复杂程度    | 简单          | 外部元件多，复杂  |
---table end---


# 4. 隔离运算放大器的补偿设计
# 4.1. EAOUT/EAOUT2 驱动反馈环路
在隔离电源反馈环路采用隔离运算放大器时，误差放大器的环路补偿是保证系统稳定工作的关键因素。图 4 中的
Z1、Z2 构成 CA-IS310x 的补偿网络，从 FB 至 COMP 的传递函数如下：
当改变当 Z1 和 Z2 阻容网络时，可以构成不同的补偿电路，常见的补偿电路包括：Type I (图 5)、Type II (图 6)、
Type III (图 7 和图 8)。
图 6 为 Type II 补偿器。该补偿电路包含 2 个极点和 1 个零点：
fP1=0Hz， \mathrm{f}_{21}=\frac{1}{2\pi\mathrm{R}1*\mathrm{C}1},\mathsf{f}_{\mathsf{P}2}=\frac{1}{2\pi\mathrm{R}1*\mathrm{C}2},C2<<C1；\mathrm{Gain}_{-}\mathrm{Comp}(s)=\frac{1+\mathrm{R}1*\mathrm{C}1*s}{s*\mathrm{R}2(\mathrm{C}1+\mathrm{C}2)*(1+s*\frac{\mathrm{C}1*\mathrm{C}2}{\mathrm{C}1*\mathrm{C}2}*\mathrm{R}1)}, s= 2 ∗ π ∗ f ∗ j
图 7 和图 8 为 Type III 补偿器。该补偿器包含 3 个极点和 2 个零点：
由于 CA-IS310x 误差放大器本身从 COMP 到 EAOUT 的带宽为 400kHz，这一带宽能够支持绝大多数隔离开关电源的
设计。当然，如果系统要求更小尺寸，必须提高开关频率，这种情况下，需要考虑误差放大器 CA-IS310x 的-3dB 带宽。
从输出 VOUT 至补偿器输入 FB，常见的反馈网络如图 10 所示， 其中，左边电路的传递函数为 H(s)=1；右边电路
的传递函数为：H(s) = RB
RB+RT。
从输出 VOUT 至 EAOUT 的信号传递函数为：
Gain_total_1(s)= Gain_op(s) ∗ Gain_Comp(s)*H(s)；
从输出 VOUT 至 EAOUT2的信号传递函数为：
Gain_total_2(s)= 2.6 ∗ Gain_op(s) ∗ Gain_Comp(s)*H(s)
结合以上计算并配合功率级的传递函数，就可以计算出整个系统环路的频响特性及补偿参数。
# 4.2. IOUT 驱动反馈环路
CA-IS3101/CA-IS3102 提供一路电流输出 IOUT，可以直接驱动电源控制器，如图 11 所示。电流 IOUT 是 EAOUT2的镜
像电流，用于直接替代光耦晶体管，驱动电源控制器的 COMP 引脚。
由此，可以求出从 EAOUT2 至 IOUT 的电流信号传递函数为：
\mathrm{Gm}_{-}\mathrm{vi}(s)=-\frac{2}{\mathrm{Rx}};
从电源输出电压 VOUT 至 IOUT 的总体小信号传递函数为：
Gain_total_3(s)= 2.6 ∗ Gain_op(s) ∗ Gain_Comp(s)*H(s)* Gm_vi(s)


# 5. 小结
本文讨论了CA-IS3101/CA-IS3102在隔离开关电源设计中的应用，分析了实际应用中常见的几种补偿网络，并
推导出不同补偿网络的传递函数。



