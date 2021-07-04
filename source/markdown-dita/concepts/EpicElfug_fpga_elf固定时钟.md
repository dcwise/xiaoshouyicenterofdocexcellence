# FPGA-Elf固定时钟 {#A7133854-5161F25-7C1655C15B06034-855227 .concept}

FPGA-Elf固定时钟有以下四个部分：

-   FPGA-Elf固定时钟输入由一个125MHz晶振产生，电平标准为LVCMOS18；
-   MCU会输出一个SPI的时钟给FPGA-Elf；
-   由外部SMB座接受外部时钟；
-   125Mhz EMCCLK提供给FPGA-Elf加载使用。

FPGA-Elf固定时钟Pin脚分配如下：

|**FPGA NET Name**|**FPGA Pin**|
|SYS\_CLK\_125MHZ|AG12|
|SPI\_MCU\_FPGA\_3V3\_SCK|L22|
|USER\_SMB\_CLK|AG11|
|FPGA\_EMCCLK\_125MHZ|K20|

**Parent topic:**[时钟](../concepts/EpicElfug_时钟.md)

