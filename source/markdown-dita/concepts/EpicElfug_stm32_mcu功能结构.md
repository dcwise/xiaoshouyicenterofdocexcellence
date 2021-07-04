# STM32 MCU功能结构 {#A4353A5B-3D0441F-2158155511CAA7B-D32E56 .concept}

MCU作为板载控制器，通过以太网口与用户主机相连。用户可对MCU进行编程，以管理板载的电源、时钟和风扇。另外MCU通过Reset SPI信号与FPGA-Elf相连。MCU资源清单如下：

-   MCU芯片

型号为STM32F429NIH6；

-   LED显示屏

显示子卡固件版本和IP等信息；

-   SPI接口

有2路SPI接口，一路用于下载FPGA-Elf比特文件，另一路用于MCU和FPGA-Elf互联通讯；

-   百兆以太网接口

用于与用户主机的通讯；

-   FPGA-Elf复位信号。

**Parent topic:**[功能结构](../concepts/EpicElfug_功能结构.md)

