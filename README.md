## 日志汇总
* 注意,有部分版本硬件底层bootloader烧录有误,导致无法进入U盘模式.  
  如有此现象请与供应商联系.或者使用我提供的项目文件,用arduino编程软件进行烧录
## RCM-X86注入工具升级目录介绍
  \internalDongle  内置嵌入式注入器.  
  \V1pcb   第一版,超级电容,黑色PCB电路板版本  
  \V2BAT   第二版,带灰色外壳,使用电池的版本  
  \V3      第二版分支,修改部分引脚功能,生成日期为2018-08-01以后.  
  
# Switch dongle RCM-X86 
RCM-X86 is MOD of Arduino Zero, 
It will send the Payload file to  NINTENDO SWITCH to run the Custom Firmware.(like Atmosphere,TX OS or others)
It was easy to change the dongle Firmware by PC,MAC or OS, using the UF2 files.

we have two version hardware:
* external dongle (with a battery, chagre 30minutes can payload about 500 times in 30 days.)
* internal dongle (solder it into the switch with 5-6 wire install,auto payload when the switch power on)




# RCM-X86注入工具升级教程:
(支持WIN7,WIN10,MAC,Linux)
* 通过microUSB线(旧版本),或者USB口接到电脑
* 接到电脑后,双击RES 复位按钮.
* 此时会在我的电脑显示一个名为RCM 的U盘,
* 把相应的文件升级文件(大气层HBL或者OS,)拷贝进去即可，
  拷贝进去后会自动重启，拔出就可以使用了


## 版本说明(刷错版本不会损坏硬件,重新刷即可)
### 黑色超级电容PCB版本(PCB version ):
* \V1pcb\V1pcbHBL.uf2  (大气层HBL引导版本3.2)
* \V1pcb\V1pcbOS.uf2   (TXOS引导,版本1.0)

### 带外壳电池版本(battery version):
* \V2BAT\HBL32.uf2  (大气层HBL引导版本3.2)
* \V2BAT\TXOS.uf2   (TXOS引导,版本1.0)
