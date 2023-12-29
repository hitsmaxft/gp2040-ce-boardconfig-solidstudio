# gp2040-ce board config for solid studio hitbox a4 

GP2040-CE solidstudio A4 hitbox 的固件
这个板子没有 led ，因此 led 相关 pin 都置空了

主要改动点

* 默认开启输入历史
* 默认开启 display
* 默认启用 FUN 键, 替换掉 Turbo
* 默认开启 PS5 支持 (需要 mayflash ), 占用 pin 0
* 默认 PS4 输入模式

display config

* i2c 0 
* SDA 26
* SCL 27
* speed 400000

bin mapping

* function: 14
* usb passthrough :  1
* turbo led: -1

