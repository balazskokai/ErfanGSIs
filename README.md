# Erfan GSIs OEM's and AOSP Porting Script Project

### You too, reading this, yes you can Fork this for your use but don't forget credits kek.

## Downloads "NipponGSIs"
Download links: [https://sourceforge.net/projects/anantgsi/files/ ](https://sourceforge.net/projects/nugu/files/) 
Join us in telegram!: https://t.me/nugugroup  
For updates follow channel: https://t.me/nugupdates 

## Requirements
    Linux

## Released GSIs "ErfanGSIs"
Download links: https://mirrors.lolinet.com/firmware/gsi/  
XDA thread: https://forum.xda-developers.com/project-treble/trebleenabled-device-development/pie-erfan-gsi-ports-t3906486  
Telegram group: https://t.me/ErfanGSIs  
Telegram channel: https://t.me/ErfanGSI  

## How to use? follow below instructions

### Download tools
```
git clone --recurse-submodules https://github.com/erfanoabdi/ErfanGSIs.git
cd ErfanGSIs
```

### For setting up requirements
    bash setup.sh

### Generating GSI from stock firmware URL
Example: for making OxygenOS of oneplus 7 pro firmware, you can use this command inside ErfanGSIs folder
```
./url2GSI.sh https://oxygenos.oneplus.net/OnePlus7ProOxygen_21.O.07_OTA_007_all_1905120542_fc480574576b4843.zip OxygenOS
```
check url2GSI.sh for more info
