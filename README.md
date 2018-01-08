# fastboot

unlock or lock bootloader for vivo(bbk) devices

步步高手机解锁bootloader专用fastboot

## 编译

准备一套AOSP编译环境，切换到AOSP主目录下，执行`lunch`命令等准备工作。

```
$ cd system/core
$ git clone git@github.com:ppma/fastboot.git
$ mm
```

## 用法

1. 解锁命令

        fastboot bbk unlock_vivo

2. 上锁命令

        fastboot bbk lock_vivo
