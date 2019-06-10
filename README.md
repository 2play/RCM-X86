
## The chip V1.1 is the same use as the old chip . 
(No need to soder out the R1)  
If you want to use like the trinket M0 (without the usb switc logic IC)  
just soder the X pad and Y pad.  
* * *
  ![res](https://github.com/euclala/RCM-X86/blob/master/V1.1.jpg.jpg)
* * *

## You can also download the UF2 file form Mattytrog 's Github  
https://gbatemp.net/threads/modchip-software-simple-uf2-with-switchboot-save-fuses-without-autorcm.526607/  
https://github.com/mattytrog?tab=repositories  

* * *  

USB dongle move to here ---[USB_Dongle](https://github.com/euclala/RCM_typeC_ex)
USB 注入器请移步这里 --- [USB_Dongle](https://github.com/euclala/RCM_typeC_ex)
* * *
## warning!warning!warning! 注意  注意 注意
[ex_SD_reload] is useless in 6.2 system, please use the [Mattytrog_SD_reload] ,
SD重载功能不能用于6.2系统,  6.2系统请刷[Mattytrog_SD_reload]
* * *

# RCM-X86 chip is a trinket M0 mod chip

install video :https://www.youtube.com/watch?v=KP71R3F2fF4&t=851s  
how to buy :https://www.tindie.com/products/jcrorxp/samd21-trinket-m0-mod-for-switch-dongle-rcm-x86/

* * *
## UF2 file introduction (UF2文件说明)
 hekate_ctcaer-> hekate-ctcaer(大气层)  
 TXOS -> TEAM xecuter os 1.0 (OS系统)  
 Mattytrog_SD_reload-> Mattytrog SD reload (6.2可用的重载功能,work well in 6.2)
 reiNX -> ReiNX  
 fusee_primary -> New ReiNX
 ex_SD_reload -> ex  SD reload  (旧版SD重载 ,useless in 6.2 system )
 disable_code -> disable the chip (禁用芯片,you can payload by the switch type-c)
* * *

## 4line install  (need to AutoRCM)四线安装,打开auto RCM
   RCM-X86 chip VCC -----> switch 3.3V  
   RCM-X86 chip GND -----> switch GND  
   RCM-X86 chip USB D-   -----> switch D-  
   RCM-X86 chip USB D+   -----> switch D+  

## 5line install  (NOT need  AutoRCM) 5线安装,启动时按住音量+
   (need to press the VOL+ and Power button to payload the switch)
   RCM-X86 chip VCC -----> switch 3.3V  
   RCM-X86 chip GND -----> switch GND  
   RCM-X86 chip USB D-   -----> switch D-  
   RCM-X86 chip USB D+   -----> switch D+ 
   RCM-X86 chip D0  -----> switch JOY-con Pin10  

* * *
WIN 7 need to install the WIN7driver驱动程序x.exe
## How to flash UF2 file (after install it into the switch)
   * solder a magnetic switch  between the GND and RES  
   * turn off the switch
   * pull in the type-C, connect the switch with the PC
   * Ues the magnet near the magnetic switch
          (twice at one second, to short the GND &RES)
   * normally it will be a new disk in you PC file explorer
   * if the PC say unknow usb driver ,just pull down the type-C and pull in it,or try again
   * copy the *.uf2 file into the new disk, then the disk will disappear.
   * done.
## 如何升级芯片的固件(装上机器后升级)
   * WIN7 需要安装驱动程序,WIN10不需要
   * 必须要在芯片GND和RES中间焊接干簧管
   * 关闭 switch
   * 通过 type-C数据线连接到switch,
   * 1秒内用磁铁触碰干簧管两次(实现短路)
   * 通常情况下,电脑就会显示出一个U盘,
   * 把 *.uf2 文件复制进去 这个U盘,U盘会自动消失,升级成功.
* * *

## If you want to bulid you project
This is the sch ,(All the GPIO is the same as the trinket M0)
The USB Logic IC EN pin is pull down with a 10K res.
(trinket M0 GPIO D3 is link to the USB IC EN pin)
   
  ![res](https://github.com/euclala/RCM-X86/blob/master/z_20180915090138.jpg)
  ![res](https://github.com/euclala/RCM-X86/blob/master/zphoto1.JPG)
  ![res](https://github.com/euclala/RCM-X86/blob/master/z_switch_board.jpg)
  ![res](https://github.com/euclala/RCM-X86/blob/master/initpintu.jpg)  
  
  
  
  
















