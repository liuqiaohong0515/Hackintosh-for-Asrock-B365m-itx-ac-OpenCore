# Hackintosh for Asrock B365 itx/ac OpenCore
 This is mainly here for my benefit more than anyone elses, but you're welcome to use or modify these files in any way if you believe they can be of assistance to you.

该配置文件根据我自己的电脑配置定制，不一定适用于其他型号的硬件配置。


 # Version 版本
Type|Version
--|:--|
OpenCore|0.7.9
MacOS|12.3

系统|版本
--|:--|
OpenCore|0.7.9
MacOS|12.3


# Hardware 硬件
Type|Item
--|:--|
CPU|Intel Core i7-8700
Motherboard|ASRock B365M-ITX/ac
Video Card|null
Wifi card|BCM94352Z

硬件|型号
--|:--|
CPU|Intel Core i7-8700
主板|ASRock B365M-ITX/ac
显卡|无
无线网卡|BCM94352Z


# Functionality 运行状况
## Works 正常工作的
* Ethernet 有线网络
* Onboard Audio (including digital audio) 板载音频输出
* Sleep/Wake 睡眠唤醒
* All USB ports at 3.x speed USB接口并正常运行在3.0速率
* iMessage
* App Store
* Facetime
* APFS
* Handoff
* Bluetooth & Wi-Fi  蓝牙与WiFi，注意更换无线网卡
* Airdrop  隔空投送
* AirPlay
* Continuity
* Power Nap  电源小憩
* NVRAM
* Igpu headless mode (must be headless mode if you want Airplay works)
* Wired Sidecar

## Does't work 无法正常工作的
* Onboard Wifi: Won't work, I removed it and replaced with Broadcom BCM94352Z Card
* Wireless Sidecar