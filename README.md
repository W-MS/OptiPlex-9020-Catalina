# OptiPlex - 9020 - Catalina


Tested on：

> * OptiPlex 9020m 


<br/><br/>
You need to run

` setup_var 0x263 0x03 `
and 
` setup_var 0xDA2 0x00 `

in Grub to update DVMT settings first and after everytime you reset your bios.

请在放置EFI前在Grub中修改DVMT设置。默认8Bit的显存容量不足以引导系统启动。

**This command works FOR 9020 ONLY!**

此命令仅对9020有效，在其他电脑上运行可能会损坏BIOS。

**Use this on other model may damage your computer!**

<br/><br/>



FileVault加密不可打开，开启会导致无法启动。

**NEVER** enable FileVault on a hackintosh. 


**其他机型 黑苹果Hackintosh资源 [请访问链接](https://github.com/daliansky/Hackintosh) **
