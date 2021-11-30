# DSM7_UHD630
Synology Diskstation UHD630 Driver File -> i915.ko

# Background
Because there is only modded i915 driver for DSM 6.2.3, I made an i915.ko file for DSM 7.0.1 based on the previous principle

## What does it apply to?
1、RedPill DSM 7.0.1 (use loader on https://www.openos.org/threads/dsm-7-0-redpill-108.3536/) 
2、DS918+ 
3、i5-9400, i5-9600k, i7-9700t, i7-9700, i5-10500, i5-10600T,i5-10600K

# Use it at your own risk.

## How to use?
Backup and replace suitable i915.ko to /usr/lib/modules/i915.ko.

3E98 => iGPU UHD 630, High End Desktop 9 Series (i5-9400, i5-9600k, i7-9700t, i7-9700)

9BC8 => iGPU UHD 630, Low End Desktop i5-10500, i5-10600T and lower

9BC5 => iGPU UHD 630, High End Desktop i5-10600K and higher


# Chinese
## 背景
最近折腾黑群7.0.1，显卡一直无法驱动，导致Photos人脸识别没法用，于是基于之前的经验修改了下新版的i915.ko文件，测试了下，i5-9400完美驱动显卡，原版的Photos直接完美使用，plex的硬解也没有问题。

## 用法
下载对应文件夹内的i915.ko文件，备份并替换到/usr/lib/modules/i915.ko路径即可
