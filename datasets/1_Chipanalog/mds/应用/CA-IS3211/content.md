#  CA-IS3211 5A 拉、6A 灌、 5.7-kVRMS 光耦兼容单通道隔离式栅极驱动器


# 1. 产品特性
• 光耦输入的 5.7 kVRMS单通道隔离式栅极驱动器
• 输出峰值电流：5A 拉 / 6A 灌
• 最大 30V 输出驱动电源电压
• 8V (B) 或 12V (C) VCC 欠压锁定阈值
• 轨到轨输出
• 70 ns（典型值）传输延迟
• 25 ns（最大）部件对部件延迟匹配
• 35 ns（最大）脉冲宽度失真
• 150 kV/μs（最小）共模瞬态抗扰度（CMTI）
• 隔离栅寿命大于 40 年
• 输入级最高反向耐压 7 V，并支持互锁
• 宽体 SOIC6-WB/SOIC8-WB 封装，气隙和爬电距离
大于 8.5 mm
• 工作结温范围 TJ：-40°C 到 150°C
• 安全相关认证：（认证中）
- 8000 VPK 增强隔离耐压，根据 DIN V VDE V0884-
11: 2017-01(SOIC6-WB/SOIC8-WB)
- 5300 VPK 基本隔离耐压，根据 DIN V VDE V0884-
11: 2017-01(DUB8)
- 5.7 kVRMS隔离，1 分钟，根据 UL 1577(SOIC6-
WB/SOIC8-WB)
- 3.75 kVRMS隔离，1 分钟，根据 UL 1577(DUB8)
- TUV 认证，根据 EN61010-1:2010+A1


# 2. 应用
• 工业电机控制驱动器
• 工业不间断电源（UPS）
• 太阳能逆变器
• 充电桩
• 储能变流器


# 3. 概述
CA-IS3211 是一款光耦兼容的单通道隔离式栅极驱动器，
可用于驱动 MOSFET、IGBT 和 SiC 器件。隔离等级达到
5.7kVRMS，芯片可提供 5A 拉、6A 灌输出峰值电流能力。
高达 30V 的电源电压范围允许使用双极性电源来有效驱
动 IGBT 和 SiC 功率 FET。该芯片的性能亮点包括：高共
模瞬态抗扰度（CMTI）、低传输延迟、低脉冲宽度失真。
严格的工艺控制使得芯片一致性较好。输入级是模拟二
极管，与传统的光耦隔离栅极驱动器的 LED 相比，具有
更好的长期可靠性和老化特性。高性能和高可靠性使得
该芯片适用于工业电源、光伏逆变器、车载充电器、直
流电机控制以及汽车空调与加热系统。CA-IS3211 可以
驱动高压侧及低压侧的功率管，既能够完全兼容传统的
光耦栅极驱动器，又显著提高了驱动的性能。
器件信息
器件信息
---table begin---
Table tile:CA-IS3211器件信息表
| 器件型号     | 封装      | 封装尺寸（标称值）   |
| ------------ | --------- | ------------------- |
| CA-IS3211VBJ | SOIC6-WB  | 7.5 mm x 4.68 mm    |
| CA-IS3211VCJ | SOIC6-WB  | 7.5 mm x 4.68 mm    |
| CA-IS3211VBG | SOIC8-WB  | 7.5 mm x 5.85 mm    |
| CA-IS3211VCG | SOIC8-WB  | 7.5 mm x 5.85 mm    |
| CA-IS3211SBG | SOIC8-WB  | 7.5 mm x 5.85 mm    |
| CA-IS3211SCG | SOIC8-WB  | 7.5 mm x 5.85 mm    |
| CA-IS3211VCU | DUB8      | 9.2 mm x 6.35 mm    |
---table end---


# 4. 订购指南
表 4-1 有效订购零件编号
---table begin---
Table tile:CA-IS3211有效订购零件编号表
| 型号          | 输出方式        | UVLO 电压 (V) | 隔离耐压 (Vpk) | 封装      |
| ------------- | --------------- | -------------- | --------------- | --------- |
| CA-IS3211VBJ  | Single Vout Pin | 8              | 8000            | SOIC6-WB  |
| CA-IS3211VCJ  | Single Vout Pin | 12             | 8000            | SOIC6-WB  |
| CA-IS3211VBG  | Single Vout Pin | 8              | 8000            | SOIC8-WB  |
| CA-IS3211VCG  | Single Vout Pin | 12             | 8000            | SOIC8-WB  |
| CA-IS3211SBG  | Split Output    | 8              | 8000            | SOIC8-WB  |
| CA-IS3211SCG  | Split Output    | 12             | 8000            | SOIC8-WB  |
| CA-IS3211VCU  | Single Vout Pin | 12             | 5300            | DUB8      |

# 6. 引脚功能描述
# 6.1表 6-1 CA-IS3211VBJ/ CA-IS3211VCJ SOIC6-WB 引脚功能描述
---table begin---
Table tile:CA-IS3211VBJ/ CA-IS3211VCJ SOIC6-WB 引脚功能描述表
| 引脚名称 | 引脚编号 | 类型 | 描述         |
|----------|---------|------|--------------|
| ANODE    | 1       | I    | 正极         |
| NC       | 2       | -    | 无连接       |
| CATHODE  | 3       | I    | 负极         |
| VEE      | 4       | P    | 负输出级电源轨 |
| VOUT     | 5       | O    | 栅极驱动输出  |
| VCC      | 6       | P    | 正输出级电源轨 |
1. P 代表电源， I 代表输入，O 代表输出
---table end---

# 6.2表 6-2 CA-IS3211VBG/ CA-IS3211VCG SOIC8-WB, CA-IS3211VCU DUB8 引脚功能描述
---table begin---
Table tile: CA-IS3211VBG/ CA-IS3211VCG SOIC8-WB, CA-IS3211VCU DUB8 引脚功能描述表
| 引脚名称 | 引脚编号 | 类型 | 描述         |
|----------|---------|------|--------------|
| NC       | 1       | -    | 无连接       |
| ANODE    | 2       | I    | 正极         |
| CATHODE  | 3       | I    | 负极         |
| NC       | 4       | -    | 无连接       |
| VEE      | 5       | P    | 负输出级电源轨 |
| VOUT     | 6       | O    | 栅极驱动输出  |
| NC       | 7       | -    | 无连接       |
| VCC      | 8       | P    | 正输出级电源轨 |
2. P 代表电源， I 代表输入，O 代表输出
---table end---


# 6.3表 6-2 CA-IS3211SBG/ CA-IS3211SCG SOIC8-WB 引脚功能描述
---table begin---
Table tile:CA-IS3211SBG/ CA-IS3211SCG SOIC8-WB 引脚功能描述表
| 引脚名称 | 引脚编号 | 类型 | 描述            |
|----------|---------|------|-----------------|
| NC       | 1       | -    | 无连接          |
| ANODE    | 2       | I    | 正极            |
| CATHODE  | 3       | I    | 负极            |
| NC       | 4       | -    | 无连接          |
| VEE      | 5       | P    | 负输出级电源轨   |
| OUTL     | 6       | O    | 栅极驱动下拉输出 |
| OUTH     | 7       | O    | 栅极驱动上拉输出 |
| VCC      | 8       | P    | 正输出级电源轨   |
3. P 代表电源， I 代表输入，O 代表输出
---table end---


# 7. 产品规格
# 7.1. 绝对最大额定值
在自然通风条件下的工作温度范围内（除非另外说明）(1)
---table begin---
Table tile:CA-IS3211绝对最大额定值表
| 参数               | 最小值       | 最大值        | 单位   |
| ------------------ | ------------ | ------------- | ------ |
| IF(AVG)            | 平均输入电流 | -25           | mA     |
| IF(TRAN)           | 瞬态峰值输入电流（<1us pulse, 300ps） | 1 | A      |
| VR(MAX)            | 反向输入电压  | 7             | V      |
| VCC - VEE          | 输出电源电压  | -0.3          | 32 V   |
| VOUT               | 输出信号电压  | VEE - 0.3     | VCC + 0.3 | V  |
| TJ (2)             | 结温          | -40           | 150 °C |
| Tstg               | 贮存温度      | -65           | 150 °C |
---table end---


# 7.2. ESD 额定值
---table begin---
Table tile:CA-IS3211ESD 额定值表
| 数值                                 | 单位   |
| ------------------------------------ | ------ |
| 静电放电 (HBM)，根据 ANSI/ESDA/JEDEC JS-0011 | ±4000  V |
| 组件充电模式(CDM)，根据 JEDEC specification JESD22-C1012 | ±2000  V |
---table end---


# 7.3. 建议工作条件
.在自然通风条件下的工作温度范围内（除非另外说明）
---table begin---
Table tile:CA-IS3211建议工作条件表
| 参数                                | 最小值 | 典型值 | 最大值 | 单位 |
| ----------------------------------- | ------ | ------ | ------ | ---- |
| VCC 输出电源电压（VCC - VEE）        |        |        |        | V    |
| 12V UVLO 版本                        | 14     | 30     |        | V    |
| 8V UVLO 版本                         | 10     | 30     |        | V    |
| IF(ON) 输入二极管正向电流（二极管“导通”） | 7      | 16     |        | mA   |
| VF(OFF) 正极电压-负极电压（二极管“关断”）  | -5.5   | 0.9    |        | V    |
| TJ 结温                              | -40    |        | 150    | °C   |
| TA 环境温度                          | -40    |        | 125    | °C   |
---table end---


# 7.4. 热量信息
| 封装      | RθJA 结至环境的热阻 | RθJC(top) 结至外壳（顶部）的热阻 | RθJB 结至电路板的热阻 | ΨJT 结至顶部特征参数 | ΨJB 结至电路板特征参数 
---table begin---
Table tile:CA-IS3211热量信息表

| --------- | ------------------ | -------------------------------- | ------------------- | ------------------ | -------------------- |
| SOIC8-WB  | 110.1 °C/W         | 51.7 °C/W                        | 66.4 °C/W           | 16.0 °C/W         | 64.5 °C/W            |
| SOIC6-WB  | 126 °C/W           | 66.1 °C/W                        | 62.8 °C/W           | 29.6 °C/W         | 60.8 °C/W            |
| DUB8      | 73.3 °C/W          | 63.2 °C/W                        | 43.0 °C/W           | 27.4 °C/W         | 42.7 °C/W            |
| 单位      | °C/W               | °C/W                             | °C/W                | °C/W               | °C/W                 |
---table end---


# 7.5. 功耗额定值
---table begin---
Table tile:CA-IS3211功耗额定值表
| 参数                        | 测试条件                                   | 最小值 | 典型值 | 最大值 | 单位   |
| --------------------------- | ------------------------------------------ | ------ | ------ | ------ | ------ |
| PD 输入端和输出端最大功率耗散(1) | VCC = 20V, IF = 10mA, 10-kHz, 50%占空比， 方波， 180nF负载，TA = 25°C |        | 750    |        | mW     |
| PD1 最大输入功率耗散(2)     |                                            |        | 10     |        | mW     |
| PD2 最大输出功率耗散         |                                            |        |        | 740    | mW     |
(1) 超过 25°C 室温，以 6mW/°C 降低
(2) 推荐最大 PD1 = 40mW。绝对最大值 PD1 = 55mW
---table end---


# 7.6. 绝缘规格
---table begin---
Table tile:CA-IS3211绝缘规格表
| 参数            | 测试条件                                           | 最小值 | 典型值 | 最大值 | 单位    | G/J  | U    |
| --------------- | -------------------------------------------------- | ------ | ------ | ------ | ------- | ---- | ---- |
| CLR 外部气隙（间隙）1 | 端子间的最短隔空距离                            | >8.5   |        | >6.1   | mm      |      |      |
| CPG 外部爬电距离 | 端子之间沿壳体最短距离                         | >8.5   |        | >6.8   | mm      |      |      |
| DTI 隔离距离      | 最小内部间隙（内部距离)                       | >28    |        | >28    | μm      |      |      |
| CTI 相对漏电指数  | DIN EN 60112 (VDE 0303-11)；IEC 60112           | >600   |        | >600   | V       |      |      |
| 材料组          | 依据 IEC 60664-1                                 |        | I      |        |         |      |      |
| IEC 60664-1 过压类别 | 额定市电电压≤ 300 VRMS                        |        | I-IV   |        |         |      |      |
|                  | 额定市电电压≤ 400 VRMS                        |        | I-III  |        |         |      |      |
| DIN V VDE V 0884-11  | （VDE V 0884-11）2                               |        |        |        |         |      |      |
| VIORM 最大重复峰值隔离电压 | 交流电压(双极)                             | 2121   |        | 566    | VPK     |      |      |
| VIOWM 最大工作隔离电压 | 交流电压; 时间相关的介质击穿 (TDDB) 测试      | 1500   |        | 400    | VRMS    |      |      |
|                  | 直流电压                                         | 2121   |        | 566    | VDC     |      |      |
| VIOTM 最大瞬态隔离电压 | VTEST = VIOTM，t = 60 s (认证);                | 8000   |        | 5300   | VPK     |      |      |
|                  | VTEST = 1.2 × VIOTM，t= 1 s (100% 产品测试)    |        |        |        |         |      |      |
| VIOSM 最大浪涌隔离电压 | 测试方法 依据 IEC 62368，1.2/50 μs 波形，   | 8000   |        | 5000   | VPK     |      |      |
|                  | VTEST = 1.6 × VIOSM =12800VPK                 |        |        |        |         |      |      |
| qpd 表征电荷 4  | 方法 a，输入/输出安全测试子类 2/3 后，           |        |        | ≤5    | pC      |      |      |
|                  | Vini = VIOTM，tini = 60 s;                    |        |        |        |         |      |      |
|                  | Vpd(m) = 1.2 × VIORM，tm = 10 s               |        |        |        |         |      |      |
|                  | 方法 a，环境测试子类 1 后，                     |        |        | ≤5    | pC      |      |      |
|                  | Vini = VIOTM，tini = 60 s;                    |        |        |        |         |      |      |
|                  | Vpd(m) = 1.6 × VIORM，tm = 10 s               |        |        |        |         |      |      |
|                  | Method b1， 常规测试 (100% 生产测试) 和前期    |        |        | ≤5    | pC      |      |      |
|                  | 预处理(抽样测试)                                |        |        |        |         |      |      |
|                  | Vini = 1.2 × VIOTM，tini = 1 s;               |        |        |        |         |      |      |
|                  | Vpd(m) = 1.875 × VIORM，tm = 1 s              |        |        |        |         |      |      |
| CIO 栅电容，输入到输出 5 | VIO = 0.4 × sin (2πft)， f = 1 MHz          |        |        | 0.5    | pF      |      |      |
| RIO 绝缘电阻，输入到输出 5 | VIO = 500 V，TA = 25°C                        | >1012  |        |        | Ω       |      |      |
|                  | VIO = 500 V，100°C ≤ TA ≤ 125°C                | >1011  |        |        | Ω       |      |      |
|                  | VIO = 500 V at TS = 150°C                     | >109   |        |        | Ω       |      |      |
| 污染度 2           | 气候类别 40/125/21                               |        |        |        |         |      |      |
| UL 1577          |                                                  |        |        |        |         |      |      |
| VISO 最大隔离电压 | VTEST = VISO ，t = 60 s (认证);                | 5700   |        | 3750   | VRMS    |      |      |
|                  | VTEST = 1.2 × VISO ，t = 1 s (100%生产测试)    |        |        |        |         |      |      |
---table end---


# 7.7. 安全相关认证
---table begin---
Table tile:CA-IS3211安全相关认证表
| 认证       | 标准                                           | 型号              | 瞬态隔离电压 (Vpk) | 重复峰值隔离电压 (Vpk) | 浪涌隔离电压 (Vpk) | 保护电压 (VRMS) |
|------------|------------------------------------------------|-------------------|--------------------|-------------------------|-------------------|----------------|
| VDE        | DIN V VDE V 0884-11:2017-01                   | 增强绝缘 (SOIC6-WB/SOIC8-WB) | 8000               | 2121                    | 8000              | 5700           |
|            |                                                | 基本绝缘 (DUB8)             | 5300               | 566                     | 5000              | 3750           |
| UL         | UL1577 器件程序认证                          | 所有型号                  | -                  | -                       | -                 | -              |
| TUV        | EN61010-1:2010+A1                             | SOIC6-WB/SOIC8-WB    | -                  | -                       | -                 | 5700           |
|            |                                                | DUB8                      | -                  | -                       | -                 | 3750           |
| 证书编号   | 认证中                                          | 所有型号                  | -                  | -                       | -                 | -              |
|            | E511334-20200117                               | 所有型号                  | -                  | -                       | -                 | -              |
|            | CN23RC4J 001                                   | 所有型号                  | -                  | -                       | -                 | -              |

---table end---


# 7.8. 安全限值
---table begin---
Table tile:CA-IS3211安全限值表
| 参数                      | 测试条件                                       | 最小值 | 典型值 | 最大值 | 单位 |
| ------------------------- | ---------------------------------------------- | ------ | ------ | ------ | ---- |
| IS 安全输出、输出或电源电流 | RqJA = 126°C/W, VI = 15V, TJ = 150°C, TA = 25°C |        | 50     |        | mA   |
|                           | RqJA = 126°C/W, VI = 30V, TJ = 150°C, TA = 25°C |        | 25     |        | mA   |
| PS 安全输入、输出或总功耗 | RqJA = 126°C/W, TJ = 150°C, TA = 25°C           |        |        | 750    | mW   |
| TS 最大安全工作温度(1)    |                                              |        |        | 150    | ℃    |
(1)对于这个特定的器件，最大安全温度 TS 等于最大结温 TJ，最大结温参考公式如下：TJ(max)=TS=TA+RqJA*PS
---table end---


# 7.9. 电气特性
除非有额外说明，本表格典型值都是在 TA = 25°C，VCC-VEE=15V，VEE=GND 条件下的结果。所有最小值和最大值都是在建议工作条件（TJ = -
40 至 150°C，IF(on)=7mA 至 16mA， VEE=GND，VCC=15V 至 30V，VF(off)=-5V 至 0.8V）下的结果。
---table begin---
Table tile:CA-IS3211电气特性表
| 参数              | 测试条件                                            | 最小值 | 典型值 | 最大值 | 单位    |
| ----------------- | --------------------------------------------------- | ------ | ------ | ------ | ------- |
| 输入              |                                                     |        |        |        |         |
| IFLH 正向输入电流阈值（低到高） | Vout > 5 V, Cg = 1 nF                          | 1.5    | 2.8    | 4      | mA      |
| VF 正向输入电压      | IF = 10 mA                                        | 1.8    | 2.1    | 2.4    | V       |
| VF_HL 输入电压阈值（高到低） | V < 5 V, Cg = 1 nF                               |        |        | 0.9    | V       |
| ∆VF/∆T 正向输入电压温度系数 | IF = 10 mA                                        | 1.5    | 1.8    |        | mV/°C   |
| VR 输入反向击穿电压    | IR = 10 uA                                        | 7      |        |        | V       |
| CIN 输入电容        | F = 0.5 MHz                                       | 15     |        |        | pF      |
| 输出              |                                                     |        |        |        |         |
| IOH 高电平峰值输出电流  | IF = 10 mA, VCC = 15 V, CLOAD = 0.18uF, CVDD = 10uF, 脉冲宽度<10us | 3      | 5      | A       |
| IOL 低电平峰值输出电流  | VF = 0 V, VCC = 15 V, CLOAD = 0.18uF, CVDD = 10uF, 脉冲宽度<10us | 3.5    | 6      | A       |
| VOH 高电平输出电压    | IF = 10 mA, IO = -20mA（相对于 VCC）               | 0.07   | 0.11   | 0.36   | V       |
|                        | IF = 10 mA, IO = 0mA                               |        |        | VCC    | V       |
| VOL 低电平输出电压     | VF = 0 V, IO = 20mA                               | 10     | 25     | mV      |
| ICC_H 输出电源电流（二极管导通） | IF = 10 mA, IO = 0mA                              | 1.13   | 2.2    | mA      |
| ICC_L 输出电源电流（二极管关断） | VF = 0 V, IO = 0mA                               | 1.05   | 2      | mA      |
| 欠压锁定（12V UVLO）   |                                                     |        |        |        |         |
| UVLOR 输出欠压锁定（VCC 上升） | VCC Rising, IF = 10mA                           | 10.9   | 12.1   | 13.3   | V       |
| UVLOF 输出欠压锁定（VCC 下降） | VCC Falling, IF = 10mA                          | 9.9    | 11.1   | 12.3   | V       |
| UVLOHYS UVLO 迟滞     | 1.0                                               |        |        |        | V       |
| 欠压锁定（8 V UVLO）    |                                                     |        |        |        |         |
| UVLOR 输出欠压锁定（VCC 上升） | VCC Rising, IF = 10mA                           | 7.3    | 8.1    | 8.9    | V       |
| UVLOF 输出欠压锁定（VCC 下降） | VCC Falling, IF = 10mA                          | 6.7    | 7.4    | 8.2    | V       |
| UVLOHYS UVLO 迟滞     | 0.7                                               |        |        |        | V       |
---table end---


# 7.10. 开关特性
除非有额外说明，本表格典型值都是在 TA = 25°C，VCC-VEE=30V，VEE=GND 条件下的结果。所有最小值和最大值都是在建议工作条件（TJ = -
40 至 150°C，IF(on)=7mA 至 16mA，VEE=GND，VCC=15V 至 30V，VF(off)=-5V 至 0.8V）下的结果。
---table begin---
Table tile:CA-IS3211开关特性表
| 参数           | 测试条件                                           | 最小值 | 典型值 | 最大值 | 单位  |
| -------------- | -------------------------------------------------- | ------ | ------ | ------ | ----- |
| tr 输出信号上升时间 | Cg = 1 nF, FSW = 20 kHz, (50%占空比), VCC = 15 V | 6      | 28     |        | ns    |
| tf 输出信号下降时间 | FSW = 20 kHz, (50%占空比)                          | 4      | 25     |        | ns    |
| tPLH 传输延迟，低到高 |                                               | 40     | 70     | 105    | ns    |
| tPHL 传输延迟，高到低 |                                               | 40     | 60     | 105    | ns    |
| tPWD 脉冲宽度失真   | |tPHL-tPLH| |                                         | 10     | 35     |        | ns    |
| tsk(pp) 部件之间传输延迟偏移 | Cg = 1 nF, VCC = 15 V, IF = 10 mA, FSW = 20 kHz (50%占空比) | 25     |        |        | ns    |
| tUVLO_rec UVLO 恢复时间 | VCC 从 0V 上升到 15V                              | 70     | 100    |        | μs    |
| CMTIH 共模瞬态抗扰度（输出高电平） | IF = 10 mA, VCM = 1500 V, VCC = 30 V, TA = 25°C  | 150    |        |        | kV/μs |
| CMTIL 共模瞬态抗扰度（输出低电平） | VF = 0 V, VCM = 1500 V, VCC = 30 V, TA = 25°C   | 150    |        |        | kV/μs |
---table end---


# 7.11. 典型参数特性
除非有额外说明，VCC=15V，VCC 到 VEE 接 1uF 电容，CLOAD=1nF 用于时序参数测试，CLOAD=180nF 用于 IOH 和 IOL 参数测试，所有参数都是在
建议工作条件（TA = -40 至 125°C）下的结果。


# 8. 参数测量信息
# 8.1. 传输延迟、上升时间和下降时间


# 9. 功能描述
# 9.1. 简述
CA-IS3211 是单通道隔离式栅极驱动器，具有光耦兼容的输入级，可以驱动 MOSFETs、IGBT 和 SiC 器件。该芯片具有 5A
拉和 6A 灌的输出峰值电流能力，最大输出驱动器电源电压为 30V。输入和输出采用全差分双串联高压 SiO2电容器隔离
技术。CA-IS3211 采用工业标准 6 引脚和 8 引脚封装，爬电距离和间隙大于 8.5mm。该芯片工作电压为 1500VRMS，强化
隔离额定值在 60ns 下为 5.7kVRMS，浪涌额定值为 8kVPK。该芯片与传统的光隔离式栅极驱动器完全兼容。
# 9.2. 功能框图
# 9.3. 电源供电
输出电源 VCC支持 10V 到 30V 或 14V 到 30V 的电压范围可选。对于单极性电源应用，VCC 连接至电源的正极，VEE 连接
至电源的 GND。对于双极性电源应用，VCC 连接至正电源，VEE 连接至负电源。IGBT 应用中 VCC 和 VEE 相对于 GND 的典
型值分别为 15V 和-8V，SiC MOSFET 应用中分别为 20V 和-5V。由于功率器件需要在栅极施加一个相对于发射极或源极
的负压来关断，从而防止了由米勒效应注入的电流引起的误开通现象。
# 9.4. 输入级
CA-IS3211 的输入级可以简单等效为模拟二极管，当输入二极管施加正压时，二极管正偏，正向电流 IF会流入模拟二极
管。模拟二极管的正向压降为 2.1V（典型值）。需要使用外部电阻来限制正向电流。推荐的正向电流范围为 7mA 到
16mA。当 IF 超出阈值电流 IFLH（典型值 2.8mA）时，一个高频信号将通过高压 SiO2电容传输过隔离层。接收器检测并
解调该高频信号，驱动 VOUT 被输出高电平。如果正极电压降低到 VF_HL以下或反偏，则栅极驱动输出低电平。
CA-IS3211 还支持互锁架构工作（参阅图 10-3），系统设计者可以使用合适的输入电阻来灵活的选取 3.3V、5.0V 电源来
驱动芯片的输入级。
# 9.5. 输出级
CA-IS3211 系列的输出级采用了特殊的推挽结构（如图 9-2），使得驱动功率管时能够输出更大的峰值电流。输出极上
拉网络采用了一个 P 沟道 MOSFET 和一个 N 沟道 MOSFET 并联的结构。当输出由低至高变化时，NMOS 优先快速短暂
导通，同时可以加快功率管的导通。因此导通阶段输出电阻是两个导通电阻的并联：ROH||RNMOS，N 沟通 MOSFET 的
导通电阻（RNMOS）约为 0.8Ω（仿真结果）。
CA-IS3211 的下拉结构仅包含了一个 N 沟道 MOSFET。由于 MOS 输出级可以提供很小的压降，因此输出电压可以实现
VCC 和 VEE 之间的轨到轨工作。
# 9.6. 欠压锁定（UVLO）
芯片的 UVLO 功能用于防止 IGBT 和 MOSFET 出现欠驱动的情况。在器件启动时 VCC 电压低于 UVLOR，或启动后低于
UVLOF，无论正向输入电流 IF 大小多少，VOUT 输出均保持为低电平。VCC的 UVLO 保护还具有迟滞功能（UVLOHYS）。迟
滞功能为了防止电源电压抖动或噪声引起的误输出现象。
VCC 降至 UVLOF以下后，当电源电压重新升高至 UVLOR，VOUT 输出需要经过 tUVLO_rec 的延迟后才会被设置为高电平。
如下图 9-3 所示。
# 9.7. 有源下拉
有源下拉功能可以在电源 VCC 断开后将 IGBT 或 MOSFET 的栅极拉到低电平状态。当驱动的输出级处于无偏置状态时
（VCC 悬空），输出将被有源钳位电路限制在低电平。在该情况下，上拉 PMOS 和 NMOS 被关断，下拉 NMOS 的栅极通
过一个 500kΩ 的电阻连接到驱动的输出，因此下拉 NMOS 可以将输出电压 VOUT 有效的钳位在 2V 以下。
# 9.8. 短路钳位
短路钳位功能通过在芯片内部专用引脚和 VCC 引脚中间添加一个二极管来实现，在短路情况下将输出引脚 VOUT 拉到略
高于 VCC，从而用来钳位驱动器的输出电压。短路保护功能用来防止 IGBT 和 MOSFET 的栅极出现过压击穿或性能降
低。内部二极管可以承受 10us 的 500mA 脉冲电流和 20mA 的持续电流。也可根据实际需求使用外部肖特基二极管来
提高电流传导能力。
# 9.9. 真值表
表 9-2 列出了 CA-IS3211 的功能模式。
表 9-2 CA-IS3211 的真值表
---table begin---
Table tile:CA-IS3211的真值表
- 当输入电流（IF）小于正向输入电流阈值（IFLH）时：
  - VCC 处于关断状态
  - VOUT 电压低
  - UVLOR 电压约为30V，处于低状态
  - UVLOF 电压约为0V，处于低状态

- 当输入电流（IF）大于正向输入电流阈值（IFLH）时：
  - VCC 处于导通状态
  - VOUT 电压约为UVLOR
  - UVLOF 电压约为0V，处于低状态
  - UVLOR 电压约为30V，处于高状态

- X（未指定条件）：
  - VCC 电压在0V至UVLOR之间
  - UVLOF 电压约为0V，处于低状态
  - UVLOR 电压约为30V，处于低状态
---table end---


# 10. 应用指南
# 10.1. 典型应用
图 10-1 和 10-2 展示了驱动 IGBT 的典型应用。为了实现更好的驱动性能，旁路电容的选择非常重要。推荐设计者使用
0.1uF/50V 陶瓷电容以减小高频噪声，10uF/50V 陶瓷电容以提供更高的峰值电流能力。并且滤波电容需要尽可能靠近
芯片 VCC 和 VEE 引脚。
CA-IS3211 芯片正常工作时，建议正向模拟二极管输入电流 7mA 至 16mA，MCU 无法直接驱动，需要增加额外的电路
或器件。推荐使用以下两种连接方式，如图 10-1 所示，使用 NMOS 和外部电阻串联，MCU 驱动 NMOS 开关即可。如
图 10-2 所示，使用缓冲器与芯片连接，增强 MCU 的驱动能力。
# 10.2. 互锁配置
典型系统应用中，栅极驱动器常用于驱动一组功率管，如图 10-3 所示，采用两路栅极驱动器分别驱动高边和低边的
IGBT。系统正常工作时，MCU 产生一对互补的 PWM 脉冲控制信号，用于控制高边和低边的功率管。系统出现故障
时，MCU 失效或软件错误可能导致 MCU 输出信号同时为高电平，导致高边和低边功率管同时导通，损坏器件。为了
避免这种现象，可采用图 10-3 所示的互锁配置，高边驱动器二极管阳极连接低边驱动器二极管的阴极，高边驱动器二
极管阴极连接低边驱动器二极管的阳极。如果 MCU 的控制信号同时错误保持高电平（或低电平）时，两个模拟二极
管的互锁配置同时进入截止状态，从而防止高、低边的功率管同时导通。
# 10.3. 输入电阻设计
输入电阻可以限制模拟二极管的正向流入电流，芯片正向阈值电流 IFLH 为 2.8mA（典型值），建议的正向电流工作范围
7mA 至 16mA。以图 10-2 典型应用为例，外部输入电阻计算公式如下：
\mathrm{I}_{\mathrm{OH}}=\min\left[5\mathrm{A},\frac{\mathrm{V}_{\mathrm{CC}}-\mathrm{V}_{\mathrm{EE}}}{\left(\mathrm{R}_{\mathrm{NMOS}}||\mathrm{R}_{\mathrm{OH}}+\mathrm{R}_{\mathrm{CON}}+\mathrm{R}_{\mathrm{GFET}_{\mathrm{int}}}\right)}\right]
其中，
- 正向输入电流 IF典型值 10mA（最小值 7mA，最大值 16mA）
- 电源电压 VSUP 为 5V（容差±5%）
- 模拟二极管正向压降 VF 典型值 2.1V（最小值 1.8V，最大值 2.4V）
- 缓冲器输出阻抗 ROH_buf 为 18Ω（最小值 13Ω，最大值 22Ω）
通过以上参数可计算出，外部电阻 REXT范围最小值 196Ω，典型值 262Ω，最大值 300Ω。
# 10.4. 输出驱动电阻设计
外部栅极驱动电阻对功率管设计尤为关键，当功率管开关时，寄生电感、寄生电容、高 dv/dt 和 di/dt 以及二极管反向
恢复时间都可能导致功率管的不良行为或 EMI 问题。栅极驱动电阻主要对以下三个方面产生影响：驱动电流、开关损
耗、上升和下降时间。因此，设计者在实际选取驱动电阻时，需要平衡方案的综合性能参数。
IOH 峰值电流估算公式：
\mathrm{R_{EXT}=\frac{V_{SUP}-V_{F}}{I_{F}}-R_{OH_{\downarrow}buf}}
其中，
- RGON是外部栅极导通电阻
- RGFET_int 是功率管内部栅极电阻（需查找功率管数据表）
IOL峰值电流估算公式：
\mathrm I_{\mathrm OL}=\min\left[6A,\frac{\mathrm V_{\mathrm CC}-\mathrm V_{\mathrm EE}}{\left(\mathrm R_{\mathrm OL}+\mathrm R_{\mathrm GOFF}+\mathrm R_{\mathrm GFET_{\mathrm int}}\right)}\right]
其中，
- RGOFF 是外部栅极关断电阻
- RGFET_int 是功率管内部栅极电阻（需查找功率管数据表）
 10.. PCB 布局指南
为了达到 CA-IS3211 的最优性能，PCB 布局时需要遵循以下原则：
• 为了保证电源为稳定性和低噪声，VCC 到 VEE 的旁路电容需要尽可能近的靠近芯片 VCC 和 VEE 引脚，并推荐使用
低 ESR 和低 ESL 的 MLCC 电容。
• 当芯片驱动功率管时，VOUT 存在非常高的 di/dt，VOUT 环路 PCB 走线寄生电感会导致 EMI 和电压振荡问题，故在
设计 PCB 时，芯片应尽可能靠近功率管位置，VOUT 走线尽可能宽，环路走线尽可能短，以降低环路寄生电感。
• 为确保原边侧和副边侧之间的隔离性能，请避免在芯片下方放在任何的 PCB 走线、覆铜、焊盘和过孔。也可以采
用 PCB 开槽工艺，以防止影响隔离性能。
• 当负载较重或开关频率较高时，芯片的损耗也会增加，可以通过适当 PCB 布局将热量传导到 PCB 板上，以达到减
小芯片的温度。建议适当地增加 VCC 和 VEE 引脚的 PCB 覆铜，优先最大程度地增加 VEE 的连接。
• 如果系统有多层板设计，建议在 VCC 和 VEE 层放置大量过孔连接，以减小寄生参数。


# 11. 封装信息
# 11.1. SOIC6-WB 宽体外形尺寸
下图说明了采用 SOIC6-WB 宽体封装大小尺寸图和建议焊盘尺寸图。尺寸以毫米为单位。
# 11.2. SOIC8-WB 宽体外形尺寸
下图说明了采用 SOIC8-WB 宽体封装大小尺寸图和建议焊盘尺寸图。尺寸以毫米为单位。
11.3. DUB8 外形尺寸
下图说明了采用 DUB8 封装大小尺寸图和建议焊盘尺寸图。尺寸以毫米为单位。


# 12. 焊接信息
---table begin---
Table tile:  焊接信息
| 简要说明                   |无铅焊接       |
|------------------------|-----------------|
| 温升速率 (TL至TP)     | 最大3°C/s        |
| 预热温度范围 (Tsmin至Tsmax) | 150°C至200°C    |
| 预热时间 (ts)          | 60~120秒         |
| 温度保持时间 (tL)      | 60~150秒         |
| 峰值温度 (TP)          | 260°C           |
| tP (小于峰值温度5°C内)  | 最长30秒         |
| 降温速率 (TP至TL)     | 最大6°C/s        |
| 常温至峰值温度时间     | 最长8分钟        |
---table end---

# 13. 卷带信息


# 14. 重要声明
上述资料仅供参考使用，用于协助 Chipanalog 客户进行设计与研发。Chipanalog 有权在不事先通知的情况下，保留
因技术革新而改变上述资料的权利。
Chipanalog 产品全部经过出厂测试。 针对具体的实际应用，客户需负责自行评估，并确定是否适用。Chipanalog
对客户使用所述资源的授权仅限于开发所涉及 Chipanalog 产品的相关应用。 除此之外不得复制或展示所述资源， 如
因使用所述资源而产生任何索赔、 赔偿、 成本、 损失及债务等， Chipanalog 对此概不负责。

# 商标信息
Chipanalog Inc.®、Chipanalog®为 Chipanalog 的注册商标。