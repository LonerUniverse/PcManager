------------------------------------------------------------
本代码来自[金山卫士开源计划 201103] http://code.ijinshan.com/
http://code.ijinshan.com/download/LIB4pcmanager.tbz
下载后,将其中子目录覆盖 pcmanager 目录;
即:LIB4pcmanager
├── lib
└── src
将 lib 和 src 目录,覆盖 pcmanager 目录中的对应同名目录
------------------------------------------------------------


## 编译说明
使用vs2005 sp2 编译，需要windows sdk 7.1,代码中原来使用的sdk版本是6.1。不太好找了。
代码在win7 sp1， win8.1， win10 上编译均可。

bdev分支整理了下工程文件。独立的工程文件放在 oss 目录下。
https://github.com/5455945/PcManager/tree/bdev/oss

包括:
ksm        #0003 金山卫士主界面 2.1  bdev/oss/ksm/sln/KSafeMain.sln
karpfw     #0005 卫士ARP防火墙       bdev/oss/karpfw/sln/karpfw.sln
bksafevul  #0006 漏洞扫描器          bdev/oss/sysopt/sln/bksafesysopt.sln
sysopt     #0007 系统优化之开机加速  bdev/oss/sysopt/sln/bksafesysopt.sln
ppro       #0008 隐私保护器          bdev/oss/ppro/sln/PrivacyProtectionGUI.sln
kclear     #0009 垃圾清理            bdev/oss/kclear/sln/kclear.sln

金山卫士主界面
https://github.com/5455945/PcManager/blob/bdev/doc/img/doc_img_ksafe.png

卫士ARP防火墙
https://github.com/5455945/PcManager/blob/bdev/doc/img/doc_img_karpfw.png

漏洞修复
https://github.com/5455945/PcManager/blob/bdev/doc/img/doc_img_beikesafevul.png

系统优化
https://github.com/5455945/PcManager/blob/bdev/doc/img/doc_img_bksafesysopt.png

隐私保护
https://github.com/5455945/PcManager/blob/bdev/doc/img/doc_img_PrivacyProtection.png

垃圾清理
https://github.com/5455945/PcManager/blob/bdev/doc/img/doc_img_kclrshell.png


主工程的sln文件在PcManager\sln下。是ksafe.sln，需要先编译commonlib.sln
release可运行，效果如下:
https://github.com/5455945/PcManager/blob/bdev/doc/img/doc_img_ksafe.png
