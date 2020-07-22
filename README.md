# msi-z390-tomahawk

[OpenCore Desktop 教程](https://dortania.github.io/OpenCore-Install-Guide/)

OpenCore 0.5.9

macOS Catalina 10.15.5

## 配置

| 硬件 | 型号 | 备注 |
| ---- | ---- | ---- |
| CPU | Intel i5-9600k | 带核显可以开启 Sidecar |
| 主板 | MSI Z390-TOMAHAWK| |
| 显卡 | SAPPHIRE RX570 4G 白金 | 免驱 |
| 网卡 | BCM94352HMB | 旧设备，非免驱，需转接卡 |
| 硬盘 | WD SN750 | |

其他硬件，可以根据个人偏好选择

| 硬件 | 型号 | 备注 |
| ---- | ---- | ---- |
| 内存 | 十铨 火神 DDR4 3200 16GB x 2 | |
| 电源 | 振华 G550 |  |
| 机箱 | 追风者 p300 air | 更推荐 p400 air |
| 散热 | 雅浚 D3 | RGB YES! |
| 显示器 | 创维 28U1 | mac尽量上4k显示器 |

## EFI

config.plist，请自行修改三码和 mac address

机型我选择的是 iMac19,1 ，本机也是按照 iMac2019 的配置挑选的

Root-PlatformInfo-Generic-MLB/SystemSerialNumber/SystemUUID/ROM