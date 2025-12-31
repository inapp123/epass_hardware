# 明日方舟电子通行证（DevKit 开发版）

一款面向折腾与二次开发的迷你 Linux 手持开发板，类似手机游戏《明日方舟》中的通行认证的电子挂牌。它基于F1C200s，拥有arm926ejs cpu，64MB内存，竖屏高分辨率 LCD、H.264 硬解能力，并保留常用外设接口。便于快速做 UI、媒体展示与各种硬件实验。项目硬件/软件资料完全开源，欢迎社区共同完善。

<img width="535" height="623" alt="image-20251119004524288" src="https://github.com/inapp123/epass_hardware/blob/master/Img/image-20251119004524288.png" />

## 最新版本
Ver.0.4

## 参数（规格）
### 主控 / 性能
主控 SoC： F1C200S（ARM926EJ‑S）

主频： 默认 408 MHz，支持 超频最高约 720 MHz

硬件能力： H.264 硬件解码

内存： 64 MB RAM

### 存储
NAND Flash： W25N01，128 MB

SDIO： TF（microSD）/ Wi‑Fi（SDIO）

### 显示
正面屏幕： 3.0 英寸，360 × 640（竖屏）

屏幕驱动： ST7701S

### 供电
电池： 1500 mAh 锂电（Li‑ion）

充电： TP4056
### 输入
按键： 4 个（LRADC 采样按键）

### 系统 / 软件
构建系统： Buildroot

内核： Linux 主线 5.4.77

### 拓展接口
* I²C： ×1
* UART： ×2
* SPI： ×1
* GPIO： ×3
* ADC： ×1
## 版本信息&注释

[[版本F&Q♿](https://github.com/rhodesepass/hardware/blob/master/Manual/Version/V0.3%20FAQ.md)]

## 对比上一个版本修改了什么？
[ / ] SOC F1C100S → F1C200S

[ + ] 增加屏幕支持，可在2种屏幕间自由选择

[ + ] 增加SD卡槽
## 开始复刻！GO!
[[前往文档♿](https://github.com/inapp123/epass_hardware/tree/master/Manual)]

[[前往软件部分♿](https://github.com/inapp123/epass_drm_app)]


## 加入交流群！
### 我们的QQ群
https://qm.qq.com/q/anjgWYaYdG 

或使用群号

```
(1群)1033668603
(2群)1072955003
```
