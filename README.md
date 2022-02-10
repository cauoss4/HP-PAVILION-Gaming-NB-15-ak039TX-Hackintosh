# HP PAVILION Gaming NB 15-ak039TX Hackintosh
 macOS  Monterey for 暗影精灵I (HP PAVILION Gaming NB 15-ak039TX)


<!-- PROJECT SHIELDS -->

<!-- PROJECT LOGO -->
<br />

<p align="center">
  <a href="https://github.com/cauoss4/HP-PAVILION-Gaming-NB-15-ak039TX-Hackintosh/">

  </a>

  <h3 align="center">HP PAVILION Gaming NB 15-ak039TX Hackintosh</h3>
  <p align="center">
    macOS  Monterey 12.2 for 暗影精灵I (HP PAVILION Gaming NB 15-ak039TX)

  </p>

</p>


 本篇README.md将只介绍此EFI的特性 无安装教学
 




###### 说明
本EFI配置文件基于OpenCore0.7.7，稳定引导 MacOS 12.2 Monterey
（本人在此EFI引导下先安装 MacOS 后使用系统官方更新至 MacOS 12.2 ，理论上支持直接安装 MacOS 12.2 ）
以后若继续使用 Hackintosh 的话会继续进行后续的更新

此EFI只在 暗影精灵I (HP PAVILION Gaming NB 15-ak039TX) 原装配置下完美支持，可能不适用于更改过硬件的 暗影精灵I (HP PAVILION Gaming NB 15-ak039TX)

配置如下所示


###### 硬件配置

Computer model	           HP 15-ak039TX (950M/GTX)

Processor	                Intel Core i5-6300HQ

Memory	                   8GB Hynix DDR3L 1600MHz

Hard Disk	                SSD 128GB/HDD 1TB

Integrated Graphics	      Intel HD Graphics 530

Monitor                  	LG LGD04B3 FHD 1920x1080 (15.7inch)

Sound Card               	Realtek ALC290 (layout-id:28)

Wireless Card            	Intel Wireless 3165

SD Card Reader	           Realtek RTS522A


###### 支持的功能

3个 USB 2.0 都可使用
触碰版    
WiFi
蓝牙
有线网口
隔空播放



###### 不支持的功能

Airdrop 隔空投送
（在MacOS Monterey系统下 可以搜索到iphone等设备，但不可传输文件。不可被其他苹果设备搜索到。）
（原因尚不明确，可能是因为 Monterey 修复了蓝牙方面的设置，使得驱动不支持）
（解决办法：更换BCM94352Z无线网卡 或 使用 MacOS 12 以下的版本# 需要更改 无线网卡和蓝牙的 kexts # ）


HDMI 扩展 
（暂时不支持 HDMI 连接显示器，后续会解决此问题）


###### 注意事项

此项EFI仅用做个人学习及开源分享，禁止一切商业行为

如需安装及配置相关的指导，请查看[OpenCore](https://dortania.github.io/OpenCore-Install-Guide)官方手册

后续会制作 引导界面UI 并修复已知问题 ，欢迎关注与讨论














