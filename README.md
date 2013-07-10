Kernel sources for iMito QX1 rk3188 device. 

=========

Kernel Source - RK3188 - modded to work in imito QX1 look at arch/arm/mach-rk3188/board-rk3188-box.c there are some values in act8846 PMU changed to make wifi work in qx1, if you want to use this sources in a different stick, please revert those changes.


Andy, from rikomagic has done it again. Thanks to him

For now I am working in a full usable kernel for android. 

Sources taken from Galland, thanks to him too for his work in this sources.

Thanks to Sam321 for share the overclock for this devices.

conf.leolas.1 is  a test config for a 1080p kernel. BT didnt work yet. CPU and RAM are overclocked.

