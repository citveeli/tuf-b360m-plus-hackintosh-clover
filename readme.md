# 华硕ASUS TUF B360M PLUS GMAING S
继承于[@qzz0518](https://github.com/qzz0518/hackintosh_9400f_b360_vega56)，但配件略有不同，所有独立一个仓库，便于自己维护。

## 具体配置如下：
| 硬件 | 型号 | 
| - | :-: |
| 主板 | 华硕ASUS TUF B360M PLUS GAMING S |
| CPU | INTEL i3 9100F |
| 显卡 | 铭影 RX560 4G |
| 内存 | 威刚+金士顿 DDR4 2400 8G*2 |
| 固态 | 台电 Teclast 240NP800 |
| 机箱 | 先马 商英 |

## 体验
nodejs web全栈开发。
本来有mini 18款i3钙版，自己加到32G内存。
但是每天背来背去有点嫌累，再买一台又过于奢侈，所以动了黑苹果的念头。
利用家里台式机，换了几个配件，搞出了黑苹果。
因为大部分是脚本开发，对性能要求不高，所以配置比较钙。
但是体验上完全不输mini，某些方面还有超越。
感谢[@qzz0518](https://github.com/qzz0518/hackintosh_9400f_b360_vega56)的EFI，省了不少事。
有时间再自己研究配置~~

## 完善程度：
系统版本：macOS Catalina 10.15.3 
SMBIOS：Mac Pro 7.1

* 机箱前置 USB 3.0 接口所有设备正常
* 重启休眠正常
* 主板后置 USB 3.0 接口所有设备正常
* 声卡正常
* 显卡HDMI+DVI双显示器
* 更换三码后，AppleId正常使用

## 问题
1. 后置TYPE-c
> qzz0518
> 后置 USB-C 口，只支持 USB 3.1 Gen 1，不支持 USB 2.0 的 USB-C 设备

我手里只有三星X5固态移动硬盘，一切正常。
typc-c的U盘也正常，其他未知

2. 开机内存错误提示
目前选Mac Pro 7.1的通病，无视即可。

## 日志
* 20/02/22 初始配置