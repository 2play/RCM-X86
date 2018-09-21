# RCM-X86 chip is a trinket M0 mod chip

## 4line install  (need to AutoRCM)
   RCM-X86 chip VCC -----> switch 3.3V  
   RCM-X86 chip GND -----> switch GND  
   RCM-X86 chip USB D-   -----> switch D-  
   RCM-X86 chip USB D+   -----> switch D+  

## 5line install  (NOT need  AutoRCM)
   RCM-X86 chip VCC -----> switch 3.3V  
   RCM-X86 chip GND -----> switch GND  
   RCM-X86 chip USB D-   -----> switch D-  
   RCM-X86 chip USB D+   -----> switch D+ 
   RCM-X86 chip D0  -----> switch JOY-con Pin10  

## How to flash UF2 file (after install it into the switch)
   * solder a magnetic switch  between the GND and RES  
   * turn off the switch
   * pull in the type-C, connect the switch with the PC
   * Ues the magnet near the magnetic switch (twice at one second)
   * normally it will be a new disk in you PC file explorer

## if you want to bulid you project  
   this is the sch
   The USB Logic IC EN pin is pull down with a 10K res.
   
  ![res](https://github.com/euclala/RCM-X86/blob/master/internalDongle/z_20180915090138.jpg)
  ![res](https://github.com/euclala/RCM-X86/blob/master/internalDongle/zphoto1.JPG)
  ![res](https://github.com/euclala/RCM-X86/blob/master/internalDongle/z_switch%E4%B8%BB%E6%9D%BF%E5%9B%BE_new.jpg)
  
  
  
















