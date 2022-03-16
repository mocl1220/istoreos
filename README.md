# iStoreOS 问题收集跟自动化编译

## 介绍

iStoreOS 是提供给入门级 OpenWRT 爱好者使用的固件，主要是为了简化操作，避免入门用户走进太多坑。其中包括：

* 提供拨号向导，简化拨号流程
* 简化 DNS 配置
* 简化硬盘格式化流程（坑最多）
* 提供 Samba 设置向导（原始的 OpenWRT 没提供 Samba 密码设置的功能）
* Docker 配置向导（未完成）
* 远程下载设置向导（未完成）

iStoreOS 还提供了软件中心：iStore，尽可能解决插件之间的依赖关系，可让大家自由自在安装插件。

除此之外，为了方便大家折腾不出问题，避免掉坑里，我们还做了很多防坑操作，比如 ARS2 固件里面有：

* 救援模式，即是固件完全刷坏，也可以进入救援模式救回来
* 沙箱模式，通过 U 盘进入沙箱模式，不管如何安装插件搞坏了系统，拔掉 U 盘就回到上个状态

当然 iStoreOS 还有整套易有云 APP 的协助，可以远程管理系统，远程访问插件，远程访问文件，备份相册，看电影等。满足了很多用户折腾半天都搞不定的场景需求。
