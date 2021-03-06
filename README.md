# 联想 拯救者 14-isk&15-isk Skylake版安装macOS Catalina 10.15& macOS Mojave 10.14使用说明
让你的拯救者 14-isk&15-isk笔记本吃上黑苹果

[English](README-EN.md) | [中文](README.md)

* | Computer:Lenovo Rescuer 14-isk / Rescuer 15-isk Laptop
* | CPU :Intel Core i5- 6300HQ@ 2.3G/Intel Core i7-6700HQ @ 2.60G (Skylake )
* | Chipset : Lenovo SuperX 4B
* | Graphics :HD530 (using Intel GPU only) + GTX960M 
* | Audio:ACL235 @ Intel Lynx Point High Definition Audio
* | Ethernet: RTL8168/8111/8112 Gigabit Ethernet Controller
* | WiFi:Broadcom BCM93452z 802.11AC (原装无解，更换) 
* | Bluetooth:BCM20702 (4.0) (原装无解，更换)          
* | BIOS Version:最新版
 
  ![截图](Screen0.JPG)   
   ![截图](Screen.JPG)

## 支持列表

* macOS Catalina 10.15& macOS Mojave 10.14
* ACPI补丁修复使用hotpatch方式，相关文件位于 `/CLOVER/ACPI/patched` 。
* 远景论坛ID：39军小兵张 [Link](http://i.pcbeta.com/space-uid-4472739.html)
* 长期维护更新QQ群：754447000 群已改为打赏群了，打赏入群5-10元吧。如果需要远程技术指导安装，30以上你看着给吧，不过我建议大家自己看我详细的新手安装文档，自己实操就更好了。


## 关于打赏

如果您认可我的工作，请通过打赏支持我后续的更新(自觉打赏的人真少啊，免费的东西长久不了,现已改为需要密码解压，需微信或支付宝打赏入群。打赏记得留言备注你的qq号，然后申请入群时，填写你的留言为验证答案就是，我确认后会通过你的验证的。PS:之所以设置打赏，并不是为了赚大钱，当然大家打赏的多是有一些零花钱。主要是维护更新不易，每次系统一更新，有问题的话，就要工作时间之外花时间去调试，解决问题。普通群最多500人，无门槛的入群，不够用，有些机友对无门槛进入还不珍惜，进退群很随意，不看相关说明，上来就问问题的又多。不多说了，理解不理解的，就这样吧。

|                                 微信                                           |                         支付宝                                       |
| ---------------------------------------------------------- | ---------------------------------------------------- |
| ![微信打赏](微信打赏.png)                                         | ![支付宝打赏](支付宝打赏.png)                           |

|                   拯救者QQ群                                            |                拯救者QQ群                                       |
| ----------------------------------------------------------| ---------------------------------------------------- |
|  ![754447000](拯救者群.png)                                    |                           |

## 发布
前期会有免费版提供，后期转维护更新后，需要打赏入群获取解压密码。
最后发布的版本前往 [release page](https://github.com/Z39/Lenovo-Rescuer-14isk-15isk-OS-X-Clover-Hotpatch/releases) 下载即可。
如果Github网络下载不太好，新增[蓝奏云](https://www.lanzous.com/b616223)  密码：8shm

## 黑苹果相关情况
- [x] 显卡 核显HD530驱动
- [x]  USB 3.0 USB端口定制 
- [x]  亮度调节 FN+上下箭头调节
- [x]  声卡 AppleALC驱动 (修复耳机无人声问题)
- [x]  CPU变频  
- [x]  电源电池睡眠唤醒，这个机子电池显示可能有些时候不太稳定，目前还可以。
- [x]  键盘 输入可用，开启内置小键盘
- [x]  触控板 自定义手势，这个触控板好像跟电池问题连一起不稳定。
- [x] 有线网卡
- [x]  无线网卡 需要更换
- [x]  蓝牙 需要更换
- [x]  摄像头
- [x]  App Store/iCloud/iMessage/Facetime
- [x]  SIP 关闭SIP
- [x]  TRIM 固态默认开启
- [x]  无痛更新升级 支持在线升级
- [x]  读卡器 未知，没这个需求搞
- [x] 外接显示器 HDMI视频OK，更新支持HDMI声音输出
- [x]  独显 屏蔽

### 存在问题
* 最主要的这个机子的电池显示诡异的很，电池信息不在DSDT上，在SSDT上。各系统版本显示可能不太稳定，有的机子很稳定，有的机子又不稳定。
* 据说触摸板有时候也不稳定
* 其他问题待完善，本人无实机，无法实机调试，一些东西需要同机型机友帮忙测试。
## kexts等更新链接

- Clover EFI bootloader [Link](https://github.com/Dids/clover-builder/releases)

- FakeSMC [Link](https://bitbucket.org/RehabMan/os-x-fakesmc-kozlek/downloads/)

- ACPIBatteryManager [Link](https://bitbucket.org/RehabMan/os-x-acpi-battery-driver/)

- BrcmPatchRAM [Link](https://bitbucket.org/RehabMan/os-x-brcmpatchram/downloads/)

- Lilu [Link](https://github.com/acidanthera/Lilu)

- AirportBrcmFixup [Link](https://github.com/acidanthera/AirportBrcmFixup)

- WhateverGreen [Link](https://github.com/acidanthera/WhateverGreen)

- AppleALC [Link](https://github.com/acidanthera/AppleALC)

## 鸣谢
shiy05，limurphy
