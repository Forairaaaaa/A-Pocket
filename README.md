# A-Pocket - 基于全志A133的掌上终端

![渲染.5.5](https://github.com/Forairaaaaa/A-Pocket/blob/main/README.assets/%E6%B8%B2%E6%9F%93.5.5.png?raw=true)

视频介绍：[【开源】 自 制 手 机 ：【一】PDA？_哔哩哔哩_bilibili](https://www.bilibili.com/video/BV11t4y1W7DJ#reply114174036736)

虽然是奔着DIY手机去的，不知咋的就做成PDA了（

由于屏幕特殊，性价比极低，不建议复刻除核心板外的其他东西。

#### 硬件组成：

- **基于全志A133邮票孔模块设计的核心板**：板载USB-OTG、USB-Debug、带MIC的3.5mm耳机接口、扬声器接口、电池接口、MPU6050、RTC等，单板即可满足正常工作。另外由板对板引出显示屏接口和USB接口供拓展。未引出A133提供的摄像头接口。

- **拓展屏幕和USB-HUB的拓展板**：板载LCD背光电路、USB5V的DC-DC升压电路和USB-HUB电路等。
- CPU散热：背壳贴石墨烯，由导热硅垫传热

#### 物件参考链接：

- [HelperBoard A133核心板（安卓10、ub，全志A133，内置5G-WIFI）-淘宝网 (taobao.com)](https://item.taobao.com/item.htm?spm=a1z09.2.0.0.fae32e8dKwhqRd&id=646476965103&_u=o2bdtj0f16a5)
- [适用智力快车儿童视频学习机早教机锂电池3.7V大容量10000mah充电-tmall.com天猫](https://detail.tmall.com/item.htm?id=613087896696&spm=a1z09.2.0.0.fae32e8dKwhqRd&_u=o2bdtj0fb0d2)   955565
- [3.8寸IPS液晶显示模块 电容触摸屏1024*600 JD9168, LVDS接口-tmall.com天猫](https://detail.tmall.com/item.htm?id=652122490131&spm=a1z09.2.0.0.fae32e8dKwhqRd&_u=o2bdtj0f7da0)

#### 缺点：

屏幕性价比低，屏占比低，核心模组也比较贵

板对板连接导致厚度大，扬声器音质很烂

#### 待改进：

改用量产的手机MIPI屏幕，但需要学写驱动（泪目

主控想改用RK3399或RK3588，但价格~~

