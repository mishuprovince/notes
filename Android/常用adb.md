# 常用adb

## adb 打开app

adb shell am start -W -n live.space365.roomboard/apps.space365.standard.roomboard.activity.MainActivity

## adb 列出包名

adb  shell pm 

## adb切换设备

//列出设备名

adb devices 

//adb -s 设备名 shell

## 远程连接adb

adb connect ip地址

adb disconnect ip地址

## 截屏

adb screencap -p sdcard/1.png

## 设置界面





## 设备详情



## 导入文件夹里的子文件

adb push Desktop/zjusom/. /sdcard/Space365/zjusom

