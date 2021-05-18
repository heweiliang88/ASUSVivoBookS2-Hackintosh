# ASUSVivoBook S2 -hackintosh

​		本项目是一个采用了Clover引导的华硕灵耀s2笔记本的黑苹果和window10的双系统配置文件，该项目基本完成了苹果系统的98%的体验，可以正常完成基本功能。

### 电脑配置

- **主板**华硕X530UN
- **处理器** Intel Core i5-8250U @ 1.6GHz（KabyLake-R）
- 形象的：
	- Intel UHD620（1536MB动态内存（与系统共享））
	- NVIDIA GeForce MX150 2GB
- 网络：
	- Wifi：Intel 8265/8275 M2 NGFF（802.11 AC（2x2））
	- 以太网：否
	- 蓝牙：V4.1（正常运行）
- **音频：** Realtek ALC256（正常工作）
- **触摸板：** ELAN 1300（I2C）（在轮询模式下工作）
- 贮存：
	- SSD三星M.2 SATA 256GB
	- 东芝硬盘1TB
- 键盘：Chiclet键盘
- 读卡器：microSD读卡器
- 网络摄像头：VGA网络摄像头
- 电池：3节42小时电池

### 正常驱动

- [x] 显卡驱动：核显

	- [x] 图形UHD 620
	- [ ]  图形NVIDIA GeForce MX150（现在不支持）

- [x] 声卡驱动

- [x] 无线网络驱动：（替换为USB Wifi或等待Intel Wifi固件）

- [x] 以太网

- [x]  蓝牙（完全支持）

- [x]  外置USB耳机

- [x] USB 2.0

- [x]  USB 3.0

- [x]  调整亮度

- [x]  Fn功能

- [x]  LED灯键盘

- [x] 睡眠功率

- [ ]  电池

- [x]  触控板（仅在VoodooI2C的轮询模式下）

- [x]  全4核

- [x]  温度

- [x]  禁用带有SSDT修补程序的独立图形GPU

- [ ]  硬件加速（尚未测试）

- [ ]  个人热点（尚未测试）

- [x]  电源管理和状态

	

