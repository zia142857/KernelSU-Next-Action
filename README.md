# 测试一加6 氢11
# KernelSU-Next-Action

只有clang-r383902b和谷歌GCC 4.9,支持编译，4.19以下的绝大多数内核，非gki内核
支持一键集成KernelSU-Next,LXC,Kali-Nethunter
使用anykernel3,magiskboot打包内核

使用方法

Fork 本仓库到你的储存库然后按照以下内容编辑 config.env，之后点击`Star`或`Action`，在左侧可看见`Build Kernel`选项，点击选项会看见右边的大对话框的上面会有`Run workflows`点击它会启动构建。

一般来说主要修改

### Kernel Source

修改为你的内核仓库地址

例如: https://github.com/Diva-Room/Miku_kernel_xiaomi_wayne

### Kernel Source Branch

修改为你的内核分支

例如: TDA

### Kernel Config

修改为你的内核配置文件名

例如: vendor/wayne_defconfig


其他的按需求修改。


## 感谢
- [rifsxd](https://github.com/rifsxd/KernelSU-Next)
- [AnyKernel3](https://github.com/osm0sis/AnyKernel3)
- [KernelSU](https://github.com/tiann/KernelSU).
- [xiaoleGun](https://github.com/xiaoleGun/KernelSU_Action)

