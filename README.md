# ElectronBot-Voice

> 这是ElectronBot桌面机器人的语音版
> 
> 原项目地址 https://github.com/peng-zhihui/ElectronBot

> 【更新 2022-04-29】： 新的传感器板子昨晚肝出来了。 今天去打板。这回应该没啥问题。 拜托。 

> 【更新 2022-05-05】： 新的传感器板子调试OK了，这个板子不用烧程序，焊接好调试好插上电脑就是一个USB声卡和麦克风。
> 						接下来就可以调用电脑的音频功能和麦克风接口实现音频功能开发啦！
> 						SDK-DEMO 正在路上。。。
> 	

> 和原项目的区别：
> 
> 版本一： （推荐）
>
> 只有传感器版不一样，主板可以和原项目维持不变。传感器板增加了USB声卡芯片，插上电脑只能编程一个音频设备。
> 同时，这个传感器板子的孔位/IMU方向都是和原项目维持不变的。
>
> 版本二： （学习音频开发）
> 1.只有主板的硬件不一样，其他硬件都一样，如果你使用这个版本的主板，软件部分和原项目也都是兼容的。
> 
> 2.主板上仅将SD卡模块更换为了 WM8978音频模块，其他接口全部兼容。 为了后期也能够扩展本地存储功能，增加了SPI-flash。
> 
> 3.如果要使用语音功能，需要使用本项目中的USB上层通讯协议。
>
> 4.如果有打算学习音频开发的同学可以参考目前的这个硬件。WM8978是很不错的一款CODEC，目前国内也出了不少替换的硬件。比如ES8388之类的。
>


