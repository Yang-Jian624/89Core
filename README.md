# 89Core
八九玄功

道家无上法门

阴数最大为八，阳数最大为九，八九相乘即为道教最大之数，故天地有九宫八卦，七十二候。. 不仅是修成金丹大道之法门，其中包含诸般神通法术。

有云：修成八九玄中妙，任尔纵横在世间。

---

## OS

### Build

#### Buildroot

`Buildroot` 是 Linux 平台上一个构建嵌入式 Linux 系统的框架。整个 `Buildroot` 是由 `Makefile(*.mk)`  脚本和 `Kconfig(Config.in)` 配置文件构成的。你可以和编译 Linux 内核一样，通过 `buildroot`  配置，`menuconfig` 修改，编译出一个完整的可以直接烧写到机器上运行的 Linux 系统软件（包含 `boot`、`kernel`、`rootfs`  以及 `rootfs` 中的各种库和应用程序）。

制作根文件系统有三大神器之一，其他俩没它好使。

### boot loader

#### U-Boot

https://www.denx.de/wiki/U-Boot/

Das U-Boot **是一个主要用于嵌入式系统的引导加载程序**



#### coreboot

https://www.coreboot.org/

原名**`LinuxBIOS`**。是一个旨在取代计算机PC中专有固件（`BIOS`或`UEFI`）的软件项目

<img src="https://www.coreboot.org/assets/images/banner.svg"  align='left'/>



#### LinuxBoot

https://www.linuxboot.org/

`LinuxBoot` 是现代服务器的固件，它用 Linux 内核和运行时替换特定的固件功能，如 `UEFI DXE` 阶段。

![Linux as Firmware](https://www.linuxboot.org/images/linuxboot_info.png)

#### Minimum Platform

https://www.intel.cn/content/www/cn/zh/developer/articles/tool/minimum-platform-architecture-open-source-uefi-firmware-for-intel-based-platforms.html

Minimum Platform: Open Source UEFI Firmware for Intel® Architecture Platforms

UEFI界中的乐高

![Minimum Platform](https://www.intel.cn/content/dam/develop/external/us/en/images/minplatform-intelfsp-stack-825417.png)

### vs

![](https://pic1.zhimg.com/80/v2-22f96427905adab2d585890d5f11f0b4_720w.jpg)

---

## 参考

- [字节跳动首发云固件，成功实现服务器LinuxBoot产品化落地](https://page.om.qq.com/page/OclAl9DthdvYPEF_CVPfs79A0)
- https://zhuanlan.zhihu.com/p/366092098
- 