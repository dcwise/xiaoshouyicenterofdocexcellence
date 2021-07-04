# FPGA-Elf系统接口 {#A1355B38-454161F-214A8151C92BD76-2D0386 .concept}

使用Xilinx Kintex UltraScale FPGA芯片，型号为XCKU040-1FFVA1156C。FPGA-Elf系统接口说明如下：

|**接口**|**说明**|
|PT3|2路PT3接口

 接插件型号为SEAM-20-02.0-S-08-2-A-K-TR

 单个接口提供52组IO及2路差分时钟信号

|
|DDR4|标配2根型号为Micron MTA16ATF2G64HZ的高速DDR4 SODIMM内存条

 单根容量为16GB（共32GB）

|
|PCIe Gen3 8-lane|一路标准的PCIe Gen3 8-lane接口，通信速率最高64Gbps|
|千兆以太网|外接TI公司PHY芯片，型号为DP83867ISRGZ，采用RJ45接口|
|Mini-SAS HD|2路Mini-SAS接口，采用HD接插件

 总共提供8条通道，每个通道最高速率为10.3125Gb/s

|
|QSFP+光模块|4路高速收发器（Transceiver），每路收发器速率可达12.5Gb/s|
|UART|1路UART接口，与MCU共用FT4232芯片，转换为USB接口与主机连接|
|JTAG与GPIO|1个10 pin标准ARM JTAG接口；5个双向GPIO

 电平可调（1.5V，1.8V，2.5V，3.3V）

|
|拨盘开关|使用4 pin的拨码开关插座，其中3根pin连到FPGA-Elf

 电平可调（1.5V，1.8V，2.5V，3.3V

|
|QSPI Flash|提供128Mb QSPI-Flash，型号为MT25QL128

 可用于固化FPGA程序

|
|LED与复位|6个LED灯，置于板卡边沿，方便用户观察

 1个复位键

|

**Parent topic:**[FPGA-Elf功能结构](../concepts/EpicElfug_fpga_elf功能结构.md)

