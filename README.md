# Lenovo-M710Q-I3-7100/i5-7500T-Hackintosh-EFI-flies
这是联想M710Q迷你小主机的黑苹果EFI文件，经我测试下来这个EFI文件可以启动MacOS10.15（Catalina）-11（BigSur）-12（Monterey,最完美的版本，功能基本都能用）-13（Ventura），本EFI适用于i3-7100和i5-7500T等7代Intel处理器，其他7代U也可以试试。注意：这个文件没有睿频补丁（CPUFriend.kext），四核四线程及以上的 intel CPU 可以选择加， Monterey 及以下可以不加，Ventura 得加，因为我测试下来 Monterey 及以下，风扇声音很小，Ventura 不加睿频补丁 i5-7500T 风扇声音特别大。如果你的第 7 代 i5/i7 遇到进入系统后风扇狂转，声音巨大，请加入睿频补丁（后续我会打包个上传）。目前来说这个 EFI 已经是很完美了，在 Monterey 系统下基本上完美使用。
 Lenovo -M710Q
 CPU : i3-7100/i5-7500T
 内存：DDR4 8GB*2 2666Mhz(最大识别 2400Mhz )
 主板：B250
 硬盘：KIOXIA KBG40ZNS 128G NVMe（这个很重要有些硬盘不兼容 Mac 系统，效果很差，装之前问 AI 你的硬盘兼容 Mac 系统吗）
 网卡&蓝牙：Intel 3160NGW

 可用功能：WIFI（Monterey 有效，其他系统替换对应版本 WiFi 驱动就可以了，再启动界面 Reset  Nvram 就可以了） 蓝牙（定制了 USB） 声音外放 USB 连接 DP 输出（HDMI 转 DP，VGA 转 DP）都可以用，大多数功能都没问题
 不可用功能：睡眠（开机会黑屏比较长时间。睡眠后无法唤醒，只能重启系统，因此不睡眠），隔空投送这些 Mac 特色功能，网卡不支持，这个小主机的是有网卡白名单的，博通的黑苹果网卡是没法用的，最多只能使用 WiFi 功能，无法驱动蓝牙，隔空投送这些功能，除非刷魔改 BIOS 破解网卡白名单。
