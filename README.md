# hik_decrypt
用来存放相关海康威视固件解密
# 相关链接
https://chenx6.github.io/post/hikvision/

https://ipcamtalk.com/threads/mcr-hikvision-packer-unpacker-for-5-3-x-and-newer-firmware.15710/page-15#post-387358

https://sudonull.com/post/64821-Hik-or-hack-NOT-IoT-Security-Using-Hikvision-IP-Cameras-NeoBIT-Blog

https://ipcamtalk.com/threads/encoding-scheme-for-digcap-dav.4174/

https://ipcamtalk.com/search/6361827/?q=HK20&o=date

https://ipcamtalk.com/threads/you-go-hang-zhou-r6-camera-ds-2cd2x42-firmware-encoding-method.11516/#post-110691

https://ipcamtalk.com/threads/hikvision-firmware-tools-change-language-extract-files-and-create-own-firmware.2664/page-32#post-29663

https://ipcamtalk.com/threads/how-to-extract-dav-firmware-files-for-hikvision-cameras.71444/#post-785771

http://www.f0und.icu/article/31.html

# 文件头
SWKH 02KH KH20
# 解密工具
hipack(一个国外大佬开发的解密工具)

hikvision-master(解包原理是将加密固件分为头部和剩余部分 先将头部进行异或处理 然后根据文件头计算出固件的checksum offset filesize filename)

packFirmwareH5(原理和hikvision-master基本一致)

scripts(同上)