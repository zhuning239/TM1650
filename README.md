# 创乐博microbit 开发板四位数码管 (TM1650)
用于micro:bit 开发板的四位数码管(TM1650)包  


四位数码管电路，基于microbot扩展板上，为7段四位数码管带点，可以显示数字，支持小数点显示
，内置TM1650驱动芯片，采用IIC总线控制。

编辑: 朱林  
时间: 2020年1月10日  

![](https://raw.githubusercontent.com/microbit-makecode-packages/TM1650/master/icon.png)

## 使用说明

打开你的Makecode 编程环境，在扩展中复制如下链接： 

https://github.com/zhuning239/TM1650  

输入到搜索框进行搜索。

![](https://raw.githubusercontent.com/microbit-makecode-packages/TM1650/master/4-LED.jpg)

## API

- **on()**  
打开显示进行显示.  

- **off()**  
关闭显示.  

- **clear()**  
清除显示内容.  

- **digit(num: number, bit: number)**  
在给定的位置显示数字.  

- **showNumber(num: number)**  
显示数字.  

- **showHex(num: number)**  
显示十六进制数.  

- **showDpAt(bit: number, show: boolean)**  
显示或隐藏点点在给位
位是点点位置，[0 - 3]
显示时，true:会显示DP，false:会隐藏它

- **setIntensity(dat: number)**  
设置显示强度.  

## 案例程序

![](https://raw.githubusercontent.com/microbit-makecode-packages/TM1650/master/demo.jpg)

## License  

MIT

湖南创乐博智能科技有限公司

## Supported targets  

* for PXT/microbit


[湖南创乐博智能科技有限公司](www.loborobot.com)
