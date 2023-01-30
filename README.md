# JGINYUE-H610I-GAMING-12100F-RX550-Hackintosh
OpenCore EFI for JGINYUE-H610I-GAMING-12100F-RX550-Hackintosh

点击链接加入 [精粤 B660I Snow Dream 黑苹果交流群](https://jq.qq.com/?_wv=1027&k=NBj9mNYo)

### Computer Spec:

| Component        | Specifications                         |
| ---------------- | -------------------------------------- |
| CPU              | Intel® Core™ i3-12100F                 |
| RAM              | Asgard 16GB DDR4 3200MHz               |
| Disk             | Western Digital PC SN730 512G NVMe SSD |
| GPU              | AMD Radeon™ RX 550                     |
| LAN              | Realtek RTL8111H                       |
| WiFi & Bluetooth | Intel® Wi-Fi 6 AX200                   |
| Audio            | Realtek ALC897                         |
| Monitor          | TUOSHUO 28" 4K@144Hz                   |
| SMBIOS           | MacPro7,1                              |
| BootLoader       | OpenCore 0.8.8                         |

### What Works:

- [x] Intel® Core™ i3-12100F Turbo Boost
- [x] AMD Radeon™ GPUs
- [x] ALC897 Audio Output/Input
- [x] Realtek RTL8111H
- [x] Intel Wi-Fi & Bluetooth
- [x] All USB Ports
- [x] Sleep
- [x] NVRAM

### BIOS Settings:

* Disable:  
CSM  
CFG Lock  
Secure Boot  
Wake on Lan

### Note

必须刷入下面指定版本的12代BIOS文件,搭配12代CPU,在BIOS中必须关闭网络唤醒(Wake on Lan)，才能正常睡眠。需要按下电源键唤醒，USB键盘鼠标唤醒无效。
[BIOS下载](http://down.jginyue.com/uploads/JYH61A0Bzidong.rar)

## Credits

- [Apple](https://apple.com) for macOS.
- [Acidanthera](https://github.com/acidanthera) for OpenCore and all the lovely hackintosh work.
- [Dortania](https://github.com/dortania) for great and detailed guides.
