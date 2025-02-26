# CA-IS382x 高速双通道数字隔离器


# 1. 产品特性
• 信号传输速率：DC to 150Mbps 
• 宽电源电压范围：2.5V to 5.5V 
• 宽温度范围：-40°C to 125°C 
• 无需启动初始化
• 默认输出高电平和低电平选项
• 优异的电磁抗扰度
• 高 CMTI：±150kV/µs (典型值) 
• 低功耗，(典型值): 
▪ 电流为 1.5mA/通道（@5V， 1Mbps ）
▪ 电流为 6.6mA/通道（@5V， 100Mbps ）
• 精确时序 (典型值) 
▪ 12ns 传播延迟
▪ 1ns 脉冲宽度失真
▪ 2ns 传播延迟偏差
▪ 5ns 最小脉冲宽度
• 高达 5.7kVRMS的隔离电压（宽体封装）
• 高达 7.5kVRMS的隔离电压（超宽体封装）
• ESD：±8kV HBM 
• 隔离栅寿命：>40 年
• 施密特触发器输入
• 宽体 SOIC8(G)封装，宽体 SOIC16(W)和超宽体
SOIC16(WW)，符合 RoHS 标准


# 2. 应用
• 工业自动化
• 电机控制
• 医疗电子
• 隔离开关电源
• 太阳能逆变器
• 隔离 ADC, DAC 


# 3. 概述
CA-IS382x 是一款高性能 2 通道数字隔离器具有精确的
时序特性和低电源损耗。 在隔离 CMOS 数字 I/O 时，
CA-IS382x 器件可提供高电磁抗扰度和低辐射。所有器
件版本均具有施密特触发器输入，可实现高抗噪性能。
每条隔离通道的逻辑输入和输出缓冲器均由二氧化硅
(SiO2) 绝缘栅隔离。 CA-IS3820 器件具有两个前向双通道，
CA-IS3821 一个前向一个反向两个通道， CA-IS3822 和
CA-IS3821 通道相反，具有一个反向一个前向两个通道。
所有设备都具有故障安全模式选项。 如果输入侧电源
掉电或信号丢失，对于后缀为 L 的设备，默认输出为低，
对于带有后缀 H 的设备，默认输出为高。
CA-IS382x 器件具有高绝缘能力，有助于防止数据总线
或其他电路上的噪声和浪涌进入本地接地端，从而干扰
或损坏敏感电路。 高 CMTI 能力有望保证数字信号的正
确传输。 CA-IS382x 器件采用 8 脚宽体 SOIC，16 脚宽体
SOIC 封装和 16 脚超宽体 SOIC 封装。宽体封装的产品绝
缘耐压均高达 5.7kVRMS，超宽体封装的产品绝缘耐压能
达到 7.5kVRMS。
器件信息
---table begin---
Table tile:CA-IS382x器件信息表
| 零件号   | 封装             | 封装尺寸(标称值)   |
| ------- | ---------------- | ------------------ |
| CA-IS3820 | SOIC8-WB(G)     | 5.85 mm × 7.50 mm  |
| CA-IS3821 | SOIC16-WB(W)    | 10.30 mm × 7.50 mm |
| CA-IS3822 | SOIC16-WWB(WW)  | 10.30 mm × 14.00 mm |
---table end---


通道 A 和 B 被隔离电容隔开。 
GNDA 和 GNDB 分别连接 A 侧信号和 B 侧电源隔离接
地。

# 4. 订购指南
表 4-1 有效订购零件编号
---table begin---
Table tile:CA-IS382x有效订购零件编号表
| 型号           | 输入通道数 (A侧) | 输入通道数 (B侧) | 故障安全输出状态 | 额定耐压 (kV) | 输出使能 | 封装           |
| -------------- | ----------------- | ----------------- | ----------------- | -------------- | -------- | -------------- |
| CA-IS3820LG    | 2                 | 0                 | 低                | 5.7            | No       | SOIC8-WB       |
| CA-IS3820LW    | 2                 | 0                 | 低                | 5.7            | No       | SOIC16-WB      |
| CA-IS3820LWW   | 2                 | 0                 | 低                | 7.5            | Yes      | SOIC16-WWB     |
| CA-IS3820HG    | 2                 | 0                 | 高                | 5.7            | No       | SOIC8-WB       |
| CA-IS3820HW    | 2                 | 0                 | 高                | 5.7            | No       | SOIC16-WB      |
| CA-IS3820HWW   | 2                 | 0                 | 高                | 7.5            | Yes      | SOIC16-WWB     |
| CA-IS3821LG    | 1                 | 1                 | 低                | 5.7            | No       | SOIC8-WB       |
| CA-IS3821LW    | 1                 | 1                 | 低                | 5.7            | No       | SOIC16-WB      |
| CA-IS3821LWW   | 1                 | 1                 | 低                | 7.5            | Yes      | SOIC16-WWB     |
| CA-IS3821HG    | 1                 | 1                 | 高                | 5.7            | No       | SOIC8-WB       |
| CA-IS3821HW    | 1                 | 1                 | 高                | 5.7            | No       | SOIC16-WB      |
| CA-IS3821HWW   | 1                 | 1                 | 高                | 7.5            | Yes      | SOIC16-WWB     |
| CA-IS3822LG    | 1                 | 1                 | 低                | 5.7            | No       | SOIC8-WB       |
| CA-IS3822LW    | 1                 | 1                 | 低                | 5.7            | No       | SOIC16-WB      |
| CA-IS3822LWW   | 1                 | 1                 | 低                | 7.5            | Yes      | SOIC16-WWB     |
| CA-IS3822HG    | 1                 | 1                 | 高                | 5.7            | No       | SOIC8-WB       |
| CA-IS3822HW    | 1                 | 1                 | 高                | 5.7            | No       | SOIC16-WB      |
| CA-IS3822HWW   | 1                 | 1                 | 高                | 7.5            | Yes      | SOIC16-WWB     |
---table end---



#  6. 引脚功能描述
表 6-1 CA-IS382x SOIC8 引脚功能描述
---table begin---
Table tile:CA-IS382x引脚功能描述表
| 引脚名称  | SOIC8引脚编号 | 类型           | 描述                                                                 |
|---------|---------|----------------|----------------------------------------------------------------------|
| VDDA    | 1       | 电源           | A 侧电源电压                                                          |
| VI1/VO1 | 2       | 逻辑输入/输出  | CA-IS3820/21 A 侧逻辑输入，CA-IS3822 A 侧逻辑输出                         |
| VI2/VO2 | 3       | 逻辑输入/输出  | CA-IS3820/22 A 侧逻辑输入，CA-IS3821 A 侧逻辑输出                         |
| GNDA    | 4       | 地             | A 侧接地基准点                                                         |
| GNDB    | 5       | 地             | B 侧接地基准点                                                         |
| VI2/VO2 | 6       | 逻辑输入/输出  | CA-IS3821 B 侧逻辑输入，CA-IS3820/22 B 侧逻辑输出                         |
| VI1/VO1 | 7       | 逻辑输入/输出  | CA-IS3822 B 侧逻辑输入，CA-IS3820/21 B 侧逻辑输出                         |
| VDDB    | 8       | 电源           | B 侧电源电压                                                          |

---table end---

# 7. 产品规格
#  7.1. 绝对最大额定值 1
 参数和电气特性
---table begin---
Table tile:CA-IS382x绝对最大额定值表
| 参数      | 描述             | 最小值 | 最大值 | 单位   |
|----------|------------------|-------|-------|--------|
| VDDA, VDDB | 电源电压       | -0.5  | 7.0   | V      |
| Vin      | 输入电压 VIx，ENA，ENB | -0.5  | VDD+0.53 | V   |
| IO       | 输出电流         | -20   | 20    | mA     |
| TJ       | 结温             |       | 150   | °C     |
| TSTG     | 存储温度范围     | -65   | 150   | °C     |
备注**:
1. 等于或超出上述绝对最大额定值可能会导致产品永久性损坏。这只是额定最值，并不能以这些条件或者在任何其它超出本技术规范操作章节中所示规格的条件下，推断产品能否正常工作。长期在超出最大额定值条件下工作会影响产品的可靠性。
2. 除差分 I / O 总线电压以外的所有电压值，均相对于本地接地端子（GNDA 或 GNDB），并且是峰值电压值。
3. 最大电压不得超过 7 V。
---table end---


# 7.2. ESD 额定值
#电气特性
---table begin---
Table tile:CA-IS382x电气特性表
| 1    | 2                              | 数值  | 单位 |
|------|---------------------------------|-------|------|
| VESD静电放电  | 人体模型 (HBM), 根据 ANSI/ESDA/JEDEC JS-001,同侧引脚对同侧 GND。 | ±8000 | V    |
| VESD静电放电  | 组件充电模式(CDM), 根据 JEDEC specification JESD22-C101, 所有引脚。 | ±2000 | V    |
---table end---


#  7.3. 建议工作条件
---table begin---
Table tile:CA-IS382x建议工作条件表
| 参数             | 描述                              | 最小值 | 典型值 | 最大值 | 单位   |
|------------------|-----------------------------------|-------|-------|-------|--------|
| VDDA, VDDB       | 电源电压                           | 2.375 | 3.3   | 5.5   | V      |
| VDD（UVLO+）     | VDD 电源电压上升时的欠压阈值      | 1.95  | 2.24  | 2.375 | V      |
| VDD（UVLO-）     | VDD 电源电压下降时的欠压阈值      | 1.88  | 2.10  | 2.325 | V      |
| VHYS（UVLO）     | VDD 迟滞欠压阈值                   | 70    | 140   | 250   | mV     |
| IOH              | 高电平输出电流                     |       |       |       |        |
| - VDDO = 5V     |                                 | -4    |       |       | mA     |
| - VDDO = 3.3V   |                                 | -2    |       |       | mA     |
| - VDDO = 2.5V   |                                 | -1    |       |       | mA     |
| IOL              | 低电平输出电流                     |       |       |       |        |
| - VDDO = 5V     |                                 | 4     |       |       | mA     |
| - VDDO = 3.3V   |                                 | 2     |       |       | mA     |
| - VDDO = 2.5V   |                                 | 1     |       |       | mA     |
| VIH              | 输入阈值逻辑高电平                |       | 2.0   |       | V      |
| VIL              | 输入阈值逻辑低电平                |       | 0.8   |       | V      |
| DR               | 信号传输速率                      | 0     | 150   |       | Mbps   |
| TA               | 环境温度                          | -40   | 27    | 125   | °C     |
备注**:
1. VDDO = 输出侧 VDD
---table end---


# 7.4. 热量信息 
#热量表 CA-IS382x
---table begin---
Table tile:CA-IS382x热量信息表
| 封装型号         | 描述                   | RθJA (°C/W) |
|------------------|------------------------|-------------|
| SOIC8-WB(G)      | SOIC8 封装 (WB - 窄体) | 92.3        |
| SOIC16-WB(W)     | SOIC16 封装 (WB - 窄体) | 83.4        |
| SOIC16-WWB(WW)   | SOIC16 封装 (WWB - 超宽体) | 83.4        |
---table end---


# 7.5. 额定功率
---table begin---
Table tile:CA-IS382x额定功率表
| 参数     | 测试条件                                      | 最小值 | 典型值 | 最大值 | 单位   |
|----------|-----------------------------------------------|-------|-------|-------|--------|
| PD       | 最大功耗                                      |       | 120   |       | mW     |
| PDA      | A 侧的最大功耗                                |       | 20    |       | mW     |
| PDB      | B 侧的最大功耗                                |       | 100   |       | mW     |
---table end---


# 7.5.1. 额定功率CA-IS3821
---table begin---
Table tile:CA-IS382x额定功率表
| 参数     | 测试条件                                      | 最小值 | 典型值 | 最大值 | 单位   |
|----------|-----------------------------------------------|-------|-------|-------|--------|
| PD       | 最大功耗                                      |       | 120   |       | mW     |
| PDA      | A 侧的最大功耗                                |       | 60    |       | mW     |
| PDB      | B 侧的最大功耗                                |       | 60    |       | mW     |
---table end---


# 7.5.2. 额定功率CA-IS3822
---table begin---
Table tile:CA-IS382x额定功率表
| 参数     | 测试条件                                      | 最小值 | 典型值 | 最大值 | 单位   |
|----------|-----------------------------------------------|-------|-------|-------|--------|
| PD       | 最大功耗                                      |       | 120   |       | mW     |
| PDA      | A 侧的最大功耗                                |       | 60    |       | mW     |
| PDB      | B 侧的最大功耗                                |       | 60    |       | mW     |
---table end---


#  7.6. 隔离特性
---table begin---
Table tile:CA-IS382x隔离特性表
| 参数    | 测试条件                                       | 数值             | 单位      |
|---------|-----------------------------------------------|------------------|-----------|
| CLR     | 外部气隙（间隙）1 测量输入端至输出端，隔空最短距离 | 8 - 15          | mm        |
| CPG     | 外部爬电距离1 测量输入端至输出端，沿壳体最短距离 | 8 - 15          | mm        |
| DTI     | 隔离距离 最小内部间隙（内部距离)                | 27               | μm        |
| CTI     | 相对漏电指数 DIN EN 60112 (VDE 0303-11); IEC 60112 | >600            | V         |
|         | 材料组 依据 IEC 60664-1                        | I                |           |
|         | IEC 60664-1 过压类别                            |                  |           |
|         | 额定市电电压 ≤ 300 VRMS                        | I-IV             |           |
|         | 额定市电电压 ≤ 400 VRMS                        | I-IV             |           |
|         | 额定市电电压 ≤ 600 VRMS                        | I-III            |           |
|         | DIN V VDE V 0884-11:2017-012                   |                  |           |
| VIORM   | 最大重复峰值隔离电压 交流电压(双极)             | 2121             | VPK       |
| VIOWM   | 最大工作隔离电压 交流电压; 时间相关的介质击穿 (TDDB) 测试 | 1500             | VRMS      |
|         | 直流电压                                      | 2121             | VDC       |
| VIOTM   | 最大瞬态隔离电压                               |                  |           |
|         | VTEST = VIOTM, t = 60 s (认证)                  | 8000             | VPK       |
|         | VTEST = 1.2 × VIOTM, t= 1 s (100% 产品测试)     |                  |           |
| VIOSM   | 最大浪涌隔离电压 3 测试方法 依据 IEC 60065, 1.2/50 μs 波形 | 8000      | VPK       |
|         | VTEST = 1.6 × VIOSM (生产测试)                  |                  |           |
| qpd     | 表征电荷 4                                   |                  |           |
|         | 方法 a，输入/输出安全测试子类 2/3 后，Vini = VIOTM, tini = 60 s; Vpd(m) = 1.2 × VIORM, tm = 10 s | ≤5 | pC |
|         | 方法 a，环境测试子类 1 后，Vini = VIOTM, tini = 60 s; Vpd(m) = 1.6 × VIORM, tm = 10 s | ≤5 | pC |
|         | 方法 b1, 常规测试 (100% 生产测试) 和前期预处理(抽样测试) Vini = 1.2 × VIOTM, tini = 1 s; Vpd(m) = 1.875 × VIORM, tm = 1 s | ≤5 | pC |
| CIO     | 栅电容, 输入到输出                           | VIO = 0.4 × sin (2πft), f = 1 MHz | ~0.5 | pF |
| RIO     | 绝缘电阻 5                                  | VIO = 500 V, TA = 25°C | >1012 | Ω |
|         | VIO = 500 V, 100°C ≤ TA ≤ 125°C             |                  |           |
|         | VIO = 500 V at TS = 150°C                   | >109 |           |
| 污染度  | 2                                             | 2                |           |
| UL 1577 |                                               |                  |           |
| VISO    | 最大隔离电压                                |                  |           |
|         | VTEST = VISO , t = 60 s (认证)               | 5700             | VRMS      |
|         | VTEST = 1.2 × VISO , t = 1 s (100%生产测试)  |                  |           |
---table end---


# 7.7. 安全相关认证
---table begin---
Table tile:CA-IS382x安全相关认证表
认证及证书编号

| 认证来源 | 标准或规定                    | 证书编号            |
|---------|------------------------------|---------------------|
| VDE     | DIN V VDE V 0884-11:2017-01  | 申请中              |
| UL      | UL1577 器件程序认证          | E511334-20200117    |
| TUV     | EN 61010-1:2010+A1           | CN23RC4J 001        |
---table end---


# 7.8. 电气特性
# 7.8.1. VDDA = VDDB = 5 V ± 10%, TA = -40 to 125°C
---table begin---
Table tile:CA-IS382x电气特性表
| 参数       | 测试条件                                     | 最小值 | 典型值 | 最大值 | 单位  |
|------------|----------------------------------------------|-------|-------|-------|-------|
| VOH        | 输出电压逻辑高电平                           |       | -0.4  | 4.8   | V     |
| -          | IOH = -4mA; 图 8-1 VDDO1                    |       |       |       |       |
| VOL        | 输出电压逻辑低电平                           |       | 0.2   | 0.4   | V     |
| -          | IOL = 4mA; 图 8-1                            |       |       |       |       |
| VIT+(IN)  | 输入高电平                                  |       |       | 2     | V     |
| VIT-(IN)  | 输入低电平                                  |       |       | 0.8   | V     |
| VIT+(EN)  | EN 引脚输入高电平                            |       |       | 0.7*VDD | V   |
| VIT-(EN)  | EN 引脚输入低电平                            |       |       | 0.3*VDD | V   |
| IIH        | 输入高电平漏电流                            | VIH = VDDA/B at VIx |       | 20    | µA  |
| IIL        | 输入低电平漏电流                            | VIL = 0 V at VIx |       | -20   | µA  |
| ZO         | 输出阻抗 2                                  |       |       | 50    | Ω     |
| CMTI       | 共模瞬变抗扰度                              | VI = VDDI1 or 0 V, VCM = 1200 V; 图 8-3 | 100   | 150   | kV/µs |
| CI         | 输入电容 3                                  | VI = VDD/ 2 + 0.4×sin(2πft), f = 1 MHz, VDD = 5 V | 2     |       | pF    |
备注**:
1. VDDI = 输入侧 VDD, VDDO = 输出侧 VDD
2. 正常隔离器通道的输出阻抗约为 50Ω±40％。
3. 从引脚到地测量。
---table end---


#  7.8.2. VDDA = VDDB = 3点3 V ± 10%, TA = -40 to 125°C
#参数和测试条件
---table begin---
Table tile:CA-IS382x参数和测试条件表
| 参数       | 测试条件                                     | 最小值 | 典型值 | 最大值 | 单位  |
|------------|----------------------------------------------|-------|-------|-------|-------|
| VOH        | 输出电压逻辑高电平                           |       | -0.4  | 3.1   | V     |
| -          | IOH = -4mA; 图 8-1 VDDO1                    |       |       |       |       |
| VOL        | 输出电压逻辑低电平                           |       | 0.2   | 0.4   | V     |
| -          | IOL = 4mA; 图 8-1                            |       |       |       |       |
| VIT+(IN)  | 输入高电平                                  |       |       | 2     | V     |
| VIT-(IN)  | 输入低电平                                  |       |       | 0.8   | V     |
| VIT+(EN)  | EN 引脚输入高电平                            |       |       | 0.7*VDD | V   |
| VIT-(EN)  | EN 引脚输入低电平                            |       |       | 0.3*VDD | V   |
| IIH        | 输入高电平漏电流                            | VIH = VDDA/B at VIx |       | 20    | µA  |
| IIL        | 输入低电平漏电流                            | VIL = 0 V at VIx |       | -20   | µA  |
| ZO         | 输出阻抗 2                                  |       |       | 50    | Ω     |
| CMTI       | 共模瞬变抗扰度                              | VI = VDDI1 or 0 V, VCM = 1200 V; 图 8-3 | 100   | 150   | kV/µs |
| CI         | 输入电容 3                                  | VI = VDD/ 2 + 0.4×sin(2πft), f = 1 MHz, VDD = 3.3 V | 2     |       | pF    |
备注**:
1. VDDI = 输入侧 VDD, VDDO = 输出侧 VDD
2. 正常隔离器通道的输出阻抗约为 50Ω±40％。
3. 从引脚到地测量。
---table end---


# 7.8.3. VDDA = VDDB = 2点5 V ± 5%, TA = -40 to 125°C
#参数和测试条件
---table begin---
Table tile:CA-IS382x参数和测试条件表
| 参数       | 测试条件                                     | 最小值 | 典型值 | 最大值 | 单位  |
|------------|----------------------------------------------|-------|-------|-------|-------|
| VOH        | 输出电压逻辑高电平                           |       | -0.4  | 2.3   | V     |
| -          | IOH = -4mA; 图 8-1 VDDO1                    |       |       |       |       |
| VOL        | 输出电压逻辑低电平                           |       | 0.2   | 0.4   | V     |
| -          | IOL = 4mA; 图 8-1                            |       |       |       |       |
| VIT+(IN)  | 输入高电平                                  |       |       | 2     | V     |
| VIT-(IN)  | 输入低电平                                  |       |       | 0.8   | V     |
| VIT+(EN)  | EN 引脚输入高电平                            |       |       | 0.7*VDD | V   |
| VIT-(EN)  | EN 引脚输入低电平                            |       |       | 0.3*VDD | V   |
| IIH        | 输入高电平漏电流                            | VIH = VDDA/B at VIx |       | 20    | µA  |
| IIL        | 输入低电平漏电流                            | VIL = 0 V at VIx |       | -20   | µA  |
| ZO         | 输出阻抗 2                                  |       |       | 50    | Ω     |
| CMTI       | 共模瞬变抗扰度                              | VI = VDDI1 or 0 V, VCM = 1200 V; 图 8-3 | 100   | 150   | kV/µs |
| CI         | 输入电容 3                                  | VI = VDD/ 2 + 0.4×sin(2πft), f = 1 MHz, VDD = 2.5 V | 2     |       | pF    |
备注**:
1. VDDI = 输入侧 VDD, VDDO = 输出侧 VDD
2. 正常隔离器通道的输出阻抗约为 50Ω±40％。
3. 从引脚到地测量。
---table end---


# 7.9. 电源电流特性
# 7.9.1. VDDA = VDDB = 5 V ± 10%, TA = -40 to 125°C
电源电流参数和测试条件
---table begin---
Table tile:CA-IS382x电源电流参数和测试条件表
| 测试条件                            | 电源电流 (mA) |
|-----------------------------------|---------------|
| 直流信号 VIN = 0V (CA-IS3820L)     |               |
| - VIN = VDDI1 (CA-IS3820H)        | 0.9 - 1.3     |
| - VIN = VDDI (CA-IS3820L)         | 2.5 - 4.1     |
| - VIN = 0V(CA-IS3820H)            | 1.4 - 2.2     |
| 交流信号 (1Mbps)                   |               |
| - 所有通道输入 50%占空比，幅值为 5V 的方波；每个通道 CL = 15 pF | 1.7 - 2.7     |
| 交流信号 (10Mbps)                  |               |
| - 所有通道输入 50%占空比，幅值为 5V 的方波；每个通道 CL = 15 pF | 1.8 - 2.9     |
| 交流信号 (100Mbps)                 |               |
| - 所有通道输入 50%占空比，幅值为 5V 的方波；每个通道 CL = 15 pF | 2.5 - 3.9     |
| - 10Mbps (5MHz)                   | 8.8 - 11.8    |
| - 100Mbps (50MHz)                 | 22 - 30.0     |
---table end---


# 7.9.1.1.CA-IS3821
---table begin---
Table tile:CA-IS382x电源电流参数和测试条件表
| 测试条件                            | 电源电流 (mA) |
|-----------------------------------|---------------|
| 直流信号 VIN = 0V (CA-IS3821L)     |               |
| - VIN = VDDI (CA-IS3821H)         | 1.6 - 3.2     |
| - VIN = 0V(CA-IS3821H)            | 1.6 - 3.2     |
| 交流信号 (1Mbps)                   |               |
| - 所有通道输入 50%占空比，幅值为 5V 的方波；每个通道 CL = 15 pF | 2.1 - 3.2     |
| 交流信号 (10Mbps)                  |               |
| - 所有通道输入 50%占空比，幅值为 5V 的方波；每个通道 CL = 15 pF | 5.6 - 7.8     |
| 交流信号 (100Mbps)                 |               |
| - 所有通道输入 50%占空比，幅值为 5V 的方波；每个通道 CL = 15 pF | 12.9 - 22     |
---table end---


# 7.9.1.2.CA-IS3822
---table begin---
Table tile:CA-IS382x电源电流参数和测试条件表
| 测试条件                            | 电源电流 (mA) |
|-----------------------------------|---------------|
| 直流信号 VIN = 0V (CA-IS3822L)     |               |
| - VIN = VDDI (CA-IS3822H)         | 1.6 - 3.2     |
| - VIN = 0V(CA-IS3822H)            | 1.6 - 3.2     |
| 交流信号 (1Mbps)                   |               |
| - 所有通道输入 50%占空比，幅值为 5V 的方波；每个通道 CL = 15 pF | 2.1 - 3.2     |
| 交流信号 (10Mbps)                  |               |
| - 所有通道输入 50%占空比，幅值为 5V 的方波；每个通道 CL = 15 pF | 5.6 - 7.8     |
| 交流信号 (100Mbps)                 |               |
| - 所有通道输入 50%占空比，幅值为 5V 的方波；每个通道 CL = 15 pF | 12.9 - 22     |

备注**:
1. VDDI = 输入侧 VDD
---table end---


# 7.9.2. VDDA = VDDB = 3点3 V ± 10%, TA = -40 to 125°C 
电源电流参数和测试条件
---table begin---
Table tile:CA-IS382x电源电流参数和测试条件表
| 测试条件                            | 电源电流 (mA) |
|-----------------------------------|---------------|
| 直流信号 VIN = 0V (CA-IS3820L);     |               |
| - VIN = VDDI1 (CA-IS3820H)        | 0.8 - 1.3     |
| - VIN = VDDI (CA-IS3820L)         | 2.4 - 4.0     |
| - VIN = 0V(CA-IS3820H)            | 1.3 - 2.0     |
| 交流信号 (1Mbps)                   |               |
| - 所有通道输入 50%占空比，幅值为 3.3V 的方波；每个通道 CL = 15 pF | 1.6 - 2.7     |
| 交流信号 (10Mbps)                  |               |
| - 所有通道输入 50%占空比，幅值为 3.3V 的方波；每个通道 CL = 15 pF | 1.7 - 2.7     |
| 交流信号 (100Mbps)                 |               |
| - 所有通道输入 50%占空比，幅值为 3.3V 的方波；每个通道 CL = 15 pF | 2.2 - 3.5     |
| - 10Mbps (5MHz)                   | 6.2 - 8.4     |
| - 100Mbps (50MHz)                 | 14.4 - 19.7   |
---table end---


# 7.9.2.1.CA-IS3821
---table begin---
Table tile:CA-IS382x电源电流参数和测试条件表
| 测试条件                            | 电源电流 (mA) |
|-----------------------------------|---------------|
| 直流信号 VIN = 0V (CA-IS3821L)     |               |
| - VIN = VDDI (CA-IS3821H)         | 1.2 - 1.9     |
| - VIN = 0V(CA-IS3821H)            | 1.2 - 1.9     |
| 交流信号 (1Mbps)                   |               |
| - 所有通道输入 50%占空比，幅值为 3.3V 的方波；每个通道 CL = 15 pF | 1.9 - 2.9     |
| 交流信号 (10Mbps)                  |               |
| - 所有通道输入 50%占空比，幅值为 3.3V 的方波；每个通道 CL = 15 pF | 4.2 - 5.9     |
| 交流信号 (100Mbps)                 |               |
| - 所有通道输入 50%占空比，幅值为 3.3V 的方波；每个通道 CL = 15 pF | 8.8 - 12.1    |
---table end---

# 7.9.2.2.CA-IS3822
---table begin---
Table tile:CA-IS382x电源电流参数和测试条件表
| 测试条件                            | 电源电流 (mA) |
|-----------------------------------|---------------|
| 直流信号 VIN = 0V (CA-IS3822L)     |               |
| - VIN = VDDI (CA-IS3822H)         | 1.2 - 1.9     |
| - VIN = 0V(CA-IS3822H)            | 1.2 - 1.9     |
| 交流信号 (1Mbps)                   |               |
| - 所有通道输入 50%占空比，幅值为 3.3V 的方波；每个通道 CL = 15 pF | 1.9 - 2.9     |
| 交流信号 (10Mbps)                  |               |
| - 所有通道输入 50%占空比，幅值为 3.3V 的方波；每个通道 CL = 15 pF | 4.2 - 5.9     |
| 交流信号 (100Mbps)                 |               |
| - 所有通道输入 50%占空比，幅值为 3.3V 的方波；每个通道 CL = 15 pF | 8.8 - 12.1    |
备注**:
1. VDDI = 输入侧 VDD


# 7.9.3. VDDA = VDDB = 2.5 V ± 5%, TA = -40 to 125°C
电源电流参数和测试条件
---table begin---
Table tile:CA-IS382x电源电流参数和测试条件表
| 测试条件                            | 电源电流 (mA) |
|-----------------------------------|---------------|
| 直流信号 VIN = 0V (CA-IS3820L);     |               |
| - VIN = VDDI1 (CA-IS3820H)        | 0.8 - 1.2     |
| - VIN = VDDI (CA-IS3820L)         | 2.4 - 4.0     |
| - VIN = 0V(CA-IS3820H)            | 1.4 - 2.0     |
| 交流信号 (1Mbps)                   |               |
| - 所有通道输入 50%占空比，幅值为 2.5V 的方波；每个通道 CL = 15 pF | 1.6 - 2.6     |
| 交流信号 (10Mbps)                  |               |
| - 所有通道输入 50%占空比，幅值为 2.5V 的方波；每个通道 CL = 15 pF | 1.7 - 2.7     |
| 交流信号 (100Mbps)                 |               |
| - 所有通道输入 50%占空比，幅值为 2.5V 的方波；每个通道 CL = 15 pF | 2.1 - 3.4     |
| - 10Mbps (5MHz)                   | 5.0 - 6.8     |
| - 100Mbps (50MHz)                 | 10.8 - 14.7   |
---table end---


# 7.9.3.1.CA-IS3821
---table begin---
Table tile:CA-IS382x电源电流参数和测试条件表
| 测试条件                            | 电源电流 (mA) |
|-----------------------------------|---------------|
| 直流信号 VIN = 0V (CA-IS3821L)     |               |
| - VIN = VDDI (CA-IS3821H)         | 1.5 - 1.9     |
| - VIN = 0V(CA-IS3821H)            | 1.5 - 1.9     |
| 交流信号 (1Mbps)                   |               |
| - 所有通道输入 50%占空比，幅值为 2.5V 的方波；每个通道 CL = 15 pF | 1.9 - 2.8     |
| 交流信号 (10Mbps)                  |               |
| - 所有通道输入 50%占空比，幅值为 2.5V 的方波；每个通道 CL = 15 pF | 3.6 - 5.2     |
| 交流信号 (100Mbps)                 |               |
| - 所有通道输入 50%占空比，幅值为 2.5V 的方波；每个通道 CL = 15 pF | 6.9 - 9.5     |
---table end---


# 7.9.3.2.CA-IS3822
---table begin---
Table tile:CA-IS382x电源电流参数和测试条件表
| 测试条件                            | 电源电流 (mA) |
|-----------------------------------|---------------|
| 直流信号 VIN = 0V (CA-IS3822L)     |               |
| - VIN = VDDI (CA-IS3822H)         | 1.5 - 1.9     |
| - VIN = 0V(CA-IS3822H)            | 1.5 - 1.9     |
| 交流信号 (1Mbps)                   |               |
| - 所有通道输入 50%占空比，幅值为 2.5V 的方波；每个通道 CL = 15 pF | 1.9 - 2.8     |
| 交流信号 (10Mbps)                  |               |
| - 所有通道输入 50%占空比，幅值为 2.5V 的方波；每个通道 CL = 15 pF | 3.6 - 5.2     |
| 交流信号 (100Mbps)                 |               |
| - 所有通道输入 50%占空比，幅值为 2.5V 的方波；每个通道 CL = 15 pF | 6.9 - 9.5     |
备注**:
1. VDDI = 输入侧 VDD
---table end---


# 7.10. 时序特性
# 7.10.1. VDDA = VDDB = 5 V ± 10%, TA = -40 to 125°C
#参数和测试条件
---table begin---
Table tile:CA-IS382x时序特性表
| 参数       | 测试说明           | 最小值 | 典型值 | 最大值 | 单位  |
|------------|------------------|-------|-------|-------|-------|
| DR         | 数据速率            | 0     | 150   | Mbps  |       |
| PWmin      | 最小脉冲宽度         | 5.0   |       | ns    |       |
| tPLH, tPHL | 传播延迟            |       | 12.0  | 15.0  | ns    |
| PWD        | 脉冲宽度失真         |       | 0.2   | 4.5   | ns    |
| tsk(o)     | 通道到通道输出偏移时间 1 |       | 0.4   | 2.5   | ns    |
| tsk(pp)    | 片与片之间通道输出偏移时间 2 |     | 2.0   | 4.5   | ns    |
| tr         | 输出上升时间         |       | 2.5   | 4.0   | ns    |
| tf         | 输出下降时间         |       | 2.5   | 4.0   | ns    |
| tDO        | 默认输出延迟时间从输入电源损耗 | 8     |       | 12    | µs    |
| tSU        | 启动时间             | 15    |       | 40    | µs    |
备注**:
1. tsk(o) 为具有所有驱动输入连接在一起的单个设备的输出与驱动相同负载时沿相同方向切换的输出之间的偏差。
2. tsk(pp) 是在相同的电源电压、温度、输入信号和负载下，不同器件在同一方向切换的任意终端之间传播延迟时间的差值。
---table end---


# 7.10.2. VDDA = VDDB = 3点3 V ± 10%, TA = -40 to 125°C
参数和测试条件
---table begin---
Table tile:CA-IS382x参数和测试条件表
| 参数       | 测试说明           | 最小值 | 典型值 | 最大值 | 单位  |
|------------|------------------|-------|-------|-------|-------|
| DR         | 数据速率            | 0     | 150   | Mbps  |       |
| PWmin      | 最小脉冲宽度         | 5.0   |       | ns    |       |
| tPLH, tPHL | 传播延迟            |       | 12.0  | 17.0  | ns    |
| PWD        | 脉冲宽度失真         |       | 0.2   | 4.5   | ns    |
| tsk(o)     | 通道到通道输出偏移时间 1 |       | 0.4   | 2.5   | ns    |
| tsk(pp)    | 片与片之间通道输出偏移时间 2 |     | 2.0   | 4.5   | ns    |
| tr         | 输出上升时间         |       | 2.5   | 4.0   | ns    |
| tf         | 输出下降时间         |       | 2.5   | 4.0   | ns    |
| tDO        | 默认输出延迟时间从输入电源损耗 | 8     |       | 12    | µs    |
| tSU        | 启动时间             | 15    |       | 40    | µs    |
备注**:
1. tsk(o) 为具有所有驱动输入连接在一起的单个设备的输出与驱动相同负载时沿相同方向切换的输出之间的偏差。
2. tsk(pp) 是在相同的电源电压、温度、输入信号和负载下，不同器件在同一方向切换的任意终端之间传播延迟时间的差值。
---table end---


# 7.10.3. VDDA = VDDB = 2点5 V ± 5%, TA = -40 to 125°C
参数和测试条件
---table begin---
Table tile:CA-IS382x参数和测试条件表
| 参数       | 测试说明           | 最小值 | 典型值 | 最大值 | 单位  |
|------------|------------------|-------|-------|-------|-------|
| DR         | 数据速率            | 0     | 150   | Mbps  |       |
| PWmin      | 最小脉冲宽度         | 5.0   |       | ns    |       |
| tPLH, tPHL | 传播延迟            |       | 12.0  | 20.0  | ns    |
| PWD        | 脉冲宽度失真         |       | 0.2   | 5.0   | ns    |
| tsk(o)     | 通道到通道输出偏移时间 1 |       | 0.4   | 2.5   | ns    |
| tsk(pp)    | 片与片之间通道输出偏移时间 2 |     | 2.0   | 5.0   | ns    |
| tr         | 输出上升时间         |       | 2.5   | 4.0   | ns    |
| tf         | 输出下降时间         |       | 2.5   | 4.0   | ns    |
| tDO        | 默认输出延迟时间从输入电源损耗 | 8     |       | 12    | µs    |
| tSU        | 启动时间             | 15    |       | 40    | µs    |
备注**:
1. tsk(o) 为具有所有驱动输入连接在一起的单个设备的输出与驱动相同负载时沿相同方向切换的输出之间的偏差。
2. tsk(pp) 是在相同的电源电压、温度、输入信号和负载下，不同器件在同一方向切换的任意终端之间传播延迟时间的差值。
---table end---


# 8. 参数测量信息


# 9. 详细说明
# 9.1. 工作原理
CA-IS38xx 系列产品采用全差分隔离电容技术。由 SiO2 构成的高压隔离电容为不同的电压域之间提供可靠的绝缘屏
障，并提供可靠的高频信号传输路径；为了保证稳定的数据传输质量，引入开关键控(OOK)调制解调技术。发射机(TX)
将输入信号调制到载波频率上，即 TX 在一个输入状态下通过隔离电容传递高频信号，而在另一个输入状态下无信号通
过隔离电容，然后接收机根据检测到的带内数据重建输入信号。这个架构为隔离的不同电压域之间提供了可靠的数据
传输路径，在启动时不需要考虑初始化。全差分的隔离电容架构可以最大限度地提高信号共模瞬态抗干扰能力。
 CA-IS38xx 系列产品采用先进的电路技术可以有效的抑制载波信号和 IO 开关引入的 EMI。相比于电感耦合隔离架
构，电容耦合架构具有更高的电磁抗干扰能力。OOK 调制方案消除了脉冲调制方案中可能出现的脉冲丢失引起的误码
现象。 图 9-1 和图 9-2 分别为单通道功能框图和 OOK 开关键控调制方案波形示意图。
# 9.2. 功能框图
# 9.3. 真值表
表 9-1 为 CA-IS382x 器件真值表。
表 9-1 真值表 1
---table begin---
Table tile:CA-IS382x真值表
| VDDI | VDDO | 输入(Ax/Bx) | 输出使能 (ENx) | 输出 (Ax/Bx) 模式 |
|------|------|------------|----------------|------------------|
| PU   | PU   | H          | H or NC        | H                |
|      |      |            |                | or NC            |
|      |      |            |                |                  |
|      |      | 正常运行模式：  |                |                  |
|      |      | 通道的输出跟随通道输入状态 | L                | H or NC           |
|      |      |            |                |                  |
|      |      |            |                | Open             |
|      |      |            |                | or NC Default    |
|      |      |            |                |                  |
| X    | PU   | X          | L              | Z                |
|      |      | 高阻抗模式：  |                |                  |
|      |      | 如果 Enable 引脚连接为低电平 |                |                  |
|      |      | 输出将处于高阻态 |                |                  |
|      |      |            |                |                  |
| PD   | PU   | X          | H or NC        | Default          |
|      |      | 默认输出故障安全模式： |                |                  |
|      |      | 如果输入侧 VDD 未通电 |                |                  |
|      |      | 输出进入默认输出故障安全模式 |                |                  |
|      |      | (CA-IS382xL 为低电平，CA-IS382xH 为高电平) |                |                  |
|      |      |            |                |                  |
| X    | PD   | X          | X              | Undetermined     |
|      |      | 如果输出侧 VDD 未供电 |                |                  |
|      |      | 输出的状态不确定。   |                |                  |

备注:
1. VDDI = 输入侧 VDD; VDDO = 输出侧 VDD; PU = 上电 (VCC ≥ 2.375 V); PD = 断电 (VCC ≤ 2.25 V); X = 无关; H = 高电平; L = 低电平; Z = 高阻抗。
2. 强驱动的输入信号可以通过内部保护二极管微弱地驱动浮动的 VDD，从而导致输出不确定。
3. 当 CA-IS382x 在噪声环境中工作时，建议将使能引脚输入连接到外部逻辑的高电平或低电平。
4. NC 引脚是没有内部连接，可以悬空，连接到 VDD 或连接到 GND。
5. 当 2.25V < VDDI， VDDO < 2.375 V 时，输出处于不确定状态。
---table end---

# 9.3.1. 使能输入真值表
表 9-1 使能输入真值表
---table begin---
Table tile:CA-IS382x使能输入真值表
| 型号       | ENA1,2 | ENB1,2 | 输出   | 状态                                                         |
|------------|-------|-------|--------|--------------------------------------------------------------|
| CA-IS3820  | —     | H     | VO1, VO2 | 通道开启，输出状态和输入状态相同。                              |
|            | —     | L     | VO1, VO2 | 通道关闭 ，输出为高阻态。                                     |
| CA-IS3821  | H     | X     | VO1     | 通道开启，输出状态和输入状态相同。                              |
|            | L     | X     | VO1     | 通道关闭，输出为高阻态。                                        |
|            | X     | H     | VO1     | 通道开启 ，输出状态和输入状态相同。                             |
|            | X     | L     | VO1     | 通道关闭，输出为高阻态。                                        |
| CA-IS3822  | H     | X     | VO1     | 通道开启。                                                     |
|            | L     | X     | VO1     | 关闭，输出为高阻态。                                           |
|            | X     | H     | VO2     | 通道开启，输出状态和输入状态相同。                              |
|            | X     | L     | VO2     | 通道关闭，输出为高阻态。                                        |


备注:**
1. 使能输入 ENA 和 ENB 可用于多路复用，时钟同步或其他输出控制。表 9-2 中列出了每种隔离器产品的 ENA，ENB 逻辑运算。这些输入在内部上拉至本地 VDD，允许它们连接到外部逻辑电平（高或低）或悬空。为了最大限度地降低噪声耦合，如果它们悬空，请不要将电路走线连接到 ENA 或 ENB。如果未使用 ENA，ENB，建议将它们连接到外部逻辑电平，特别是如果 CA-IS382x 在嘈杂的环境中运行。
2. X = 无关; H = 高电平; L = 低电平。
---table end---


# 10. 应用电路
相比于光耦器件，CA-IS38xx 系列数字隔离器不需要外部元件来提供偏置或限制电流能力，只需要两个外部 VDD 旁
路电容（0.1μF 至 1μF）即可工作。 CA-IS38xx 产品输入兼容 TTL 电平，仅吸收微安级的输入漏电流，无需外部缓冲电
路即可驱动。 输出电阻为 50Ω（轨到轨输出），可提供正向和反向通道配置。图 10-1 显示了 CA-IS3821 的典型应用电
路。图 10-2 显示了 CA-IS38xx 系列产品的典型应用电路。 



# 11. 封装信息
# 11.1. SOIC8 宽体外形尺寸
下图说明了 CA-IS382x 系列数字隔离器采用 SOIC8 宽体封装大小尺寸图和建议焊盘尺寸图。 尺寸以毫米为单位。
# 11.2. SOIC16 宽体外形尺寸
下图说明了 CA-IS382x 系列数字隔离器采用 SOIC-16WB 宽体封装大小尺寸图和建议焊盘尺寸图。 尺寸以毫米为单
位。
# 11.31. SOIC16 超宽体外形尺寸
下图说明了 CA-IS382x 系列数字隔离器 SOIC16 超宽体封装大小尺寸图和建议焊盘尺寸图。 尺寸以毫米为单位。


# 12. 焊接信息


# 13. 编带信息


# 14. 重要声明
上述资料仅供参考使用，用于协助 Chipanalog 客户进行设计与研发。Chipanalog 有权在不事先通知的情况下，保
留因技术革新而改变上述资料的权利。
Chipanalog 产品全部经过出厂测试。 针对具体的实际应用，客户需负责自行评估，并确定是否适用。Chipanalog
对客户使用所述资源的授权仅限于开发所涉及 Chipanalog 产品的相关应用。 除此之外不得复制或展示所述资源， 如
因使用所述资源而产生任何索赔、 赔偿、 成本、 损失及债务等， Chipanalog 对此概不负责。

 